---
version: alpha
name: Free AI Voice Generator & Voice Agents Platform \\| ElevenLabs
description: Create lifelike speech with our AI voice generator and voice agents platform. Access 5,000+ voices in 70+ languages with secure APIs and SDKs.
colors:
  primary: "#2B7FFF"
  color.accent: "#2B7FFF"
  color.border: rgba(255,255,255,.2)
  color.ink: "#000"
  color.canvas: "#fff"
  color.overlay-dark: rgba(0,0,0,0.4)
  color.shadow-subtle: rgba(0,0,0,0.04)
typography:
  font.body:
    fontFamily: Inter, Inter Fallback, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5rem
  font.caption:
    fontFamily: Inter, Inter Fallback, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.25rem
  font.display.lg:
    fontFamily: Waldenburg, sans-serif
    fontSize: 48px
    fontWeight: 300
    lineHeight: 1.15
  font.heading.sm:
    fontFamily: Inter, Inter Fallback, sans-serif
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.75rem
  font.heading.lg:
    fontFamily: Waldenburg, sans-serif
    fontSize: 36px
    fontWeight: 300
    lineHeight: 1.15
rounded:
  radius.125rem: .125rem
  radius.25rem: .25rem
  radius.375rem: .375rem
  radius.5rem: .5rem
  radius.75rem: .75rem
  radius.0: 0
  radius.1rem: 1rem
  radius.pill: 9999px
components:
  nav-link-button-desktop:
    backgroundColor: transparent
    textColor: rgb(0, 0, 0)
    rounded: 18px
  play-button-hero:
    backgroundColor: transparent
    textColor: rgb(0, 0, 0)
    rounded: 9999px
  tab-component-selected-state:
    backgroundColor: transparent
    textColor: rgb(0, 0, 0)
    rounded: 9999px
  feature-grid-item-card:
    backgroundColor: rgb(245, 243, 241)
    textColor: rgb(0, 0, 0)
    rounded: 20px
  primary-button:
    backgroundColor: rgb(0, 0, 0)
    textColor: rgb(255, 255, 255)
    rounded: 9999px
    padding: 0px 12px
    typography: Inter
  secondary-button:
    backgroundColor: rgb(255, 255, 255)
    textColor: rgb(0, 0, 0)
    rounded: 9999px
    padding: 0px 12px
    typography: Inter
sectionMap:
  navigation-bar:
    background: rgba(0,0,0,0)
    text: "#000"
    border: none
    media: none
    layout: horizontal flex (desktop)
  hero-section:
    background: rgb(253, 252, 252)
    text: "#000, rgb(119, 113, 105)"
    border: none
    media: interactive circular play buttons, background illustrations (inferred)
    layout: centered text block with layered media elements
  general-content-sections:
    background: rgb(253, 252, 252)
    text: "#000, rgb(119, 113, 105), rgb(165, 159, 151)"
    border: none
    media: various (photography, product UI)
    layout: fluid content blocks, some with internal grid layouts
  feature-grid-items:
    background: rgb(245, 243, 241)
    text: "#000"
    border: none
    media: often includes imagery/icons
    layout: card-like structure within a grid
  footer:
    background: "#000"
    text: "#fff"
    border: none
    media: none
    layout: multi-column grid (desktop), stacked columns (mobile, inferred)
buildTokens:
  layout.max-content-width-desktop: 1178px
  layout.max-content-width-mobile: 350px
  layout.outer-gutter-mobile: 1.25rem (20px)
  layout.outer-gutter-desktop: 2.5rem (40px)
  layout.section-vertical-spacing: 2.5rem (my-40) to 3rem (my-48)
  layout.component-gap-inner-grid-gap: 1.75rem (gap-28)
---

# Free AI Voice Generator & Voice Agents Platform \\| ElevenLabs — Style Reference
> technological, precise, modern, product ui led, artificial intelligence, speech synthesis, conversational ai, content creation tools.

**Theme:** light

## Overview

Enabling lifelike, natural AI speech and agents to empower creators and enterprises.

Balancing cutting-edge AI complexity with intuitive, human-like output and interaction.

**Voice:** headlines=informative_benefit_driven; body=professional_explanatory; microcopy=functional_direct; ctas=clear_action_oriented

## Colors

### Color Philosophy
- Treat surface colors as the page atmosphere before using them as decorative fills.
- Keep foreground tokens role-specific: primary text, secondary text, placeholder text, and inverse text should not collapse into one gray scale.
- The strongest contrast relationship is monochrome; add color only when evidence proves it is part of the brand system.
### Token Roles
#### Brand & Accent
- **{colors.color.accent}** (`#2B7FFF`): accent. use for interactive_elements; links; call_to_action_buttons; avoid large_decorative_areas; non_interactive_text.
#### Hairlines & Borders
- **{colors.color.border}** (`rgba(0,0,0,.1)`): border. use for card_borders; input_borders; dividers; subtle_outlines.
- **{colors.color.border}** (`rgba(255,255,255,.2)`): border. use for card_borders_on_dark; input_borders_on_dark; dividers_on_dark.
#### Text
- **{colors.color.ink}** (`rgb(165, 159, 151)`): foreground. use for button_text; avoid primary_heading; body_text.
- **{colors.color.ink}** (`#000`): foreground. use for heading; body_text; icons; stroke.
#### Semantic
- **{colors.color.overlay-dark}** (`rgba(0,0,0,0.4)`): overlay. use for overlays; backdrop_effects; strong_shadows.
- **{colors.color.shadow-subtle}** (`rgba(0,0,0,0.04)`): shadow. use for card_elevation; component_shadows.
#### Surface
- **{colors.color.canvas}** (`#fff`): surface. use for page_background; card_background; ring_offset.

## Typography

### Typography Principles

- Treat typography as a hierarchy of roles, not a global font swap: Inter, Inter Fallback, sans-serif; Waldenburg, sans-serif.

- Match type hierarchy to the content voice: headline posture, utility labels, and CTA tone should remain distinct.

### Font Family

- **Inter, Inter Fallback, sans-serif**; fallbacks: Inter Fallback; sans-serif.

- **Inter, Inter Fallback, sans-serif**; fallbacks: Inter Fallback; sans-serif.

- **Waldenburg, sans-serif**; fallbacks: Waldenburg Fallback; sans-serif.

- **Inter, Inter Fallback, sans-serif**; fallbacks: Inter Fallback; sans-serif.

- **Waldenburg, sans-serif**; fallbacks: Waldenburg Fallback; sans-serif.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 16px | 400 | 1.5rem |  |  |
| {typography.font.caption} | 14px | 400 | 1.25rem |  |  |
| {typography.font.display.lg} | 48px | 300 | 1.15 |  |  |
| {typography.font.heading.sm} | 18px | 600 | 1.75rem |  |  |
| {typography.font.heading.lg} | 36px | 300 | 1.15 |  |  |

## Layout

### Composition Principles
- Overall page rhythm is established through consistent application of a vertical spacing scale, primarily driven by `--spacing-outer-gutter` and `--spacing-inner-gutter` variables, which adjust based on viewport size.
- Vertical spacing between sections is managed by a set of defined spacing tokens, including 1.5rem, 2rem, 2.5rem, and 3rem, used as margins.
- Content is generally left-aligned within its primary container, with hero sections and main navigation sometimes utilizing center alignment on desktop.
- sparse layout
- Compose pages as named sections with explicit surface, text, media, and component treatment instead of one generic page container.
### Rhythm
- Vertical spacing between sections is managed by a set of defined spacing tokens, including 1.5rem, 2rem, 2.5rem, and 3rem, used as margins.
- Overall page rhythm is established through consistent application of a vertical spacing scale, primarily driven by `--spacing-outer-gutter` and `--spacing-inner-gutter` variables, which adjust based on viewport size.
- sparse layout
### Implementation Notes
- Container widths: 1176px (desktop); 350px (mobile)
- Flexible grid patterns are utilized within specific content sections (e.g., feature grids), but no single overarching grid system is applied globally for the page layout.
- Content is generally left-aligned within its primary container, with hero sections and main navigation sometimes utilizing center alignment on desktop.

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Navigation Bar | rgba(0,0,0,0) | #000 | none | none | horizontal flex (desktop) |  |
| Hero Section | rgb(253, 252, 252) | #000, rgb(119, 113, 105) | none | interactive circular play buttons, background illustrations (inferred) | centered text block with layered media elements |  |
| General Content Sections | rgb(253, 252, 252) | #000, rgb(119, 113, 105), rgb(165, 159, 151) | none | various (photography, product UI) | fluid content blocks, some with internal grid layouts |  |
| Feature Grid Items | rgb(245, 243, 241) | #000 | none | often includes imagery/icons | card-like structure within a grid |  |
| Footer | #000 | #fff | none | none | multi-column grid (desktop), stacked columns (mobile, inferred) |  |
| Navigation Bar | rgba(0,0,0,0) | #000 | none | none | horizontal flex (desktop) |  |
| Hero Section | rgb(253, 252, 252) | #000, rgb(119, 113, 105) | none | interactive circular play buttons, background illustrations (inferred) | centered text block with layered media elements |  |
| General Content Sections | rgb(253, 252, 252) | #000, rgb(119, 113, 105), rgb(165, 159, 151) | none | various (photography, product UI) | fluid content blocks, some with internal grid layouts |  |
| Feature Grid Items | rgb(245, 243, 241) | #000 | none | often includes imagery/icons | card-like structure within a grid |  |
| Footer | #000 | #fff | none | none | multi-column grid (desktop), stacked columns (mobile, inferred) |  |

### Implementation Notes
- **layout.max-content-width-desktop**: `1178px` — main_content_boundary
- **layout.max-content-width-mobile**: `350px` — main_content_boundary
- **layout.outer-gutter-mobile**: `1.25rem (20px)` — page_padding
- **layout.outer-gutter-desktop**: `2.5rem (40px)` — page_padding
- **layout.section-vertical-spacing**: `2.5rem (my-40) to 3rem (my-48)` — vertical_rhythm_element
- **layout.component-gap-inner-grid-gap**: `1.75rem (gap-28)` — spacing_between_elements
- **layout.max-content-width-desktop**: `1178px` — main_content_boundary
- **layout.max-content-width-mobile**: `350px` — main_content_boundary
- **layout.outer-gutter-mobile**: `1.25rem (20px)` — page_padding
- **layout.outer-gutter-desktop**: `2.5rem (40px)` — page_padding
### Build Notes
- Utilize CSS variables for outer and inner gutters, as identified in the token evidence, to ensure responsive scaling.
- Implement a centered max-width container for main content areas to maintain visual balance across desktop viewports.
- Ensure mobile navigation is fully accessible via a hamburger menu or similar pattern, hiding desktop-specific navigation links.
- Utilize CSS variables for outer and inner gutters, as identified in the token evidence, to ensure responsive scaling.
- Implement a centered max-width container for main content areas to maintain visual balance across desktop viewports.
- Ensure mobile navigation is fully accessible via a hamburger menu or similar pattern, hiding desktop-specific navigation links.

## Elevation & Depth

No shadow or elevation system is evidenced.

### Borders

- **{borders.border.06rem}** (`.06rem`): border-extra-thin

- **{borders.border.5px}** (`.5px`): border-very-thin

- **{borders.border.0}** (`0`): border-none

- **{borders.border.1-5px}** (`1.5px`): border-medium

- **{borders.border.1px}** (`1px`): border-thin

- **{borders.border.2px}** (`2px`): border-thick

- **{borders.border.2px-solid-transparent}** (`2px solid transparent`): outline-transparent

- **{borders.border.4px}** (`4px`): border-extra-thick

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 | corner-sharp |
| {rounded.radius.1rem} | 1rem | corner-large |
| {rounded.radius.pill} | 9999px | corner-pill |
| {rounded.radius.125rem} | .125rem | corner-extra-small |
| {rounded.radius.25rem} | .25rem | corner-small |
| {rounded.radius.375rem} | .375rem | corner-medium-small |
| {rounded.radius.5rem} | .5rem | corner-medium |
| {rounded.radius.75rem} | .75rem | corner-large-medium |

## Components

### Buildable Component Recipes
#### Nav Link/Button (Desktop)
- **Component:** a
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 18px

#### Play Button (Hero)
- **Component:** button
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 9999px

#### Tab Component (Selected State)
- **Component:** div (role='tab')
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 9999px

#### Feature Grid Item Card
- **Component:** div
- **Background:** rgb(245, 243, 241)
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 20px

#### primary_button
- **Component:** Primary Button
- **Background:** rgb(0, 0, 0)
- **Text:** rgb(255, 255, 255)
- **Border:** 0px
- **Radius:** 9999px
- **Padding:** 0px 12px
- **Typography:** Inter

#### secondary_button
- **Component:** Secondary Button
- **Background:** rgb(255, 255, 255)
- **Text:** rgb(0, 0, 0)
- **Border:** 0px
- **Radius:** 9999px
- **Padding:** 0px 12px
- **Typography:** Inter

#### Nav Link/Button (Desktop)
- **Component:** a
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 18px

#### Play Button (Hero)
- **Component:** button
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 9999px

#### Tab Component (Selected State)
- **Component:** div (role='tab')
- **Background:** transparent
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 9999px

#### Feature Grid Item Card
- **Component:** div
- **Background:** rgb(245, 243, 241)
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 20px

### Button (Primary/Dark)
Primary action button with dark background and light text, styled as a pill-shaped link.

### Button (Secondary/Light)
Secondary action button with light background and dark text, styled as a pill-shaped link.

### Feature Grid Item Card
A card-like structure designed for displaying features within a grid layout, often including imagery or icons. All items in these grids are marked as 'featured' by default, suggesting a uniform visual treatment rather than differentiation.

### Photography & Media
- **iconography:** role=interactive_control; aspect=square; crop=none; masking=circle; frame=none
- **product_ui_screenshot:** role=demonstrative; aspect=freeform; crop=show_feature_context; masking=none; frame=soft_rounded_corners
- **product_ui_screenshot:** role=illustrative_feature_showcase; aspect=varied, often wide (e.g., ~1.73:1); crop=fill (object-fit); masking=none (rectangular); frame=none
- **decorative_circle_element:** role=interactive_demonstration; aspect=1:1; crop=contain; masking=circular (border-radius: 9999px); frame=none

## Do's and Don'ts

### Do
- Apply 'Inter' font for all body copy, UI text, and secondary headings to ensure optimal legibility and a consistent user interface experience.
- Apply a sparse density layout, using generous vertical spacing between sections (e.g., 2.5rem to 3rem) to enhance readability and visual breathing room.
- Apply consistent large rounded corners (e.g., 9999px, 18px, 20px) for interactive components like buttons and content containers, contributing to a user-friendly and approachable feel.
- Apply rounded corners (e.g., 9999px for full circles, 18px-20px for buttons/sections) consistently for interactive elements and content cards.
- Consistently employ fully transparent `rgb(0 0 0/0)` or `rgb(255 255 255/0)` as terminal stops in gradients to achieve smooth, natural fades and prevent abrupt color transitions.
- Employ a `1.5px` border width for focus indicators to provide clear visual feedback without being overly obtrusive, and reserve transparent borders (`2px solid transparent`) for elements where focus state should occupy space without causing layout shifts.
- Ensure all interactive elements, particularly on mobile, meet or exceed a 36x36px touch target area for usability, even if the visual element size is smaller.
- Ensure navigation adapts from a condensed mobile menu (hamburger icon) to a full horizontal menu at the `37.5rem` breakpoint, transitioning gracefully for tablet and desktop viewports.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | 80rem+ | Inner gutters increase to 1.25rem to accommodate wider screens.; Full desktop navigation is displayed.; Content flows into wider multi-column layouts. |
| mobile | 0rem - 37.49rem | Navigation is condensed into a hamburger menu.; Outer gutters are reduced to 1.25rem.; Content blocks stack vertically to optimize for narrow screens. |
| tablet | 37.5rem - 79.99rem | Outer gutters expand to 2.5rem.; Inner gutters are introduced at 1rem.; Content may begin to transition to multi-column layouts where applicable. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- Explicit spacing tokens for all possible granular spacing needs: While key layout spacing variables are defined, the token list does not cover every possible granular spacing value, implying some direct pixel/rem values or derived values are used in components.
- monospace_font_usage: The 'Geist Mono' font is defined but not observed in use within the main visible content of the page, suggesting it may be reserved for code snippets or specific technical contexts.
- Universally applied CSS Grid system for overall page layout: While grid-like patterns exist within specific content sections, there is no single, explicit CSS Grid system defining the macro layout of the entire page.
- generic_language: The agent instructions required outputting decorative gradient tokens under `tokens.custom_tokens`, but the provided `OUTPUT SHAPE (strict)` schema does not include a `custom_tokens` field within `tokens`. The decorative gradient token `soft_white_orb` has been omitted to comply with the strict schema requirements.
- generic_language: The agent's output scope explicitly includes 'tokens.shadows' and 'tokens.motion', but the provided DesignDocFragment schema does not contain these fields. Therefore, shadow and motion tokens, despite being present in the captured evidence, cannot be included in the 'tokens' object of the output JSON. Related analysis is provided in claims.

## Agent Prompt Guide

Quick Color Reference:
- accent: `#2B7FFF`
- border: `rgba(0,0,0,.1)`
- text: `rgb(165, 159, 151)`
- background: `#fff`

Quick Typography Reference:
- body: Inter, Inter Fallback, sans-serif, 16px, 400, line-height 1.5rem
- headings: Waldenburg, sans-serif, 48px, 300, line-height 1.15

Implementation Rules:
- Apply 'Inter' font for all body copy, UI text, and secondary headings to ensure optimal legibility and a consistent user interface experience.
- Apply a sparse density layout, using generous vertical spacing between sections (e.g., 2.5rem to 3rem) to enhance readability and visual breathing room.
- Apply consistent large rounded corners (e.g., 9999px, 18px, 20px) for interactive components like buttons and content containers, contributing to a user-friendly and approachable feel.
- Apply rounded corners (e.g., 9999px for full circles, 18px-20px for buttons/sections) consistently for interactive elements and content cards.
- Consistently employ fully transparent `rgb(0 0 0/0)` or `rgb(255 255 255/0)` as terminal stops in gradients to achieve smooth, natural fades and prevent abrupt color transitions.
- Employ a `1.5px` border width for focus indicators to provide clear visual feedback without being overly obtrusive, and reserve transparent borders (`2px solid transparent`) for elements where focus state should occupy space without causing layout shifts.

Example Component Prompts:
1. Create a Navigation Bar section for Free AI Voice Generator & Voice Agents Platform \\| ElevenLabs using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a Nav Link/Button (Desktop) component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.
3. Create a media block that uses iconography as interactive_control; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing, not a source to copy.
- Le Labo - reference for monochrome product restraint and terse commerce language.
- COS - reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-accent: #2B7FFF;
  --color-border: rgba(0,0,0,.1);
  --color-ink: rgb(165, 159, 151);
  --color-canvas: #fff;
  --color-overlay-dark: rgba(0,0,0,0.4);
  --color-shadow-subtle: rgba(0,0,0,0.04);
  --font-body: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-caption: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-display-lg: "Waldenburg, sans-serif", "Waldenburg Fallback", sans-serif;
  --font-heading-sm: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-heading-lg: "Waldenburg, sans-serif", "Waldenburg Fallback", sans-serif;
  --radius-125rem: .125rem;
  --radius-25rem: .25rem;
  --radius-375rem: .375rem;
  --radius-5rem: .5rem;
  --radius-75rem: .75rem;
  --radius-0: 0;
  --radius-1rem: 1rem;
  --radius-pill: 9999px;
  --layout-max-content-width-desktop: 1178px;
  --layout-max-content-width-mobile: 350px;
  --layout-outer-gutter-mobile: 1.25rem (20px);
  --layout-outer-gutter-desktop: 2.5rem (40px);
  --layout-section-vertical-spacing: 2.5rem (my-40) to 3rem (my-48);
  --layout-component-gap-inner-grid-gap: 1.75rem (gap-28);
}
```

### Tailwind v4

```css
@theme {
  --color-accent: #2B7FFF;
  --color-border: rgba(0,0,0,.1);
  --color-ink: rgb(165, 159, 151);
  --color-canvas: #fff;
  --color-overlay-dark: rgba(0,0,0,0.4);
  --color-shadow-subtle: rgba(0,0,0,0.04);
  --font-body: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-caption: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-display-lg: "Waldenburg, sans-serif", "Waldenburg Fallback", sans-serif;
  --font-heading-sm: "Inter, Inter Fallback, sans-serif", "Inter Fallback", sans-serif;
  --font-heading-lg: "Waldenburg, sans-serif", "Waldenburg Fallback", sans-serif;
  --radius-125rem: .125rem;
  --radius-25rem: .25rem;
  --radius-375rem: .375rem;
  --radius-5rem: .5rem;
  --radius-75rem: .75rem;
  --radius-0: 0;
  --radius-1rem: 1rem;
  --radius-pill: 9999px;
  --layout-max-content-width-desktop: 1178px;
  --layout-max-content-width-mobile: 350px;
  --layout-outer-gutter-mobile: 1.25rem (20px);
  --layout-outer-gutter-desktop: 2.5rem (40px);
  --layout-section-vertical-spacing: 2.5rem (my-40) to 3rem (my-48);
  --layout-component-gap-inner-grid-gap: 1.75rem (gap-28);
}
```

