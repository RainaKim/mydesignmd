---
version: alpha
name: "Cursor: The best coding agent"
description: Built to make you extraordinarily productive, Cursor is the best coding agent.
colors:
  primary: "#14120b"
  color.surface: rgb(247, 247, 244)
  color.surface.dark: "#14120b"
  color.ink: "#26251e"
  color.text.muted: "#26251ebf"
typography:
  font.body:
    fontFamily: CursorGothic, system-ui
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  font.body.lg:
    fontFamily: CursorGothic, system-ui
    fontSize: 22px
    fontWeight: 400
    lineHeight: 1.5
  font.ui:
    fontFamily: var(--font-mono), ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.5
  font.caption:
    fontFamily: CursorGothic, system-ui
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  font.heading.md:
    fontFamily: CursorGothic, system-ui
    fontSize: 26px
    fontWeight: 400
    lineHeight: 1.2
  font.display.md:
    fontFamily: CursorGothic, system-ui
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.05
  font.heading.lg:
    fontFamily: CursorGothic, system-ui
    fontSize: 33.75px
    fontWeight: 600
    lineHeight: 1.2
rounded:
  radius.2xs: 2px
  radius.xs: 4px
  radius.0: 0
  radius.10px: 10px
  radius.3-40282e38px: 3.40282e38px
  radius.3px: 3px
  radius.50: 50%
  radius.6px: 6px
shadows:
  shadow.0-0-0-2px-var-color-bg-0-0-0-4px-var-color-accent: 0 0 0 2px var(--color-bg), 0 0 0 4px var(--color-accent)
  shadow.0-0-0-2px-var-color-warning: 0 0 0 2px var(--color-warning)
  shadow.0-0-0-3px-var-color-bg-0-0-0-5px-var-color-success: 0 0 0 3px var(--color-bg), 0 0 0 5px var(--color-success)
  shadow.0-0-8px-var-color-success: 0 0 8px var(--color-success)
  shadow.invert: invert()
  shadow.none: none
  shadow.var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
  shadow.var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow)
components:
  primary-button:
    backgroundColor: rgb(38, 37, 30)
    textColor: rgb(247, 247, 244)
    rounded: 3.35544e+07px
    padding: 5.6px 10.5px
    typography: CursorGothic
  secondary-outline-button:
    backgroundColor: rgba(0, 0, 0, 0)
    textColor: rgb(38, 37, 30)
    rounded: 3.40282e38px
  navigation-link:
    backgroundColor: rgba(0, 0, 0, 0)
    textColor: rgb(38, 37, 30)
    rounded: 0px
  toggle-button:
    backgroundColor: var(--color-bg-secondary)
    textColor: var(--color-text-secondary)
    rounded: 6px
  secondary-button:
    backgroundColor: rgb(242, 241, 237)
    textColor: rgb(38, 37, 30)
    rounded: 4px
    padding: 12.5625px 14.0625px
    typography: CursorGothic
sectionMap:
  header:
    background: rgb(247, 247, 244)
    text: rgb(38, 37, 30)
    border: none
    media: n/a
    layout: full-width container with content contained within page max-width
  hero:
    background: rgb(247, 247, 244)
    text: rgb(38, 37, 30)
    border: none
    media: n/a
    layout: full-width section with centered content
  content-sections-general:
    background: rgb(247, 247, 244)
    text: rgb(38, 37, 30)
    border: none
    media: mixed (images, videos, interactive demos)
    layout: full-width or max-width content container with consistent vertical padding
  changelog-recent-highlights:
    background: rgb(247, 247, 244)
    text: rgb(38, 37, 30)
    border: none
    media: user avatars (small)
    layout: max-width content container with consistent vertical padding
  footer:
    background: rgb(247, 247, 244)
    text: rgb(38, 37, 30)
    border: none
    media: n/a
    layout: max-width container with a multi-column grid for links
buildTokens:
  layout.content-max-width: 1300px
  layout.page-horizontal-padding: 20px
  layout.section-vertical-padding-default: 67.2px
  layout.section-vertical-padding-hero: 112px (top) / 67.2px (bottom)
  layout.nav-height: 52px
  layout.component-gap-small: 8px
  layout.border-radius-pill: 3.40282e38px
---

# Cursor: The best coding agent — Style Reference
> developer-focused, disciplined, high-contrast, productivity-oriented, precise

**Theme:** dark

## Overview

Cursor is a coding agent optimized for developer productivity. The interface prioritizes legibility, direct interaction patterns, and minimal cognitive overhead. Every design decision serves a single goal: removing friction from the development workflow.

The system balances powerful AI-assisted capabilities with a controlled, predictable interface. Design choices reflect the tool's purpose—accelerating code authorship without introducing unnecessary visual complexity.

**Voice:** headlines=confident_and_direct; body=technical_and_clear; microcopy=concise_imperative; ctas=action_oriented

## Colors

### Color Philosophy

Cursor's color system builds atmosphere through surface tones before decorative fills. The near-white background (rgb(247, 247, 244)) and ink-dark foreground (#26251e) establish a readable, low-fatigue working environment. Transparency and subtle alpha channels maintain visual hierarchy without adding chromatic noise.

Surface colors function as environmental anchors rather than decorative swatches. Text tokens maintain strict role separation: primary ink, muted text (#26251ebf at 75% opacity), and contextual states never collapse into an ambiguous gray scale.

### Token Roles

#### Brand & Accent
- **{colors.color.surface}** (`#0009`): accent.

#### Surface
- **{colors.color.surface}** (`rgba(237, 236, 236, 0.08)`): background.
- **{colors.color.surface.dark}** (`#14120b`): background.
- **{colors.color.surface}** (`rgb(247, 247, 244)`): background.

#### Text
- **{colors.color.ink}** (`rgb(38, 37, 30)`): foreground.
- **{colors.color.ink}** (`rgba(237, 236, 236, 0.55)`): foreground.
- **{colors.color.ink}** (`#edecec`): foreground.
- **{colors.color.ink}** (`#26251e`): foreground.
- **{colors.color.text.muted}** (`#26251ebf`): foreground.

## Typography

### Typography Principles

CursorGothic and the monospace stack (Berkeley Mono or system fallbacks) form two parallel type systems. CursorGothic handles all interface copy, marketing content, and navigation—maintaining a single voice across contexts. The monospace stack appears exclusively in code blocks, terminal output, and file-path annotations, reinforcing the boundary between prose and syntax.

Type hierarchy is role-driven, not decorative. Headlines, utility labels, and call-to-action copy maintain distinct postures: headlines use larger sizes (33.75px–36px) with restrained weight (400–600), button labels lock to 15px at weight 500, and metadata/captions sit at 14px weight 400. Line-height variation (1.05 for display text, 1.5 for body) optimizes each context for scanning or sustained reading.

### Font Family

- **CursorGothic, system-ui**.

- **CursorGothic, system-ui**.

- **CursorGothic, system-ui**.

- **CursorGothic, system-ui**.

- **CursorGothic, system-ui**.

- **CursorGothic, system-ui**.

- **var(--font-mono), ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace**.

- **CursorGothic, system-ui**.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 16px | 400 | 1.5 |  |  |
| {typography.font.body.lg} | 22px | 400 | 1.5 |  |  |
| {typography.font.ui} | 15px | 500 | 1.0 |  |  |
| {typography.font.caption} | 14px | 400 | 1.5 |  |  |
| {typography.font.heading.md} | 26px | 400 | 1.2 |  |  |
| {typography.font.display.md} | 36px | 400 | 1.05 |  |  |
| {typography.font.ui} | 14px | 500 | 1.5 |  |  |
| {typography.font.heading.lg} | 33.75px | 600 | 1.2 |  |  |

### Principles

- **Body default**: use `CursorGothic, system-ui`; size `16px`; weight `400`.

- **Body large**: use `CursorGothic, system-ui`; size `22px`; weight `400`.

- **Button text**: use `CursorGothic, system-ui`; size `15px`; weight `500`.

- **Caption / Metadata**: use `CursorGothic, system-ui`; size `14px`; weight `400`.

- **Card title**: use `CursorGothic, system-ui`; size `26px`; weight `400`.

- **Code / Pre**: use `var(--font-mono), ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace`; size `14px`; weight `400`.

- **Hero / primary display headline**: use `CursorGothic, system-ui`; size `36px`; weight `400`.

- **Section title**: use `CursorGothic, system-ui`; size `33.75px`; weight `600`.

## Layout

### Composition Principles

Cursor pages are architected as named, semantically distinct sections—header, hero, content blocks, changelog highlights, footer—each with its own surface, text treatment, and media handling. This approach prevents one-size-fits-all containers from diluting contextual clarity.

The hero section opens with elevated vertical padding (112px top / 67.2px bottom), while subsequent sections settle into a consistent 67.2px rhythm. Horizontal padding (20px) maintains breathing room within the 1300px content max-width, preventing text from colliding with viewport edges on smaller screens.

Full-bleed sections break the content well when showcasing product demos or visual narratives, using `calc(50% - 50vw)` margin techniques to extend to viewport edges while preserving centered interior content.

### Rhythm

Vertical spacing follows a deliberate cadence: the hero announces itself with asymmetric padding (more air above than below), while general content sections maintain balanced 67.2px top-and-bottom padding. Navigation locks to 52px height, and small component gaps standardize at 8px.

This rhythm creates predictable content flow without rigid uniformity—sections breathe at different rates depending on their narrative weight.

### Implementation Notes

Container widths target 1300px max for primary content, with observed secondary breakpoints at 1140px and 1380px for nested grids or constrained text blocks. The layout relies heavily on CSS custom properties (`--color-theme-fg`, `--color-bg-secondary`) for dynamic theming, enabling seamless light/dark mode transitions.

Utility-first styling (Tailwind CSS patterns) dominates the implementation. Developers should watch for explicit `calc(50% - 50vw)` margins on elements designed to break containment and extend full-width within otherwise constrained layouts.

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Header | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | full-width container with content contained within page max-width |  |
| Hero | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | full-width section with centered content |  |
| Content Sections (General) | rgb(247, 247, 244) | rgb(38, 37, 30) | none | mixed (images, videos, interactive demos) | full-width or max-width content container with consistent vertical padding |  |
| Changelog / Recent Highlights | rgb(247, 247, 244) | rgb(38, 37, 30) | none | user avatars (small) | max-width content container with consistent vertical padding |  |
| Footer | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | max-width container with a multi-column grid for links |  |
| header | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | full-width container with content contained within page max-width |  |
| hero | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | full-width section with centered content |  |
| content-sections-general | rgb(247, 247, 244) | rgb(38, 37, 30) | none | mixed (images, videos, interactive demos) | full-width or max-width content container with consistent vertical padding |  |
| changelog-recent-highlights | rgb(247, 247, 244) | rgb(38, 37, 30) | none | user avatars (small) | max-width content container with consistent vertical padding |  |
| footer | rgb(247, 247, 244) | rgb(38, 37, 30) | none | n/a | max-width container with a multi-column grid for links |  |

### Implementation Notes

- **layout.content-max-width**: `1300px` — Maximum content width for primary content areas.
- **layout.page-horizontal-padding**: `20px` — Horizontal padding applied to sections, within content max-width.
- **layout.section-vertical-padding-default**: `67.2px` — Default vertical padding for most content sections.
- **layout.section-vertical-padding-hero**: `112px (top) / 67.2px (bottom)` — Specific vertical padding for the hero section.
- **layout.nav-height**: `52px` — Height of the primary navigation bar.
- **layout.component-gap-small**: `8px` — Small spacing token, used for gaps in components like button groups.
- **layout.border-radius-pill**: `3.40282e38px` — Extremely large border-radius value to create pill-shaped elements (e.g., buttons).
- **layout.content-max-width**: `1300px` — max-width
- **layout.page-horizontal-padding**: `20px` — padding
- **layout.section-vertical-padding-default**: `67.2px` — padding

### Build Notes

- The layout heavily utilizes CSS custom properties (e.g., `--color-theme-fg`, `--color-bg-secondary`) for dynamic theming, including dark mode support.
- Many layout-related styles are applied via utility classes, indicating a Tailwind CSS or similar utility-first framework approach.
- Pay attention to explicit `calc(50% - 50vw)` margins for elements that are intended to break out of the main content well and extend to the full viewport width.
- The layout heavily utilizes CSS custom properties (e.g., `--color-theme-fg`, `--color-bg-secondary`) for dynamic theming, including dark mode support.
- Many layout-related styles are applied via utility classes, indicating a Tailwind CSS or similar utility-first framework approach.
- Pay attention to explicit `calc(50% - 50vw)` margins for elements that are intended to break out of the main content well and extend to the full viewport width.

## Elevation & Depth

### Elevation

- **{shadows.shadow.0-0-0-2px-var-color-bg-0-0-0-4px-var-color-accent}** (`0 0 0 2px var(--color-bg), 0 0 0 4px var(--color-accent)`):

- **{shadows.shadow.0-0-0-2px-var-color-warning}** (`0 0 0 2px var(--color-warning)`):

- **{shadows.shadow.0-0-0-3px-var-color-bg-0-0-0-5px-var-color-success}** (`0 0 0 3px var(--color-bg), 0 0 0 5px var(--color-success)`):

- **{shadows.shadow.0-0-8px-var-color-success}** (`0 0 8px var(--color-success)`):

- **{shadows.shadow.invert}** (`invert()`):

- **{shadows.shadow.none}** (`none`):

- **{shadows.shadow.var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow}** (`var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)`):

- **{shadows.shadow.var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow}** (`var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow)`):

### Borders

- **{borders.border.0}** (`0`):

- **{borders.border.0-solid}** (`0 solid`):

- **{borders.border.1px-solid-rgba-237-236-236-0-08}** (`1px solid rgba(237, 236, 236, 0.08)`):

- **{borders.border.1px-solid-var-color-border}** (`1px solid var(--color-border)`):

- **{borders.border.1px-solid-var-color-success}** (`1px solid var(--color-success)`):

- **{borders.border.1px-solid-var-color-theme-border-01}** (`1px solid var(--color-theme-border-01)`):

- **{borders.border.2px-solid-var-color-theme-fg}** (`2px solid var(--color-theme-fg)`):

- **{borders.border.none}** (`none`):

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 |  |
| {rounded.radius.2xs} | 2px |  |
| {rounded.radius.3px} | 3px |  |
| {rounded.radius.xs} | 4px |  |
| {rounded.radius.6px} | 6px |  |
| {rounded.radius.10px} | 10px |  |
| {rounded.radius.3-40282e38px} | 3.40282e38px |  |
| {rounded.radius.50} | 50% |  |

## Components

### Buildable Component Recipes

#### Primary Button
- **Component:** button
- **Background:** rgb(38, 37, 30)
- **Text:** rgb(247, 247, 244)
- **Border:** rgb(38, 37, 30)
- **Radius:** 3.40282e38px

#### Secondary Outline Button
- **Component:** button
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(38, 37, 30)
- **Border:** oklab(0.263084 -0.00230259 0.0124794 / 0.2)
- **Radius:** 3.40282e38px

#### Navigation Link
- **Component:** a
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(38, 37, 30)
- **Border:** rgba(0, 0, 0, 0)
- **Radius:** 0px

#### Toggle Button
- **Component:** button
- **Background:** var(--color-bg-secondary)
- **Text:** var(--color-text-secondary)
- **Border:** 1px solid var(--color-border)
- **Radius:** 6px (specific corners for groups)

#### primary_button
- **Component:** Primary Button
- **Background:** rgb(38, 37, 30)
- **Text:** rgb(247, 247, 244)
- **Border:** 1px
- **Radius:** 3.35544e+07px
- **Padding:** 5.6px 10.5px
- **Typography:** CursorGothic

#### secondary_button
- **Component:** Secondary Button
- **Background:** rgb(242, 241, 237)
- **Text:** rgb(38, 37, 30)
- **Border:** 0px
- **Radius:** 4px
- **Padding:** 12.5625px 14.0625px
- **Typography:** CursorGothic

#### secondary-outline-button
- **Component:** button
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(38, 37, 30)
- **Border:** oklab(0.263084 -0.00230259 0.0124794 / 0.2)
- **Radius:** 3.40282e38px

#### navigation-link
- **Component:** a
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(38, 37, 30)
- **Border:** rgba(0, 0, 0, 0)
- **Radius:** 0px

#### toggle-button
- **Component:** button
- **Background:** var(--color-bg-secondary)
- **Text:** var(--color-text-secondary)
- **Border:** 1px solid var(--color-border)
- **Radius:** 6px

### primary-button

High-contrast call-to-action with dark ink background (rgb(38, 37, 30)) and near-white text (rgb(247, 247, 244)). Fully rounded pill shape (3.40282e38px radius) creates tactile, approachable buttons that stand apart from the surrounding interface. Compact padding (5.6px vertical, 10.5px horizontal) keeps buttons proportional without dominating the layout.

### secondary-outline-button

Transparent background with ink-colored text (rgb(38, 37, 30)) and a subtle 20%-opacity border (oklab color space). Shares the pill-shape radius (3.40282e38px) of primary buttons, maintaining visual consistency while signaling lower hierarchy. Suitable for secondary actions or paired calls-to-action where one choice should remain visually subordinate.

### toggle-button

Context-adaptive button relying on `--color-bg-secondary` and `--color-text-secondary` custom properties. Medium-radius corners (6px) with a 1px border tied to `--color-border`. Designed for grouped toggle controls where corner radii adjust based on position (first, middle, last) within the group.

### navigation-link

Minimal anchor element with zero background, zero border, and sharp 0px radius. Ink-colored text (rgb(38, 37, 30)) maintains legibility while avoiding decorative chrome. Reflects Cursor's preference for understated navigation that doesn't compete with content hierarchy.

### Photography & Media

- **photography:** role=functional_avatar; aspect=1:1; crop=cover; masking=none; frame=none
- **product_ui_screenshot:** role=illustrative; aspect=dynamic; crop=contain; masking=none; frame=none
- **product_screenshot:** role=illustrative_context; aspect=varied; crop=object-fit: cover for contained images; masking=none; frame=implied by container padding
- **avatar:** role=author_identification; aspect=1:1; crop=center crop; masking=circular or square with small radius; frame=none

## Do's and Don'ts

### Do

- Maintain 20px horizontal padding (`--page-horizontal-padding`) within primary content wrappers to prevent edge-collision on smaller viewports—only break this rule for intentional full-bleed sections.
- Use the monospace stack (Berkeley Mono or fallback) exclusively for code blocks, file paths, and terminal output; never substitute it for body copy or UI labels.
- Apply `--color-theme-button-text` and `--color-theme-button-bg` consistently across all button variants to preserve theming integrity in light/dark mode contexts.
- Enforce strict radius discipline: primary CTAs get pill shapes (3.40282e38px), secondary buttons use 4px, toggle groups use 6px, and navigation links stay sharp at 0px—avoid intermediate radii that dilute the system's intentional contrast.
- Write copy that emphasizes measurable productivity gains and specific workflow improvements. Replace vague claims ("faster coding") with concrete observations ("jump to definition in 200ms" or "multi-file edits without context-switching").
- Provide explicit hover and focus states for all interactive elements. Cursor's developer audience expects immediate, legible feedback for keyboard navigation and pointer interactions.
- Apply the default 67.2px vertical padding (`--section-vertical-padding-default`) to all non-hero sections; only the hero section breaks this pattern with its asymmetric 112px/67.2px top/bottom spacing.
- Balance whitespace deliberately: use consistent gaps (8px for small component spacing, 20px for horizontal breathing room, 67.2px for section rhythm) rather than arbitrary pixel-pushing.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | default | header navigation includes 'Product', 'Enterprise', 'Pricing', 'Resources', 'Sign in', 'Contact sales', 'Download'. |
| mobile | (max-width:640px) | header navigation includes a hamburger menu for 'Open navigation' / 'Close navigation'. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- font-weight: No explicit 'light' or 'bold' weights are defined for general use beyond the observed '400', '500', '600', and '700'.
- letter_spacing: No explicit letter-spacing values are defined for the primary type styles.
- extraction_artifact: Missing evidence for `brand_guardian.visual_personality.contrast_posture`.
- extraction_artifact: Missing evidence for `brand_guardian.visual_personality.motion_posture`.
- extraction_artifact: Missing evidence for `brand_guardian.visual_personality.primary_media_posture`.
- extraction_artifact: Missing evidence for `content_voice.body_tone`.
- extraction_artifact: Missing evidence for `content_voice.case_style`.
- extraction_artifact: Missing evidence for `content_voice.cta_tone`.
- extraction_artifact: Missing evidence for `content_voice.microcopy_tone`.
- extraction_artifact: Missing evidence for `page_type_patterns`.
- extraction_artifact: Missing evidence for `surface_modes`.

## Agent Prompt Guide

Quick Color Reference:
- background: `#0009`
- text: `rgb(38, 37, 30)`
- muted text: `#26251ebf`

Quick Typography Reference:
- body: CursorGothic, system-ui, 16px, 400, line-height 1.5
- ui: CursorGothic, system-ui, 15px, 500, line-height 1.0
- headings: CursorGothic, system-ui, 26px, 400, line-height 1.2

Implementation Rules:
- Always apply `--page-horizontal-padding` (20px) to the primary content wrapper within sections to maintain consistent interior spacing, unless explicitly designing a full-bleed section.
- Always use a monospace font (Berkeley Mono) for code blocks and related UI elements to clearly differentiate them from primary text, which uses CursorGothic.
- Apply `--color-theme-button-text` for button text and `--color-theme-button-bg` for button backgrounds to maintain consistent button styling across the application.
- Buttons should utilize either sharp (0px) or fully rounded (e.g., 3.40282e38px for pill-shape) corner radii; avoid intermediate radii for primary call-to-action elements.
- Communicate value through clear, direct language focusing on productivity and efficiency gains. Employ an authoritative yet accessible tone.
- Ensure all interactive elements have clear hover and focus states, reinforcing usability and accessibility.

Example Component Prompts:
1. Create a Header section for Cursor: The best coding agent using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a Primary Button component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.
3. Create a media block that uses photography as functional_avatar; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

- Linear - reference for precise product UI, restrained contrast, and disciplined surfaces.
- Stripe - reference for clear product storytelling and polished implementation detail.
- Vercel - reference for developer-facing hierarchy and monochrome system discipline.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-surface: #0009;
  --color-surface-dark: #14120b;
  --color-ink: rgb(38, 37, 30);
  --color-text-muted: #26251ebf;
  --font-body: "CursorGothic, system-ui";
  --font-body-lg: "CursorGothic, system-ui";
  --font-ui: "CursorGothic, system-ui";
  --font-caption: "CursorGothic, system-ui";
  --font-heading-md: "CursorGothic, system-ui";
  --font-display-md: "CursorGothic, system-ui";
  --font-heading-lg: "CursorGothic, system-ui";
  --radius-2xs: 2px;
  --radius-xs: 4px;
  --radius-0: 0;
  --radius-10px: 10px;
  --radius-3-40282e38px: 3.40282e38px;
  --radius-3px: 3px;
  --radius-50: 50%;
  --radius-6px: 6px;
  --shadow-0-0-0-2px-var-color-bg-0-0-0-4px-var-color-accent: 0 0 0 2px var(--color-bg), 0 0 0 4px var(--color-accent);
  --shadow-0-0-0-2px-var-color-warning: 0 0 0 2px var(--color-warning);
  --shadow-0-0-0-3px-var-color-bg-0-0-0-5px-var-color-success: 0 0 0 3px var(--color-bg), 0 0 0 5px var(--color-success);
  --shadow-0-0-8px-var-color-success: 0 0 8px var(--color-success);
  --shadow-invert: invert();
  --shadow-none: none;
  --shadow-var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  --shadow-var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  --layout-content-max-width: 1300px;
  --layout-page-horizontal-padding: 20px;
  --layout-section-vertical-padding-default: 67.2px;
  --layout-section-vertical-padding-hero: 112px (top) / 67.2px (bottom);
  --layout-nav-height: 52px;
  --layout-component-gap-small: 8px;
  --layout-border-radius-pill: 3.40282e38px;
}
```

### Tailwind v4

```css
@theme {
  --color-surface: #0009;
  --color-surface-dark: #14120b;
  --color-ink: rgb(38, 37, 30);
  --color-text-muted: #26251ebf;
  --font-body: "CursorGothic, system-ui";
  --font-body-lg: "CursorGothic, system-ui";
  --font-ui: "CursorGothic, system-ui";
  --font-caption: "CursorGothic, system-ui";
  --font-heading-md: "CursorGothic, system-ui";
  --font-display-md: "CursorGothic, system-ui";
  --font-heading-lg: "CursorGothic, system-ui";
  --radius-2xs: 2px;
  --radius-xs: 4px;
  --radius-0: 0;
  --radius-10px: 10px;
  --radius-3-40282e38px: 3.40282e38px;
  --radius-3px: 3px;
  --radius-50: 50%;
  --radius-6px: 6px;
  --shadow-0-0-0-2px-var-color-bg-0-0-0-4px-var-color-accent: 0 0 0 2px var(--color-bg), 0 0 0 4px var(--color-accent);
  --shadow-0-0-0-2px-var-color-warning: 0 0 0 2px var(--color-warning);
  --shadow-0-0-0-3px-var-color-bg-0-0-0-5px-var-color-success: 0 0 0 3px var(--color-bg), 0 0 0 5px var(--color-success);
  --shadow-0-0-8px-var-color-success: 0 0 8px var(--color-success);
  --shadow-invert: invert();
  --shadow-none: none;
  --shadow-var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  --shadow-var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  --layout-content-max-width: 1300px;
  --layout-page-horizontal-padding: 20px;
  --layout-section-vertical-padding-default: 67.2px;
  --layout-section-vertical-padding-hero: 112px (top) / 67.2px (bottom);
  --layout-nav-height: 52px;
  --layout-component-gap-small: 8px;
  --layout-border-radius-pill: 3.40282e38px;
}
```
