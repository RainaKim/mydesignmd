---
version: alpha
name: Hume AI - The Empathic AI Research Lab \\| Hume AIhume.ai logohume.ai logo
description: Providing the open source models, datasets, and evaluation APIs to embed emotional intelligence into your voice models.
colors:
  primary: "#c094e4"
  color.accent: "#c094e4"
  color.base-light: rgb(255, 255, 255)
  color.dark-base: "#222"
  color.ink: "#fff6"
  color.surface: "#ffffff80"
  color.utility-transparent: "#0000"
typography:
  font.body:
    fontFamily: Fellix
    fontSize: 16px
    fontWeight: 310
    lineHeight: 1.5
  font.caption:
    fontFamily: Fellix
    fontSize: 14px
    fontWeight: 310
    lineHeight: 1.5
  font.body.lg:
    fontFamily: Fellix
    fontSize: 30px
    fontWeight: 510
    lineHeight: 1.2
  font.display.lg:
    fontFamily: Fellix
    fontSize: 48px
    fontWeight: 520
    lineHeight: 1.1
  font.heading.sm:
    fontFamily: Fellix
    fontSize: 18px
    fontWeight: 520
    lineHeight: 1.5
  font.ui:
    fontFamily: PP Fraktion Mono
    fontSize: 12px
    fontWeight: 310
    lineHeight: 1.5
rounded:
  radius.25rem: .25rem
  radius.375rem: .375rem
  radius.5rem: .5rem
  radius.0: 0
  radius.1-5rem: 1.5rem
  radius.1rem: 1rem
  radius.2-5rem: 2.5rem
  radius.3-40282e38px: 3.40282e38px
components:
  primary-action-button:
    backgroundColor: rgb(34, 34, 34)
    textColor: rgb(255, 249, 243)
    rounded: 3.35544e+07px (fully rounded)
  secondary-outline-button:
    backgroundColor: rgba(0, 0, 0, 0)
    textColor: oklab(0.251963 0.0000115335 0.00000502169 / 0.8)
    rounded: 8px
  information-card:
    backgroundColor: rgb(255, 255, 255)
    textColor: rgb(34, 34, 34)
    rounded: 12px
sectionMap:
  navigation:
    background: rgba(0, 0, 0, 0) (transparent over content)
    text: rgb(34, 34, 34)
    border: none
    media: none
    layout: fixed top
  hero:
    background: rgb(255, 255, 255) (inferred from visual content)
    text: rgb(34, 34, 34)
    border: none
    media: implied large visual/video
    layout: full width, centered content
  content-section-e-g-human-feedback-api-data-models:
    background: rgb(255, 255, 255) (inferred from visual content)
    text: rgb(34, 34, 34)
    border: none
    media: mixed images/videos
    layout: full width, constrained content
  call-to-action-get-started:
    background: rgb(34, 34, 34) (inferred from visual content)
    text: rgb(255, 249, 243)
    border: none
    media: none
    layout: full width, centered content
  footer:
    background: rgb(34, 34, 34)
    text: rgb(255, 249, 243)
    border: none
    media: none
    layout: full width, multi-column links
buildTokens:
  layout.navigation-height: 64px
  layout.desktop-section-padding-top: 70px
  layout.grid-gap-mobile: 30px
  layout.grid-gap-desktop: 34px
  layout.max-content-width-desktop: 1280px
---

# Hume AI - The Empathic AI Research Lab \\| Hume AIhume.ai logohume.ai logo — Style Reference
> modern, technical, clean, minimal, thoughtful

**Theme:** mixed

## Overview

The Emotional Intelligence Lab for Voice AI, building technology that understands humanity.

Balancing cutting-edge AI technology with the nuanced, human-centric aspect of emotional intelligence.

## Colors

### Color Philosophy
- Treat surface colors as the page atmosphere before using them as decorative fills.
- Keep foreground tokens role-specific: primary text, secondary text, placeholder text, and inverse text should not collapse into one gray scale.
### Token Roles
#### Brand & Accent
- **{colors.color.accent}** (`#c094e4`): accent. use for interactive_elements; highlights; background_elements; status_indicators.
#### Semantic
- **{colors.color.dark-base}** (`#222`): base_dark. use for body_text; headings; borders; background_elements.
- **{colors.color.base-light}** (`rgb(255, 255, 255)`): base_light. use for buttons.
- **{colors.color.utility-transparent}** (`#0000`): utility. use for gradients; shadows.
#### Text
- **{colors.color.ink}** (`oklab(0.251963 0.0000115335 0.00000502169 / 0.6)`): foreground. use for paragraphs.
- **{colors.color.ink}** (`#fff6`): foreground. use for paragraphs; icons; input_placeholders.
#### Surface
- **{colors.color.surface}** (`#fff3`): surface. use for dividers; low_emphasis_backgrounds; secondary_text; interactive_elements.
- **{colors.color.surface}** (`#ffffff80`): surface. use for cards; interactive_elements; icons; focus_rings.

## Typography

### Typography Principles

- Treat typography as a hierarchy of roles, not a global font swap: Fellix; PP Fraktion Mono.

### Font Family

- **Fellix**; fallbacks: sans-serif.

- **Fellix**; fallbacks: sans-serif.

- **Fellix**; fallbacks: sans-serif.

- **Fellix**; fallbacks: sans-serif.

- **Fellix**; fallbacks: sans-serif.

- **Fellix**; fallbacks: sans-serif.

- **PP Fraktion Mono**; fallbacks: monospace.

- **PP Fraktion Mono**; fallbacks: monospace.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 16px | 310 | 1.5 |  |  |
| {typography.font.caption} | 14px | 310 | 1.5 |  |  |
| {typography.font.body.lg} | 30px | 510 | 1.2 |  |  |
| {typography.font.display.lg} | 48px | 520 | 1.1 |  |  |
| {typography.font.heading.sm} | 20px | 520 | 1.2 |  |  |
| {typography.font.heading.sm} | 18px | 520 | 1.5 |  |  |
| {typography.font.ui} | 14px | 310 | 1.5 |  |  |
| {typography.font.ui} | 12px | 310 | 1.5 |  |  |

### Principles

- **body-default**: use `Fellix`; size `16px`; weight `310`.

- **caption-default**: use `Fellix`; size `14px`; weight `310`.

- **data-numeric-lg**: use `Fellix`; size `30px`; weight `510`.

- **display-hero**: use `Fellix`; size `48px`; weight `520`.

- **heading-md**: use `Fellix`; size `20px`; weight `520`.

- **heading-sm**: use `Fellix`; size `18px`; weight `520`.

- **label-mono-md**: use `PP Fraktion Mono`; size `14px`; weight `310`.

- **label-mono-sm**: use `PP Fraktion Mono`; size `12px`; weight `310`.

## Layout

### Composition Principles
- The page maintains a clear vertical rhythm, transitioning through distinct content sections (hero, API features, data, models, calls to action) that are primarily full-width containers with centrally aligned, narrower content blocks.
- Sections are vertically stacked with varying amounts of padding and margins, contributing to a deliberate vertical rhythm. For example, a padding-top of 70px is applied to sections on medium-width screens and above.
- Key content blocks, such as the main heading and introductory paragraph, are horizontally centered within their respective containers. Other content elements within sections also frequently employ central alignment. Text alignment for paragraphs varies, with the primary hero paragraph being centered, and others left-aligned.
- The desktop layout exhibits a balanced density posture, while the mobile layout is media-led, suggesting a greater emphasis on visual elements and adapting to smaller screen space.
- Compose pages as named sections with explicit surface, text, media, and component treatment instead of one generic page container.
### Rhythm
- Sections are vertically stacked with varying amounts of padding and margins, contributing to a deliberate vertical rhythm. For example, a padding-top of 70px is applied to sections on medium-width screens and above.
- The page maintains a clear vertical rhythm, transitioning through distinct content sections (hero, API features, data, models, calls to action) that are primarily full-width containers with centrally aligned, narrower content blocks.
- The desktop layout exhibits a balanced density posture, while the mobile layout is media-led, suggesting a greater emphasis on visual elements and adapting to smaller screen space.
### Implementation Notes
- Container widths: 960px (observed for primary headings on desktop); 672px (observed for primary paragraphs on desktop); 80rem (implied by max-w-7xl CSS class); 64rem (implied by max-w-5xl CSS class)
- The layout utilizes a robust CSS Grid system, supporting various column configurations including 1, 2, 3, and 4 columns, as well as custom track definitions like '1fr auto 1fr' and 'min-content 1fr'. This system is used for content organization and responsive adaptations.
- Key content blocks, such as the main heading and introductory paragraph, are horizontally centered within their respective containers. Other content elements within sections also frequently employ central alignment. Text alignment for paragraphs varies, with the primary hero paragraph being centered, and others left-aligned.

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Navigation | rgba(0, 0, 0, 0) (transparent over content) | rgb(34, 34, 34) | none | none | fixed top |  |
| Hero | rgb(255, 255, 255) (inferred from visual content) | rgb(34, 34, 34) | none | implied large visual/video | full width, centered content |  |
| Content Section (e.g., Human Feedback API, Data, Models) | rgb(255, 255, 255) (inferred from visual content) | rgb(34, 34, 34) | none | mixed images/videos | full width, constrained content |  |
| Call to Action / Get Started | rgb(34, 34, 34) (inferred from visual content) | rgb(255, 249, 243) | none | none | full width, centered content |  |
| Footer | rgb(34, 34, 34) | rgb(255, 249, 243) | none | none | full width, multi-column links |  |

### Implementation Notes
- **layout.navigation-height**: `64px` — structural
- **layout.desktop-section-padding-top**: `70px` — spacing
- **layout.grid-gap-mobile**: `30px` — spacing
- **layout.grid-gap-desktop**: `34px` — spacing
- **layout.max-content-width-desktop**: `1280px` — structural
### Build Notes
- Implement a responsive grid system that adapts column counts based on viewport size using CSS grid properties.
- Ensure consistent vertical rhythm for sections, with larger padding on desktop and reduced padding on mobile.
- Buttons should follow established styles for primary (dark, rounded) and secondary (outlined, rounded-8px) variants, with appropriate hover/focus states.

## Elevation & Depth

- specific_box_shadow_values: While box-shadow properties are referenced via CSS variables (e.g., '--tw-shadow'), the actual numeric and color values for these shadows are not provided in the captured evidence. This prevents precise definition of the depth model.

### Borders

- **{borders.border.0}** (`0`): no_border

- **{borders.border.0-solid}** (`0 solid`): default_no_border

- **{borders.border.1px}** (`1px`): thin_border

- **{borders.border.2px}** (`2px`): medium_border

- **{borders.border.auto}** (`auto`): system_focus_outline

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 | sharp_corners |
| {rounded.radius.1rem} | 1rem | large_radius |
| {rounded.radius.1-5rem} | 1.5rem | extra_large_radius |
| {rounded.radius.2-5rem} | 2.5rem | specific_large_radius |
| {rounded.radius.25rem} | .25rem | small_radius |
| {rounded.radius.375rem} | .375rem | medium_radius |
| {rounded.radius.5rem} | .5rem | standard_radius |
| {rounded.radius.3-40282e38px} | 3.40282e38px | full_circle |

## Components

### Buildable Component Recipes
#### Primary Action Button
- **Component:** button
- **Background:** rgb(34, 34, 34)
- **Text:** rgb(255, 249, 243)
- **Border:** none
- **Radius:** 3.35544e+07px (fully rounded)

#### Secondary Outline Button
- **Component:** button
- **Background:** rgba(0, 0, 0, 0)
- **Text:** oklab(0.251963 0.0000115335 0.00000502169 / 0.8)
- **Border:** 1px solid oklab(0.251963 0.0000115335 0.00000502169 / 0.1)
- **Radius:** 8px

#### Information Card
- **Component:** div
- **Background:** rgb(255, 255, 255)
- **Text:** rgb(34, 34, 34)
- **Border:** none
- **Radius:** 12px

### Button
Interactive elements used to trigger actions, navigate, or control content. They appear in various styles including solid, ghost, and outline, with different levels of rounded corners and text treatments. Some buttons also function as tabs for content selection.

### Card
Container components used to group related content, such as titles, descriptions, and calls to action. They typically feature a background color, rounded corners, and consistent padding.

### Grid Layout
A layout system utilizing CSS Grid to arrange content in responsive columns, supporting various column counts and custom track sizing.

### Photography & Media
- **abstract_digital_art:** role=conceptual_illustration; aspect=varied; crop=fill; masking=none; frame=none
- **photography:** role=Supportive visuals for product/feature descriptions; aspect=varied, often filling grid columns; crop=contextual, focus on human connection/technology; masking=none evident; frame=none
- **illustration:** role=Abstract representations of AI concepts; aspect=varied; crop=none; masking=none; frame=none

## Do's and Don'ts

### Do
- Adhere to the defined color palette, ensuring sufficient contrast between text and background, especially when using transparent white (e.g., '#ffffff80', '#fffc') variations. Reserve '--accent-purple' (#c094e4) for key interactive or highlight elements.
- Apply generous padding and ample whitespace around content blocks and sections to reinforce a balanced and restrained visual density across all viewports.
- Apply smooth transitions, using '--default-transition-duration' (0.15s) and '--default-transition-timing-function' (cubic-bezier(.4,0,.2,1)), to interactive elements to provide clear visual feedback on state changes.
- Apply tighter line heights (e.g., 1.1-1.2) for larger display and heading text to optimize visual density and readability, while maintaining a default line-height of 1.5 for body and caption text for legibility.
- Apply transition durations from the established set (e.g., '.15s', '.3s') with the 'cubic-bezier(.4,0,.2,1)' easing curve to ensure smooth and consistent interaction feedback across the interface.
- Consistently apply a large border-radius (e.g., `3.40282e38px` for 'rounded-full') to primary action buttons, and a smaller, consistent radius (e.g., `12px` or `0.75rem`) to content cards and secondary interactive elements.
- Ensure main content blocks (headings, core paragraphs) remain horizontally centered within their respective containers on desktop, while allowing for left-alignment where appropriate for detail text.
- Ensure sufficient contrast for foreground text elements using translucent white against the dark base, especially for body and secondary text.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | >= 48rem | Navigation displays all links horizontally.; Content areas utilize multi-column grids (e.g., 2, 3, or 4 columns).; Generous vertical padding applied to sections. |
| mobile | 0px - 47.9375rem (before 48rem) | Navigation transforms from a full menu to a hamburger icon ('Open menu').; Primary content area shrinks from 1440px to 390px (full viewport width).; Grid layouts likely collapse to single columns (e.g., from desktop multiple columns to grid-cols-1) where possible to optimize vertical scrolling.; Vertical spacing (e.g., padding-top) on sections may be reduced or absent, with a `pt-40` class observed. |
| tablet/medium | 48rem - 63.9375rem | Sections apply a padding-top of 70px (`md:pt-[70px]`).; Gap between grid items changes to 34px (`md:gap-[34px]`).; Grid columns may change from single to multiple (e.g., `md:grid-cols-2`). |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- specific_box_shadow_values: While box-shadow properties are referenced via CSS variables (e.g., '--tw-shadow'), the actual numeric and color values for these shadows are not provided in the captured evidence. This prevents precise definition of the depth model.
- Font licensing (Fellix): no explicit license found
- Font licensing (PP Fraktion Mono): no explicit license found

## Agent Prompt Guide

Quick Color Reference:
- accent: `#c094e4`
- text: `oklab(0.251963 0.0000115335 0.00000502169 / 0.6)`
- inverse text: `#fff6`
- background: `#fff3`

Quick Typography Reference:
- body: Fellix, 16px, 310, line-height 1.5
- headings: Fellix, 48px, 520, line-height 1.1
- ui: PP Fraktion Mono, 14px, 310, line-height 1.5

Implementation Rules:
- Adhere to the defined color palette, ensuring sufficient contrast between text and background, especially when using transparent white (e.g., '#ffffff80', '#fffc') variations. Reserve '--accent-purple' (#c094e4) for key interactive or highlight elements.
- Apply generous padding and ample whitespace around content blocks and sections to reinforce a balanced and restrained visual density across all viewports.
- Apply smooth transitions, using '--default-transition-duration' (0.15s) and '--default-transition-timing-function' (cubic-bezier(.4,0,.2,1)), to interactive elements to provide clear visual feedback on state changes.
- Apply tighter line heights (e.g., 1.1-1.2) for larger display and heading text to optimize visual density and readability, while maintaining a default line-height of 1.5 for body and caption text for legibility.
- Apply transition durations from the established set (e.g., '.15s', '.3s') with the 'cubic-bezier(.4,0,.2,1)' easing curve to ensure smooth and consistent interaction feedback across the interface.
- Consistently apply a large border-radius (e.g., `3.40282e38px` for 'rounded-full') to primary action buttons, and a smaller, consistent radius (e.g., `12px` or `0.75rem`) to content cards and secondary interactive elements.

Example Component Prompts:
1. Create a Navigation section for Hume AI - The Empathic AI Research Lab \\| Hume AIhume.ai logohume.ai logo using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a Primary Action Button component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.
3. Create a media block that uses abstract_digital_art as conceptual_illustration; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing, not a source to copy.
- Le Labo - reference for monochrome product restraint and terse commerce language.
- COS - reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-accent: #c094e4;
  --color-base-light: rgb(255, 255, 255);
  --color-dark-base: #222;
  --color-ink: oklab(0.251963 0.0000115335 0.00000502169 / 0.6);
  --color-surface: #fff3;
  --color-utility-transparent: #0000;
  --font-body: Fellix, sans-serif;
  --font-caption: Fellix, sans-serif;
  --font-body-lg: Fellix, sans-serif;
  --font-display-lg: Fellix, sans-serif;
  --font-heading-sm: Fellix, sans-serif;
  --font-ui: "PP Fraktion Mono", monospace;
  --radius-25rem: .25rem;
  --radius-375rem: .375rem;
  --radius-5rem: .5rem;
  --radius-0: 0;
  --radius-1-5rem: 1.5rem;
  --radius-1rem: 1rem;
  --radius-2-5rem: 2.5rem;
  --radius-3-40282e38px: 3.40282e38px;
  --layout-navigation-height: 64px;
  --layout-desktop-section-padding-top: 70px;
  --layout-grid-gap-mobile: 30px;
  --layout-grid-gap-desktop: 34px;
  --layout-max-content-width-desktop: 1280px;
}
```

### Tailwind v4

```css
@theme {
  --color-accent: #c094e4;
  --color-base-light: rgb(255, 255, 255);
  --color-dark-base: #222;
  --color-ink: oklab(0.251963 0.0000115335 0.00000502169 / 0.6);
  --color-surface: #fff3;
  --color-utility-transparent: #0000;
  --font-body: Fellix, sans-serif;
  --font-caption: Fellix, sans-serif;
  --font-body-lg: Fellix, sans-serif;
  --font-display-lg: Fellix, sans-serif;
  --font-heading-sm: Fellix, sans-serif;
  --font-ui: "PP Fraktion Mono", monospace;
  --radius-25rem: .25rem;
  --radius-375rem: .375rem;
  --radius-5rem: .5rem;
  --radius-0: 0;
  --radius-1-5rem: 1.5rem;
  --radius-1rem: 1rem;
  --radius-2-5rem: 2.5rem;
  --radius-3-40282e38px: 3.40282e38px;
  --layout-navigation-height: 64px;
  --layout-desktop-section-padding-top: 70px;
  --layout-grid-gap-mobile: 30px;
  --layout-grid-gap-desktop: 34px;
  --layout-max-content-width-desktop: 1280px;
}
```

