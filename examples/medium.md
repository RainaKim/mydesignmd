---
version: alpha
name: "Medium: Read and write stories."
description: On Medium, anyone can share insightful perspectives, useful knowledge, and life wisdom with the world.
colors:
  primary: "#000000"
  color.ink: "#6B6B6B"
  color.surface.dark: "#156D12"
  color.surface: rgba(255, 255, 255, 1)
typography:
  font.body:
    fontFamily: sohne, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
  font.caption:
    fontFamily: sohne, sans-serif
    fontSize: 13px
    fontWeight: 400
    lineHeight: 20px
  font.display.xl:
    fontFamily: sohne, sans-serif
    fontSize: 120px
    fontWeight: 300
    lineHeight: 100px
  font.heading.md:
    fontFamily: sohne, sans-serif
    fontSize: 22px
    fontWeight: 700
    lineHeight: 24px
rounded:
  radius.50: 50%
  radius.99em: 99em
sectionMap:
  global:
    background: rgba(255, 255, 255, 1)
    text: rgb(49, 49, 49)
    border: inferred
    media: inferred
    layout: inferred
  links:
    background: inferred
    text: rgb(0, 0, 238)
    border: inferred
    media: inferred
    layout: inferred
buildTokens:
  layout.page-max-width: 960px
  layout.content-margin-horizontal: 32px
  layout.heading-font-size: 40px
  layout.paragraph-font-size: 16px
  layout.link-color: rgb(0, 0, 238)
---

# Medium: Read and write stories. — Style Reference
> readable, clean, thoughtful, functional, typography and surface led

**Theme:** mixed

## Overview

Medium exists to democratize publishing—letting anyone with a story worth telling reach an audience that wants to hear it. The platform honors both the writer's need for a focused, distraction-free canvas and the reader's expectation of clarity, rhythm, and visual restraint.

The central tension: how to accommodate the vast range of voices, expertise levels, and topics submitted by contributors while maintaining editorial coherence and a reading experience that feels curated, not chaotic.

**Voice:** headlines are direct and enabling for platform features ("Write", "Sign in", "Membership"), shifting to thoughtful and contemplative when framing content ("Read and write stories"). Body copy stays informative and unadorned, explaining purpose and value without hype. Microcopy is purely functional—"Sitemap", "Sign in"—while CTAs are terse and action-oriented ("Write", "Membership").

## Colors

### Color Philosophy

Surface colors establish the reading environment first—consider them as atmospheric decisions that set mood and readability context before applying them as decorative fills or component backgrounds. Foreground tokens carry semantic weight: primary text is not interchangeable with secondary text or placeholder text. Each shade of gray, each ink value, plays a distinct functional role in the hierarchy, and collapsing them dilutes clarity.

### Token Roles
#### Surface
- **{colors.color.surface.dark}** (`#156D12`): background.
- **{colors.color.surface}** (`#1A8917`): background.
- **{colors.color.surface}** (`#F7F4ED`): background.
- **{colors.color.surface}** (`rgba(25, 25, 25, 1)`): background.
- **{colors.color.surface}** (`rgba(255, 255, 255, 1)`): background.
#### Text
- **{colors.color.ink}** (`#000000`): foreground.
- **{colors.color.ink}** (`#242424`): foreground.
- **{colors.color.ink}** (`#6B6B6B`): foreground.

## Typography

### Typography Principles

Typography is not a single font choice—it's a system of hierarchical roles. Sohne is deployed across display, heading, body, and caption tiers, but each tier carries its own posture and purpose. Headlines command attention with light weights and generous line heights; utility labels stay compact and unobtrusive; CTAs inherit the brand's directness through medium weights and tight leading. Do not treat this as a global font swap—each type token must preserve its intended role and voice.

### Font Family

- **sohne, sans-serif**.

- **sohne, sans-serif**.

- **sohne, sans-serif**.

- **sohne, sans-serif**.

- **sohne, sans-serif**.

- **sohne, sans-serif**.

- **sohne, sans-serif**.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 16px | 400 | 24px |  |  |
| {typography.font.caption} | 13px | 400 | 20px |  |  |
| {typography.font.display.xl} | 106px | 300 | 95px |  |  |
| {typography.font.display.xl} | 80px | 300 | 72px |  |  |
| {typography.font.display.xl} | 70px | 300 | 74px |  |  |
| {typography.font.display.xl} | 120px | 300 | 100px |  |  |
| {typography.font.heading.md} | 22px | 700 | 24px |  |  |

## Layout

### Composition Principles

Compose pages as discrete named sections—each with explicit surface, text, media, and component treatment—rather than relying on a single generic page container. This approach ensures that a "global" section can maintain `rgba(255, 255, 255, 1)` backgrounds and `rgb(49, 49, 49)` text, while a "links" section applies `rgb(0, 0, 238)` text without inheritance conflicts. Sparse spacing (32px horizontal margins, 75px vertical rhythm) reinforces the editorial priority: breathing room over density.

### Rhythm
- 75px
- 32px
- sparse layout
### Implementation Notes
- center

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| global | rgba(255, 255, 255, 1) | rgb(49, 49, 49) | inferred | inferred | inferred |  |
| links | inferred | rgb(0, 0, 238) | inferred | inferred | inferred |  |
| global | rgba(255, 255, 255, 1) | rgb(49, 49, 49) | inferred | inferred | inferred |  |
| links | inferred | rgb(0, 0, 238) | inferred | inferred | inferred |  |

### Implementation Notes
- **layout.page-max-width**: `960px` — container
- **layout.content-margin-horizontal**: `32px` — spacing
- **layout.heading-font-size**: `40px` — typography
- **layout.paragraph-font-size**: `16px` — typography
- **layout.link-color**: `rgb(0, 0, 238)` — color
- **layout.page-max-width**: `960px` — layout
- **layout.content-margin-horizontal**: `32px` — layout
- **layout.heading-font-size**: `40px` — layout
- **layout.paragraph-font-size**: `16px` — layout
- **layout.link-color**: `rgb(0, 0, 238)` — layout
### Build Notes
- Defined breakpoints: No explicit CSS breakpoints were identified in the provided tokens, implying layout adjustments are handled by general responsive design principles or component-level adaptability.
- Explicit container widths: Layout does not enforce fixed container widths, suggesting fluid or responsive column behavior.
- Shadows: No explicit shadow tokens (e.g., `box-shadow`, `text-shadow`) or usage were observed across the site.
- extraction_artifact: The live page rendered appears to be a security verification gate, which may not fully represent the typical design system or brand experience of Medium's content pages. Typography tokens were present, but actual page content used system fonts.

## Elevation & Depth

- Shadows: No explicit shadow tokens (e.g., `box-shadow`, `text-shadow`) or usage were observed across the site.

### Borders

- **{borders.border.1px}** (`1px`): border

- **{borders.border.1px-solid-242424}** (`1px solid #242424`): border

- **{borders.border.2px}** (`2px`): border

- **{borders.border.inherit}** (`inherit`): border

- **{borders.border.solid-1px-242424}** (`solid 1px #242424`): border

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.99em} | 99em | border |
| {rounded.radius.50} | 50% | border |

## Components

No reusable component patterns were captured.

### Photography & Media
- **logo:** role=brand_identity; aspect=1:1; crop=fit_to_container; masking=none; frame=none

## Do's and Don'ts

### Do
- Preserve type hierarchy as a functional system: Sohne or GT-Super for brand-critical contexts, with system fallbacks only where performance or licensing dictates. Every tier—display, heading, body, caption—must maintain its designated weight, line height, and semantic role.
- Center-align content when the viewport exceeds the 960px max-width container, ensuring symmetry and focus without edge-to-edge sprawl.
- Maintain high contrast between text and background: `#000000` or `#242424` ink on `rgba(255, 255, 255, 1)` surfaces, `rgb(0, 0, 238)` for actionable links.
- Allocate generous whitespace—32px horizontal margins and 75px section rhythm—to give text room to breathe and readers room to think.
- Reflow content into a single-column layout on mobile viewports, prioritizing legibility over grid complexity.
- Set line heights that prevent cramped text runs, especially at display scales (e.g., 95px line height on 106px type).
- Embrace sparse layouts as a brand principle, not a fallback: whitespace is an active ingredient in the reading experience, not wasted space.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | >= 992px |  |
| mobile | < 768px | Content is presented in a single column layout. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- Defined breakpoints: No explicit CSS breakpoints were identified in the provided tokens, implying layout adjustments are handled by general responsive design principles or component-level adaptability.
- Explicit container widths: Layout does not enforce fixed container widths, suggesting fluid or responsive column behavior.
- Shadows: No explicit shadow tokens (e.g., `box-shadow`, `text-shadow`) or usage were observed across the site.
- extraction_artifact: The live page rendered appears to be a security verification gate, which may not fully represent the typical design system or brand experience of Medium's content pages. Typography tokens were present, but actual page content used system fonts.

## Agent Prompt Guide

Quick Color Reference:
- text: `#000000`
- background: `#156D12`

Quick Typography Reference:
- body: sohne, sans-serif, 16px, 400, line-height 24px
- headings: sohne, sans-serif, 106px, 300, line-height 95px

Implementation Rules:
- Preserve type hierarchy as a functional system: Sohne or GT-Super for brand-critical contexts, with system fallbacks only where performance or licensing dictates. Every tier—display, heading, body, caption—must maintain its designated weight, line height, and semantic role.
- Center-align content when the viewport exceeds the 960px max-width container, ensuring symmetry and focus without edge-to-edge sprawl.
- Maintain high contrast between text and background: `#000000` or `#242424` ink on `rgba(255, 255, 255, 1)` surfaces, `rgb(0, 0, 238)` for actionable links.
- Allocate generous whitespace—32px horizontal margins and 75px section rhythm—to give text room to breathe and readers room to think.
- Reflow content into a single-column layout on mobile viewports, prioritizing legibility over grid complexity.

Example Component Prompts:
1. Create a global section for Medium: Read and write stories. using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a media block that uses logo as brand_identity; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing and the disciplined use of negative space as a narrative device, not a source to copy.
- Le Labo - reference for monochrome product restraint, terse commerce language, and the refusal to over-explain or over-decorate.
- COS - reference for quiet, image-led minimalism where neutral surfaces and disciplined typography carry the entire aesthetic load.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-ink: #000000;
  --color-surface-dark: #156D12;
  --color-surface: #1A8917;
  --font-body: "sohne, sans-serif";
  --font-caption: "sohne, sans-serif";
  --font-display-xl: "sohne, sans-serif";
  --font-heading-md: "sohne, sans-serif";
  --radius-50: 50%;
  --radius-99em: 99em;
  --layout-page-max-width: 960px;
  --layout-content-margin-horizontal: 32px;
  --layout-heading-font-size: 40px;
  --layout-paragraph-font-size: 16px;
  --layout-link-color: rgb(0, 0, 238);
}
```

### Tailwind v4

```css
@theme {
  --color-ink: #000000;
  --color-surface-dark: #156D12;
  --color-surface: #1A8917;
  --font-body: "sohne, sans-serif";
  --font-caption: "sohne, sans-serif";
  --font-display-xl: "sohne, sans-serif";
  --font-heading-md: "sohne, sans-serif";
  --radius-50: 50%;
  --radius-99em: 99em;
  --layout-page-max-width: 960px;
  --layout-content-margin-horizontal: 32px;
  --layout-heading-font-size: 40px;
  --layout-paragraph-font-size: 16px;
  --layout-link-color: rgb(0, 0, 238);
}
```
