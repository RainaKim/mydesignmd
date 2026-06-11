# MYDESIGN.MD API Reference

Extract a complete design system from any public URL via REST API.

**Base URL:** `https://api.mydesignmd.com`

---

## Authentication

All API requests must include an API key in the `Authorization` header:

```
Authorization: Bearer mdsk_your_api_key_here
```

### Get an API key

1. Sign in at [mydesignmd.com](https://www.mydesignmd.com)
2. Go to **Settings → API Keys**
3. Click **Create key**, give it a name, copy it immediately — it's shown once

API keys start with `mdsk_` and are 53 characters long. Keep them secret — treat them like passwords.

### Key security best practices

- Never commit API keys to source control
- Use environment variables: `MYDESIGNMD_API_KEY=mdsk_...`
- Create one key per project so you can revoke individually
- Rotate keys if you suspect exposure

---

## Manage API keys

### Create a key

```bash
POST /v1/api-keys
Authorization: Bearer <session_token>
Content-Type: application/json

{"name": "my-project"}
```

Response (plain key returned **once only**):

```json
{
  "key_id": "key_abc123",
  "key_prefix": "mdsk_abc1234",
  "name": "my-project",
  "created_at": "2026-06-11T10:00:00Z",
  "plain_key": "mdsk_abc1234567890abcdef1234567890abcdef1234567890abcdef"
}
```

> **Note:** `plain_key` only appears in the create response. Store it immediately — you cannot retrieve it again.

### List keys

```bash
GET /v1/api-keys
Authorization: Bearer <session_token>
```

```json
{
  "keys": [
    {
      "key_id": "key_abc123",
      "key_prefix": "mdsk_abc1234",
      "name": "my-project",
      "created_at": "2026-06-11T10:00:00Z",
      "last_used_at": "2026-06-11T14:32:00Z"
    }
  ]
}
```

### Revoke a key

```bash
DELETE /v1/api-keys/{key_id}
Authorization: Bearer <session_token>
```

Returns `204 No Content` on success.

---

## Submit an extraction job

```bash
POST /v1/design-jobs
Authorization: Bearer mdsk_your_api_key_here
Content-Type: application/json
```

**Request body:**

| Field | Type | Required | Description |
|---|---|---|---|
| `url` | string | ✅ | Public URL to extract. Must be accessible without login. |
| `forceRefresh` | boolean | | Skip cache and run a fresh extraction. Default: `false` |

**Example:**

```bash
curl -X POST https://api.mydesignmd.com/v1/design-jobs \
  -H "Authorization: Bearer mdsk_your_api_key_here" \
  -H "Content-Type: application/json" \
  -d '{"url": "https://stripe.com"}'
```

**Response `202 Accepted`:**

```json
{
  "jobId": "job_abc123def456",
  "status": "queued",
  "phase": "queued",
  "inputUrl": "https://stripe.com",
  "createdAt": "2026-06-11T10:00:00Z"
}
```

---

## Poll job status

```bash
GET /v1/design-jobs/{jobId}
Authorization: Bearer mdsk_your_api_key_here
```

**Response:**

```json
{
  "jobId": "job_abc123def456",
  "status": "done",
  "phase": "done",
  "inputUrl": "https://stripe.com",
  "createdAt": "2026-06-11T10:00:00Z",
  "artifactUrls": {
    "design.md": "/v1/design-jobs/job_abc123def456/artifact/design.md",
    "design-tokens.json": "/v1/design-jobs/job_abc123def456/artifact/design-tokens.json",
    "variables.css": "/v1/design-jobs/job_abc123def456/artifact/variables.css",
    "tailwind.config.js": "/v1/design-jobs/job_abc123def456/artifact/tailwind.config.js",
    "audit.md": "/v1/design-jobs/job_abc123def456/artifact/audit.md"
  }
}
```

**Status values:**

| Status | Meaning |
|---|---|
| `queued` | Waiting for an agent slot |
| `running` | Extraction in progress |
| `done` | Complete — artifacts are ready |
| `failed` | Extraction failed — check `error` field |

---

## Download artifacts

Once `status === "done"`, fetch any artifact by appending the relative `artifactUrls` path to the base URL:

```bash
curl https://api.mydesignmd.com/v1/design-jobs/job_abc123def456/artifact/design.md \
  -H "Authorization: Bearer mdsk_your_api_key_here"
```

**Available artifacts:**

| File | Format | Contents |
|---|---|---|
| `design.md` | Markdown | Colors, typography, spacing, components, design rationale |
| `design-tokens.json` | W3C DTCG JSON | Machine-readable token map for Style Dictionary, Tokens Studio |
| `variables.css` | CSS | Custom properties, ready to drop into any stylesheet |
| `tailwind.config.js` | JS | Tailwind v4 `@theme` block |
| `audit.md` | Markdown | Inconsistencies found in the source CSS |

---

## Complete example — submit and poll

### Shell

```bash
#!/bin/bash
API_KEY="mdsk_your_api_key_here"
BASE="https://api.mydesignmd.com"

# Submit
JOB=$(curl -s -X POST "$BASE/v1/design-jobs" \
  -H "Authorization: Bearer $API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"url": "https://stripe.com"}')

JOB_ID=$(echo $JOB | jq -r '.jobId')
echo "Job started: $JOB_ID"

# Poll until done
while true; do
  STATUS=$(curl -s "$BASE/v1/design-jobs/$JOB_ID" \
    -H "Authorization: Bearer $API_KEY" | jq -r '.status')
  echo "Status: $STATUS"
  if [ "$STATUS" = "done" ] || [ "$STATUS" = "failed" ]; then
    break
  fi
  sleep 5
done

# Download DESIGN.md
curl -s "$BASE/v1/design-jobs/$JOB_ID/artifact/design.md" \
  -H "Authorization: Bearer $API_KEY" \
  -o DESIGN.md

echo "Saved DESIGN.md"
```

### Node.js

```js
const API_KEY = process.env.MYDESIGNMD_API_KEY;
const BASE = 'https://api.mydesignmd.com';

async function extractDesignSystem(url) {
  // Submit job
  const res = await fetch(`${BASE}/v1/design-jobs`, {
    method: 'POST',
    headers: {
      'Authorization': `Bearer ${API_KEY}`,
      'Content-Type': 'application/json',
    },
    body: JSON.stringify({ url }),
  });
  const { jobId } = await res.json();

  // Poll until done
  while (true) {
    const job = await fetch(`${BASE}/v1/design-jobs/${jobId}`, {
      headers: { 'Authorization': `Bearer ${API_KEY}` },
    }).then(r => r.json());

    if (job.status === 'done') return job;
    if (job.status === 'failed') throw new Error(job.error);
    await new Promise(r => setTimeout(r, 3000));
  }
}

// Usage
const job = await extractDesignSystem('https://stripe.com');
const designMd = await fetch(
  `${BASE}${job.artifactUrls['design.md']}`,
  { headers: { 'Authorization': `Bearer ${API_KEY}` } }
).then(r => r.text());

console.log(designMd);
```

### Python

```python
import os, time, requests

API_KEY = os.environ["MYDESIGNMD_API_KEY"]
BASE = "https://api.mydesignmd.com"
HEADERS = {"Authorization": f"Bearer {API_KEY}"}

def extract_design_system(url: str) -> dict:
    # Submit
    job = requests.post(
        f"{BASE}/v1/design-jobs",
        headers=HEADERS,
        json={"url": url},
    ).json()
    job_id = job["jobId"]

    # Poll
    while True:
        job = requests.get(f"{BASE}/v1/design-jobs/{job_id}", headers=HEADERS).json()
        if job["status"] == "done":
            return job
        if job["status"] == "failed":
            raise RuntimeError(job.get("error", "Job failed"))
        time.sleep(3)

# Usage
job = extract_design_system("https://stripe.com")
design_md = requests.get(
    f"{BASE}{job['artifactUrls']['design.md']}",
    headers=HEADERS,
).text
print(design_md)
```

---

## Error responses

All errors follow this shape:

```json
{
  "detail": "Human-readable error message"
}
```

| Status | Meaning |
|---|---|
| `400` | Invalid request — bad URL or missing field |
| `401` | Missing or invalid API key |
| `402` | Insufficient credits |
| `404` | Job not found |
| `429` | Rate limit exceeded — slow down |
| `503` | Service temporarily unavailable |

---

## Rate limits

| Tier | Requests/min | Concurrent jobs |
|---|---|---|
| Free | 5 | 1 |
| Pro | 30 | 3 |
| Team | 120 | 10 |

When you hit a rate limit, the response is `429` with a `Retry-After` header indicating seconds to wait.

---

## Credits

Each extraction costs **3 credits**. Credits are included with all plans and can also be purchased as add-on packs.

Check your balance at [mydesignmd.com/settings](https://www.mydesignmd.com/settings).

---

## CLI

Prefer the command line? Use the official CLI — no API key management needed, it reads from your signed-in session:

```bash
npx mydesignmd generate https://stripe.com --out DESIGN.md
```

Full CLI docs: `npx mydesignmd --help`

---

## SDK

TypeScript and Python SDKs are available in the `packages/` directory of the monorepo. See `packages/sdk-ts` and `packages/sdk-py` for installation and usage.

---

Questions? [hello@mydesignmd.com](mailto:hello@mydesignmd.com)
