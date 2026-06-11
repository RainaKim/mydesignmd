---
version: alpha
name: "Modal: High-performance AI infrastructure"
description: Bring your own code, and run CPU, GPU, and data-intensive compute at scale. The serverless platform for AI and data teams.
colors:
  primary: "#fff"
  color.accent: "#7fee6433"
  color.surface: "#ffffff0d"
  color.border: "#fff3"
  color.focus-ring: "#7fee6480"
  color.ink: oklch(21% .034 264.665)
typography:
  font.body.lg:
    fontFamily: Inter Variable
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.75
    role: Large body text
  font.body:
    fontFamily: Inter Variable
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.75
    role: Standard body text
  font.ui:
    fontFamily: Inter Variable
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    role: Caption or small label
  font.display:
    fontFamily: Goga
    fontSize: 30px
    fontWeight: 800
    lineHeight: 1.1
    role: Secondary display headline
  font.display.lg:
    fontFamily: Goga
    fontSize: 54px
    fontWeight: 800
    lineHeight: 1
    role: Primary display headline
rounded:
  radius.full: 100%
  radius.medium-md: .375rem
  radius.none: 0
  radius.small-sm: .25rem
---

# Modal: High-performance AI infrastructure — Style Reference
> technical, modern, sophisticated, high-contrast, code-focused

**Theme:** light

## Overview

Modal is a high-performance AI infrastructure platform, a production cloud for AI designed to run CPU, GPU, and data-intensive compute at scale.

The platform addresses the need for instant, scalable, and commitment-free access to high-performance AI compute, simplifying complex infrastructure into code.

**Voice:** headlines=direct_and_declarative; body=informative_and_technical; microcopy=supportive_and_instructive; ctas=action-oriented_and_benefit-driven

## Colors

### Color Philosophy
- Treat surface colors as the page atmosphere before using them as decorative fills.
- Keep foreground tokens role-specific: primary text, secondary text, placeholder text, and inverse text should not collapse into one gray scale.
### Token Roles
#### Brand & Accent
- **{colors.color.accent}** (`#7fee6433`): accent_interactive. use for primary_buttons; hover_states; active_states.
- **{colors.color.surface}** (`#fff`): surface_primary_light. use for light_theme; toast; input_field.
- **{colors.color.ink}** (`oklch(21% .034 264.665)`): text_primary. use for text; links; bold_text.
#### Hairlines & Borders
- **{colors.color.border}** (`oklch(55.1% .027 264.364)`): border_input. use for input_fields; placeholders; checkboxes.
- **{colors.color.border}** (`#fff3`): border_subtle. use for dark_background; outlined_buttons; subtle_text.
#### Semantic
- **{colors.color.focus-ring}** (`#7fee6480`): focus_indicator. use for interactive_elements; form_controls.
#### Surface
- **{colors.color.surface}** (`#ffffff1a`): surface_interactive. use for dark_background; interactive_elements.
- **{colors.color.surface}** (`#ffffff0d`): surface_interactive. use for dark_background; interactive_elements.

## Typography

### Typography Principles

- Treat typography as a hierarchy of roles, not a global font swap: Inter Variable; Goga.

- Keep expressive heading families reserved for display moments; do not leak them into dense controls or utility text unless evidenced.

- Match type hierarchy to the content voice: headline posture, utility labels, and CTA tone should remain distinct.

### Font Family

- **Inter Variable**; fallbacks: ui-sans-serif; system-ui; sans-serif; role: Caption or small label.

- **Inter Variable**; fallbacks: ui-sans-serif; system-ui; sans-serif; role: Large body text.

- **Goga**; role: Primary display headline.

- **Goga**; role: Secondary display headline.

- **Inter Variable**; fallbacks: ui-sans-serif; system-ui; sans-serif; role: Standard body text.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.ui} | 14px | 400 | 1.5 |  | Caption or small label |
| {typography.font.body.lg} | 20px | 400 | 1.75 |  | Large body text |
| {typography.font.display.lg} | 54px | 800 | 1 |  | Primary display headline |
| {typography.font.display} | 30px | 800 | 1.1 |  | Secondary display headline |
| {typography.font.body} | 16px | 400 | 1.75 |  | Standard body text |

### Principles

- **Caption or small label**: use `Inter Variable`; size `14px`; weight `400`.

- **Large body text**: use `Inter Variable`; size `20px`; weight `400`.

- **Primary display headline**: use `Goga`; size `54px`; weight `800`.

- **Secondary display headline**: use `Goga`; size `30px`; weight `800`.

- **Standard body text**: use `Inter Variable`; size `16px`; weight `400`.

## Layout

### Composition Principles
- Modular, with generous vertical spacing between primary content sections. Not a strict, uniform rhythm across the entire page.
- Modular, with varying vertical spacing between major sections. Within prose blocks, `em` units (e.g., 1em, 1.25em, 1.6em, 2em) define vertical rhythm for text elements and components.
- Content is predominantly left-aligned within its respective containers. Some elements use flexbox for internal alignment (e.g., justify-content for buttons).
- Content density is 'media-led', meaning it adapts based on the type and amount of media/content, rather than following a strict global standard. Spacing tokens suggest a balanced to generous density within prose.
- Compose pages as named sections with explicit surface, text, media, and component treatment instead of one generic page container.
### Rhythm
- Modular, with varying vertical spacing between major sections. Within prose blocks, `em` units (e.g., 1em, 1.25em, 1.6em, 2em) define vertical rhythm for text elements and components.
- Modular, with generous vertical spacing between primary content sections. Not a strict, uniform rhythm across the entire page.
- Content density is 'media-led', meaning it adapts based on the type and amount of media/content, rather than following a strict global standard. Spacing tokens suggest a balanced to generous density within prose.
### Implementation Notes
- Container widths: Desktop main content: 1304px (e.g., navigation, primary headings); Desktop sections: 1400px (with implicit 20px horizontal padding within a 1440px viewport); Mobile content area: inferred ~358px (within a 390px viewport, suggesting ~16px horizontal padding)
- CSS Grid is utilized for arranging elements, with defined horizontal gaps (e.g., gap-x-5).
- Content is predominantly left-aligned within its respective containers. Some elements use flexbox for internal alignment (e.g., justify-content for buttons).

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Hero | rgb(33, 37, 37) | rgb(221, 255, 220) |  |  | Dark |  |
| Features & Benefits (Dark Mode) | rgb(33, 37, 37) | rgb(221, 255, 220) |  | rgb(24, 24, 24) | Dark |  |
| Features & Benefits (Light Mode, Inferred) | rgb(222, 240, 221) | rgb(0, 0, 0) |  |  | Light |  |
| Customer Stories | rgb(0, 0, 0) | rgb(221, 255, 220) |  | rgb(24, 24, 24) | Dark |  |
| Call to Action | rgb(0, 0, 0) | rgb(221, 255, 220) |  |  | Dark |  |

### Implementation Notes
- **layout.navigation-height**: `48px` — layout
- **layout.content-max-width**: `1304px` — layout
- **layout.section-horizontal-padding**: `20px (desktop), 16px (mobile)` — layout
- **layout.vertical-section-spacing**: `64px (desktop, from my-16), 40px (desktop, from mb-10), adaptable for mobile` — layout
- **layout.grid-gap**: `20px (from gap-x-5)` — layout
- **layout.paragraph-vertical-spacing**: `1.25em` — layout
### Build Notes
- Ensure consistent application of Tailwind-like utility classes for spacing and layout for maintainability.
- Implement responsive behavior with `md:` and other breakpoints as observed in CSS, particularly for grid-to-stack transitions.
- Pay attention to `:hover` and `:active` states for buttons, as they involve specific color and filter changes.

## Elevation & Depth

No shadow or elevation system is evidenced.

### Borders

- **{borders.border.default}** (`1px`): structural_divider

- **{borders.border.no-border}** (`0 solid`): border_absence

- **{borders.border.themed-component-boundary}** (`1px solid var(--normal-border)`): structural_divider

- **{borders.border.transparent-focus-outline}** (`2px solid #0000`): accessibility_outline

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.none} | 0 | shape_corner |
| {rounded.radius.full} | 100% | shape_corner |
| {rounded.radius.medium-md} | .375rem | shape_corner |
| {rounded.radius.small-sm} | .25rem | shape_corner |

## Components

### Buildable Component Recipes
#### Primary Marketing Button
- **Component:** button
- **Background:** rgb(127, 238, 100)
- **Text:** rgb(0, 0, 0)
- **Border:** none
- **Radius:** 3.35544e+07px

#### Secondary Marketing Button (Dark BG)
- **Component:** button
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(221, 255, 220)
- **Border:** oklab(0.966498 -0.0472349 0.0339288 / 0.3) 1px solid
- **Radius:** 3.35544e+07px

#### Secondary Marketing Button (Light BG)
- **Component:** button
- **Background:** rgba(0, 0, 0, 0)
- **Text:** rgb(62, 74, 60)
- **Border:** rgb(62, 74, 60) 1px solid
- **Radius:** 3.35544e+07px

#### Story Card
- **Component:** card
- **Background:** rgb(24, 24, 24)
- **Text:** rgb(221, 255, 220)
- **Border:** none
- **Radius:** 12px

### Button
A primary interactive element used to trigger actions or navigate. Available in various visual styles, themes, and states, including primary and secondary variants, and custom color options.

### Story Card
A display component for showcasing content such as customer testimonials or data points, typically featuring text, visual elements, and interactive hover effects.

### Photography & Media
- **abstract_illustrations:** role=atmospheric_background; aspect=dynamic; crop=fill_container; masking=none; frame=none
- **image/media:** role=Illustrative/Contextual; aspect=varied (often filling grid areas or as full-width hero elements); crop=Focal point-based, adapting dynamically to layout changes; masking=None apparent, standard rectangular; frame=None

## Do's and Don'ts

### Do
- Always use a dark background color palette (e.g., rgb(33, 37, 37) or rgb(24, 24, 24)) with primary elements highlighted by vibrant green, maintaining high contrast for readability.
- Apply a consistent rapid transition duration (0.15s) for most UI interactions. Reserve complex cubic-bezier easing and staggered animations for key, nuanced interactive components to enhance perceived responsiveness and delight, avoiding overuse for simple elements.
- Apply rounded corners (e.g., full pill shape for buttons, 12px for cards) consistently to interactive elements and content blocks to maintain visual cohesion.
- Apply subtle transition effects to interactive elements to maintain a restrained and polished user experience.
- Apply the bright green (#7fee6480) as the primary accent for focus indicators to maintain strong visual feedback for interactive elements.
- Consistently apply visual feedback for interactive states (hover, active, focus-visible) across all button variants and other interactive components, leveraging defined transition tokens.
- Employ 'Goga' font for primary headings to convey a modern, technical aesthetic, ensuring large font sizes (e.g., 54px for H2) for clear hierarchy and impact.
- Employ conditional display utilities (e.g., `md:hidden`, `md:block`) to manage component visibility across different breakpoints effectively.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | (width>=1024px) | Enables multi-column layouts for content sections (e.g., two-column layouts for feature descriptions).; Larger horizontal content areas and wider gutters. |
| mobile | (width<=600px) | Content typically collapses to a single-column layout.; Reduced horizontal padding (e.g., 16px) compared to desktop. |
| universal | (hover:hover) |  |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- Strict Global Vertical Rhythm: There is no single, site-wide consistent vertical rhythm applied to all sections and content blocks, but rather a more modular, context-dependent approach.
- extraction_artifact: No direct evidence for 'letter-spacing' values was found for any typography tokens. The field is set to an empty string.
- extraction_artifact: Direct CSS evidence linking specific font-weight and line-height values to 'Goga' and 'Inter Variable' font families for their observed sizes is missing. Values for 'weight' and 'line_height' have been inferred based on general CSS rules for headings/body text and common typographic practices.
- extraction_artifact: The browser encountered and cleaned up visible overlay layers on both desktop and mobile viewports during analysis, which could potentially obscure or shift elements. This might subtly impact the perceived layout or spacing of elements that were underneath the overlay.
- extraction_artifact: There is a discrepancy in font family evidence. CSS tokens indicate 'degular' (from Typekit) and several 'KaTeX' families, while computed styles for headings clearly show 'Goga'. The rendered headings on the site use 'Goga', suggesting it is the intended primary display font.

## Agent Prompt Guide

Quick Color Reference:
- accent: `#7fee6433`
- background: `#fff`
- border: `oklch(55.1% .027 264.364)`
- text: `oklch(21% .034 264.665)`

Quick Typography Reference:
- body: Inter Variable, 20px, 400, line-height 1.75
- ui: Inter Variable, 14px, 400, line-height 1.5
- headings: Goga, 30px, 800, line-height 1.1

Implementation Rules:
- Always use a dark background color palette (e.g., rgb(33, 37, 37) or rgb(24, 24, 24)) with primary elements highlighted by vibrant green, maintaining high contrast for readability.
- Apply a consistent rapid transition duration (0.15s) for most UI interactions. Reserve complex cubic-bezier easing and staggered animations for key, nuanced interactive components to enhance perceived responsiveness and delight, avoiding overuse for simple elements.
- Apply rounded corners (e.g., full pill shape for buttons, 12px for cards) consistently to interactive elements and content blocks to maintain visual cohesion.
- Apply subtle transition effects to interactive elements to maintain a restrained and polished user experience.
- Apply the bright green (#7fee6480) as the primary accent for focus indicators to maintain strong visual feedback for interactive elements.
- Consistently apply visual feedback for interactive states (hover, active, focus-visible) across all button variants and other interactive components, leveraging defined transition tokens.

Example Component Prompts:
1. Create a Hero section for Modal: High-performance AI infrastructure using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a Primary Marketing Button component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.
3. Create a media block that uses abstract_illustrations as atmospheric_background; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing, not a source to copy.
- Le Labo - reference for monochrome product restraint and terse commerce language.
- COS - reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-accent: #7fee6433;
  --color-surface: #fff;
  --color-border: oklch(55.1% .027 264.364);
  --color-focus-ring: #7fee6480;
  --color-ink: oklch(21% .034 264.665);
  --font-body-lg: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-body: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-ui: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-display: Goga;
  --font-display-lg: Goga;
  --radius-full: 100%;
  --radius-medium-md: .375rem;
  --radius-none: 0;
  --radius-small-sm: .25rem;
  --layout-navigation-height: 48px;
  --layout-content-max-width: 1304px;
  --layout-section-horizontal-padding: 20px (desktop), 16px (mobile);
  --layout-vertical-section-spacing: 64px (desktop, from my-16), 40px (desktop, from mb-10), adaptable for mobile;
  --layout-grid-gap: 20px (from gap-x-5);
  --layout-paragraph-vertical-spacing: 1.25em;
}
```

### Tailwind v4

```css
@theme {
  --color-accent: #7fee6433;
  --color-surface: #fff;
  --color-border: oklch(55.1% .027 264.364);
  --color-focus-ring: #7fee6480;
  --color-ink: oklch(21% .034 264.665);
  --font-body-lg: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-body: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-ui: "Inter Variable", ui-sans-serif, system-ui, sans-serif;
  --font-display: Goga;
  --font-display-lg: Goga;
  --radius-full: 100%;
  --radius-medium-md: .375rem;
  --radius-none: 0;
  --radius-small-sm: .25rem;
  --layout-navigation-height: 48px;
  --layout-content-max-width: 1304px;
  --layout-section-horizontal-padding: 20px (desktop), 16px (mobile);
  --layout-vertical-section-spacing: 64px (desktop, from my-16), 40px (desktop, from mb-10), adaptable for mobile;
  --layout-grid-gap: 20px (from gap-x-5);
  --layout-paragraph-vertical-spacing: 1.25em;
}
```

