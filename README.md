# MYDESIGN.MD

**Extract a complete design system from any live website URL.**

Paste a public URL → get back a structured `DESIGN.md`, `design-tokens.json` (W3C DTCG), CSS custom properties, Tailwind v4 config, and a design audit report. No install. No Figma access required.

[![npm version](https://img.shields.io/npm/v/mydesignmd.svg)](https://www.npmjs.com/package/mydesignmd)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/web-mydesignmd.com-black)](https://www.mydesignmd.com)

---

## Why this exists

[awesome-design-md](https://github.com/VoltAgent/awesome-design-md) curates high-quality `DESIGN.md` files for well-known brands. If the site you need is Stripe or Linear, you're covered. If it isn't — you're on your own.

MYDESIGN.MD makes that output available for **any public URL, on demand**. Same quality bar. No waiting for someone to manually curate the brand you actually need.

→ **[Generate a DESIGN.md for any URL at mydesignmd.com](https://www.mydesignmd.com)**

---

## Extracted design systems

### AI & Developer Platforms
- [Anthropic](./examples/anthropic.md) — anthropic.com
- [Cursor](./examples/cursor.md) — cursor.com
- [ElevenLabs](./examples/elevenlabs.md) — elevenlabs.io
- [Hume AI](./examples/hume-ai.md) — hume.ai
- [Microsoft AI](./examples/microsoft-ai.md) — microsoft.ai
- [Modal](./examples/modal.md) — modal.com
- [Replit](./examples/replit.md) — replit.com
- [Supabase](./examples/supabase.md) — supabase.com

### Crypto & Web3
- [Caldera](./examples/caldera.md) — caldera.xyz

### Health & Fitness
- [Whoop](./examples/whoop.md) — whoop.com

### Lifestyle & Retail
- [Le Labo Fragrances](./examples/le-labo.md) — lelabofragrances.com

### Media & Publishing
- [Medium](./examples/medium.md) — medium.com

---

## What each output contains

Every extraction returns a full design system package:

| Artifact | Format | Contents |
|---|---|---|
| `DESIGN.md` | Markdown | Colors, typography, spacing, components, design rationale |
| `design-tokens.json` | W3C DTCG | Machine-readable token map for Style Dictionary, Tokens Studio |
| `variables.css` | CSS | Custom properties, ready to drop into any stylesheet |
| `tailwind.config.js` | JS | Tailwind v4 `@theme` block |
| `audit.md` | Markdown | Inconsistencies in the source CSS |

---

## Generate your own

Any public URL → full design system package in a few minutes.

**Web:** [mydesignmd.com](https://www.mydesignmd.com) — no install required

**CLI:**
```bash
npx mydesignmd extract https://your-site.com
```

**API:**
```bash
curl -X POST https://api.mydesignmd.com/v1/extract \
  -H "Authorization: Bearer YOUR_KEY" \
  -H "Content-Type: application/json" \
  -d '{"url": "https://your-site.com"}'
```

---

## Use with AI coding agents

`DESIGN.md` is plain markdown — every major AI coding agent can load it as persistent context.

| Agent | Where to add |
|---|---|
| **Claude Code** | `@DESIGN.md` in `CLAUDE.md` |
| **OpenAI Codex** | `@DESIGN.md` in `AGENTS.md` |
| **Cursor** | `.cursor/rules/design-tokens.mdc` |
| **GitHub Copilot** | `.github/copilot-instructions.md` |
| **Windsurf** | `.windsurfrules` |

Full setup guide → [design-tokens-for-ai-coding-agents](https://www.mydesignmd.com/design-tokens-for-ai-coding-agents)

---

## Honest limitations

- **Login-gated sites** — the extractor sees what an unauthenticated browser sees
- **Production drift** — output reflects shipped CSS, not Figma intent. Usually this is what you want.
- **No rationale extraction** — the "why" is inferred from visual evidence; review it with your team
- **Heavy JS interaction** — sites that require user interaction before rendering may produce incomplete output

---

## Related

- [What is a DESIGN.md file?](https://www.mydesignmd.com/what-is-design-md)
- [How to extract a design system from any website](https://www.mydesignmd.com/how-to-extract-a-design-system-from-any-website)
- [Design tokens for AI coding agents](https://www.mydesignmd.com/design-tokens-for-ai-coding-agents)
- [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) — curated collection of hand-crafted DESIGN.md files

---

MIT License
