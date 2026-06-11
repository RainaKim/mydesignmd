---
version: alpha
name: Caldera - The Internet of Chains
description: Caldera is a network of interconnected, purpose-built blockchains, settling on Ethereum.
colors:
  primary: "#151317"
  color.accent: "#fc5000"
  color.dark-overlay-medium: "#15131733"
  color.surface.dark: "#070607"
  color.ink: "#000000"
  color.interactive-blue: "#1358df"
  color.ink.inverse: "#ffffff"
typography:
  font.body.lg:
    fontFamily: DM Sans, sans-serif
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.2
  font.body:
    fontFamily: DM Sans, sans-serif
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.2
  font.caption:
    fontFamily: sans-serif
    fontSize: 12px
  font.display.xl:
    fontFamily: PP Neue Corp Compact Ultrabold, sans-serif
    fontSize: 96px
    fontWeight: 900
  font.heading.lg:
    fontFamily: PP Neue Corp Compact Ultrabold, sans-serif
    fontSize: 48px
    fontWeight: 900
rounded:
  radius.input: 100px
  radius.32px: 32px
  radius.40px: 40px
  radius.pill: 800px
components:
  primary-cta-button:
    backgroundColor: "#fc5000"
    textColor: "#000000"
    rounded: 800px
  secondary-cta-button-outlined:
    backgroundColor: transparent
    textColor: "#000000"
    rounded: 800px
  article-slider-navigation-button:
    backgroundColor: transparent
    textColor: rgb(0,0,0)
    rounded: 40px
  primary-button:
    backgroundColor: rgb(252, 80, 0)
    textColor: rgb(0, 0, 238)
    rounded: 800px
    padding: 0px 12px
    typography: sans-serif
  feature-card:
    backgroundColor: "#151317"
    textColor: "#ffffff"
    rounded: 32px
sectionMap:
  default-content-sections:
    background: rgb(226, 226, 223)
    text: rgb(7, 6, 7)
    border: none
    media: dynamic
    layout: auto
  primary-cta:
    background: rgb(252, 80, 0)
    text: rgb(0, 0, 0)
    border: none
    media: none
    layout: auto
  secondary-cta-links:
    background: transparent
    text: rgb(0, 0, 238)
    border: none
    media: none
    layout: auto
buildTokens:
  layout.horizontal-content-padding-desktop: 56px
  layout.horizontal-content-padding-mobile: 12px
  layout.major-vertical-section-padding: 160px-200px
  layout.content-grid-gap-large: 64px
  layout.content-grid-gap-medium: 32px
  layout.content-grid-gap-small: 16px
---

# Caldera - The Internet of Chains — Style Reference
> modern, sophisticated, energetic, structured, high-contrast

**Theme:** dark

## Overview

Caldera builds a network of interconnected, purpose-built blockchains that settle on Ethereum. The brand positions itself as foundational infrastructure—not a flashy consumer app, but the layer beneath that makes customized, scalable blockchain solutions possible. This infrastructure-first posture shapes every visual decision: the design is unapologetically technical, confident in its complexity, and built to signal permanence and reliability to developers and institutions.

The central tension is between the highly technical nature of the product (modular rollups, settlement layers, chain orchestration) and the need to communicate this capability without overwhelming prospective partners. Caldera resolves this by leaning into bold, declarative typography paired with generous whitespace and a restrained color palette. The brand doesn't shy away from its technical depth—it frames it as a strength, using visual authority to suggest mastery rather than accessibility theater.

**Voice:** headlines=bold_declarative; body=informative_direct; microcopy=functional_instructive; ctas=action_oriented_empowering

## Colors

### Color Philosophy
The palette is deliberately minimal: a near-black canvas (#070607, #151317) anchors the interface, while the singular accent—a vivid electric orange (#fc5000)—operates as a high-signal element reserved for primary actions and critical wayfinding. This is not a "dark mode" aesthetic; it's an intentional choice to foreground content and reduce visual noise. The absence of gradients, tints, or decorative color variations reinforces the brand's infrastructural seriousness.

Surface colors function as atmospheric layers before they serve as decorative fills. The dark background (#070607) establishes the base environment; slightly lighter surfaces (#151317, #1f1e1f) create stacked planes for cards and nested components. This layering is subtle—1-2 shades of difference—relying on spacing and typography to communicate hierarchy rather than dramatic color shifts.

Foreground tokens maintain strict role distinctions: primary text, inverse text, and interactive elements each have dedicated colors that do not collapse into a single grayscale ramp. The strongest contrast pairing is monochrome—pure white (#ffffff) or pure black (#000000) on opposing dark or light grounds. Color is added only when evidence confirms its systemic role, not as ad-hoc decoration.

### Token Roles
#### Brand & Accent
- **{colors.color.accent}** (`#fc5000`): accent. use for buttons; links; highlights; avoid large_text_blocks; primary_backgrounds.
#### Surface
- **{colors.color.surface.dark}** (`#070607`): background. use for body; canvas.
- **{colors.color.surface.dark}** (`#151317`): surface. use for cards; sections; components.
- **{colors.color.surface.dark}** (`#1f1e1f`): surface. use for cards; nested_components.
#### Text
- **{colors.color.ink}** (`#000000`): foreground. use for text; hero_button; avoid dark_backgrounds.
- **{colors.color.ink.inverse}** (`#ffffff`): foreground. use for text; input_fields; avoid large_backgrounds.
#### Semantic
- **{colors.color.interactive-blue}** (`#1358df`): interactive. use for links; interactive_elements; avoid primary_text; large_backgrounds.
- **{colors.color.dark-overlay-medium}** (`#15131733`): overlay. use for cards; modals; interactive_backgrounds; avoid primary_backgrounds.

## Typography

### Typography Principles

Caldera's type system is a study in contrast—literally and hierarchically. PP Neue Corp Compact Ultrabold, set at extreme weights (900) and large sizes (48px–96px), delivers headlines with the visual force of industrial signage. These are not aspirational taglines; they're statements of capability, set tight with minimal line height to maximize impact and density.

Body copy uses DM Sans at medium weight (500) and comfortable sizes (16px–18px, line-height 1.2), creating a readable, approachable counterpoint to the aggressive display type. This pairing establishes a clear division: headlines command attention and declare intent; body text explains, informs, and reassures. Microcopy and captions default to a generic sans-serif at 12px, reinforcing their utilitarian, non-expressive role.

Typography is not a global font swap—it's a hierarchy of distinct roles. Display type is reserved for hero moments and section headings; body type handles all explanatory and navigational content; caption type manages metadata, labels, and fine print. Mixing these roles or collapsing the hierarchy dilutes the system's clarity.

### Font Family

- **DM Sans, sans-serif**; fallbacks: sans-serif.

- **DM Sans, sans-serif**; fallbacks: sans-serif.

- **sans-serif**.

- **PP Neue Corp Compact Ultrabold, sans-serif**; fallbacks: sans-serif.

- **PP Neue Corp Compact Ultrabold, sans-serif**; fallbacks: sans-serif.

- **PP Neue Corp Compact Ultrabold, sans-serif**; fallbacks: sans-serif.

- **PP Neue Corp Compact Ultrabold, sans-serif**; fallbacks: sans-serif.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body.lg} | 18px | 500 | 1.2 |  |  |
| {typography.font.body} | 16px | 500 | 1.2 |  |  |
| {typography.font.caption} | 12px |  |  |  |  |
| {typography.font.display.xl} | 80px | 900 |  |  |  |
| {typography.font.display.xl} | 56px | 900 |  |  |  |
| {typography.font.display.xl} | 96px | 900 |  |  |  |
| {typography.font.heading.lg} | 48px | 900 |  |  |  |

## Layout

### Composition Principles
Caldera's layouts are composed of full-width content sections separated by asymmetrical vertical spacing (100px–200px), creating distinct visual breaks that give each section room to breathe. This is not a uniform grid—section padding varies intentionally, allowing some blocks to feel expansive and others more compact based on content priority.

Content within sections frequently uses flexbox centering (`align-items: center; justify-content: center`) to anchor elements within their containers, while text alignment defaults to `start` (left-aligned). This creates a balanced tension: centered containers with left-reading text, maintaining both visual symmetry and reading flow.

The page operates at a fixed maximum width of 1440px, centered with responsive horizontal padding (56px on desktop, 12px on mobile). Whitespace is generous but not wasteful—large gaps (64px) separate major content groups; medium gaps (32px) divide related blocks; small gaps (16px) handle inline elements. This three-tier spacing system enforces consistent rhythm without requiring pixel-perfect uniformity.

Layouts are structured as named sections with explicit surface treatments, not as generic page containers. Each section carries its own background, text color, and media handling rules (see Section Treatment Map), allowing the design to shift contextually from dark informational blocks to bright CTAs without visual confusion.

### Rhythm
The vertical rhythm is deliberately non-uniform. Major section padding ranges from 160px to 200px, creating a breathing, varied cadence as users scroll. This variability prevents the monotony of strict grid systems while maintaining a sense of intentional pacing. Internal content spacing follows a more predictable pattern—64px for major divisions, 32px for grouped content, 16px for inline elements—but these values adapt at breakpoints to preserve visual density across devices.

Horizontal rhythm is constrained by the 1440px max-width container and responsive padding, ensuring content never touches viewport edges on large screens while maximizing usable space on mobile. The result is a layout that feels expansive on desktop (where generous whitespace reinforces the brand's confidence) and efficient on mobile (where reduced padding and tighter gaps maintain readability without cramping).

### Implementation Notes
- Container widths: Fixed container at 1440px maximum width, centered, with responsive horizontal padding.
- Flexible box layout with columnar and grid orientations for content sections.
- Content often uses `display: flex` with `align-items: center` and `justify-content: center` to center elements within their containers, while internal text alignment is typically `start` (left-aligned).

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Default Content Sections | rgb(226, 226, 223) | rgb(7, 6, 7) | none | dynamic | auto |  |
| Primary CTA | rgb(252, 80, 0) | rgb(0, 0, 0) | none | none | auto |  |
| Secondary CTA / Links | transparent | rgb(0, 0, 238) | none | none | auto |  |
| Default Content Sections | rgb(226, 226, 223) | rgb(7, 6, 7) | none | dynamic | auto |  |
| Primary CTA | rgb(252, 80, 0) | rgb(0, 0, 0) | none | none | auto |  |
| Secondary CTA / Links | transparent | rgb(0, 0, 238) | none | none | auto |  |

### Implementation Notes
- **layout.horizontal-content-padding-desktop**: `56px` — horizontal content constraint
- **layout.horizontal-content-padding-mobile**: `12px` — horizontal content constraint
- **layout.major-vertical-section-padding**: `160px-200px` — vertical spacing between main sections
- **layout.content-grid-gap-large**: `64px` — spacing between major grid items/sections
- **layout.content-grid-gap-medium**: `32px` — spacing between content groups
- **layout.content-grid-gap-small**: `16px` — spacing between individual items
- **layout.horizontal-content-padding-desktop**: `56px` — horizontal content constraint
- **layout.horizontal-content-padding-mobile**: `12px` — horizontal content constraint
- **layout.major-vertical-section-padding**: `160px-200px` — vertical spacing between main sections
- **layout.content-grid-gap-large**: `64px` — spacing between major grid items/sections
### Build Notes
- Ensure flexible container layouts with consistent horizontal padding based on viewport size.
- Implement a responsive grid system with adjusted gap values for different breakpoints to maintain visual density.
- Vertical section spacing is highly variable and should be implemented as observed, not uniform.
- Container widths: Fixed container at 1440px maximum width, centered, with responsive horizontal padding.
- Flexible box layout with columnar and grid orientations for content sections.
- Content often uses `display: flex` with `align-items: center` and `justify-content: center` to center elements within their containers, while internal text alignment is typically `start` (left-aligned).
- Ensure flexible container layouts with consistent horizontal padding based on viewport size.
- Implement a responsive grid system with adjusted gap values for different breakpoints to maintain visual density.

## Elevation & Depth

- tokens.shadows: The design does not appear to utilize direct CSS box-shadows or text-shadows for conveying depth or elevation. This indicates an intentional flat design approach.

### Borders

- **{borders.border.1-5px-dotted-070607}** (`1.5px dotted #070607`): accent_border_dark

- **{borders.border.1-5px-dotted-ffffff}** (`1.5px dotted #ffffff`): accent_border_light

- **{borders.border.none}** (`none`): absence_of_outline_or_border

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.32px} | 32px | responsive_container_rounding |
| {rounded.radius.40px} | 40px | container_rounding |
| {rounded.radius.input} | 100px | input_rounding |
| {rounded.radius.pill} | 800px | pill_shape_rounding |

## Components

### Buildable Component Recipes
#### Primary CTA Button
- **Component:** button
- **Background:** #fc5000
- **Text:** #000000
- **Border:** none
- **Radius:** 800px

#### Secondary CTA Button (outlined)
- **Component:** button
- **Background:** transparent
- **Text:** #000000
- **Border:** 1.5px dotted #070607
- **Radius:** 800px

#### Article Slider Navigation Button
- **Component:** button
- **Background:** transparent
- **Text:** rgb(0,0,0)
- **Border:** none
- **Radius:** 40px

#### primary_button
- **Component:** Primary Button
- **Background:** rgb(252, 80, 0)
- **Text:** rgb(0, 0, 238)
- **Border:** 0px
- **Radius:** 800px
- **Padding:** 0px 12px
- **Typography:** sans-serif

#### Primary CTA Button
- **Component:** button
- **Background:** #fc5000
- **Text:** #000000
- **Border:** none
- **Radius:** 800px

#### Secondary CTA Button (outlined)
- **Component:** button
- **Background:** transparent
- **Text:** #000000
- **Border:** 1.5px dotted #070607
- **Radius:** 800px

#### Article Slider Navigation Button
- **Component:** button
- **Background:** transparent
- **Text:** rgb(0,0,0)
- **Border:** none
- **Radius:** 40px

#### Feature Card
- **Component:** card
- **Background:** #151317
- **Text:** #ffffff
- **Border:** none
- **Radius:** 32px

### CTA Buttons
Caldera's button system operates on a clear visual hierarchy tied to user intent. Primary CTAs use the brand's electric orange (#fc5000) with black text and an 800px pill radius, creating unmistakable focal points for high-priority actions like "Get Started" or "Deploy Chain." These buttons are never used for tertiary actions—their visual weight is reserved for moments of conversion.

Secondary CTAs maintain the pill shape but use transparent backgrounds with a 1.5px dotted border (#070607 on light, #ffffff on dark). This creates a "ghost button" effect that signals importance without competing with primary actions. The dotted border is a distinctive brand flourish—subtle enough to avoid novelty, but specific enough to differentiate Caldera's buttons from generic outlined variants.

Article slider navigation buttons are minimal and functional: transparent backgrounds, 40px radius (softer than the pill but still rounded), no borders. These buttons prioritize usability over visual dominance, appearing only when needed and receding when inactive. Hover states introduce subtle transforms and transitions to provide feedback without distraction—this is infrastructure UI, not entertainment.

### Feature Grid Card
Feature cards are dark (#151317), rounded (32px), and text-light (#ffffff), designed to sit comfortably on the near-black canvas while maintaining legible contrast. Each card contains a heading (likely PP Neue Corp Compact Ultrabold at 48px), body text (DM Sans at 16px), and an interactive link or CTA, typically styled with the interactive blue (#1358df) to differentiate it from static content.

Cards are displayed in responsive grids with variable gaps (64px on desktop, 32px on tablet, 16px on mobile), allowing content density to adapt without compromising readability. Optional media placeholders (illustrations or photography) follow flexible aspect ratios with cover cropping, ensuring visual consistency even when image sources vary.

The cards avoid decorative shadows or borders, relying instead on the slight luminance difference between the card surface (#151317) and the page background (#070607) to establish their presence. This flat approach keeps the focus on content hierarchy—headline, description, action—rather than visual ornamentation.

### Photography & Media
- **illustration:** role=explanatory_or_heroic; aspect=varied; crop=fit_or_contain; masking=none; frame=none
- **photography:** role=decorative_background_or_feature; aspect=flexible; crop=cover; masking=none; frame=none

## Do's and Don'ts

### Do
- Always specify a generic 'sans-serif' fallback for all custom font families to ensure graceful degradation and consistent text rendering across diverse user environments.
- Apply rounded corner radii consistently: use 40px for primary container elements, 100px for input fields to create a 'pill' like effect, and 800px for explicitly pill-shaped components.
- Apply subtle transitions and transforms on interactive elements like buttons to provide visual feedback without being distracting.
- Center primary content blocks within their parent containers using flexbox `align-items: center` and `justify-content: center` to maintain visual balance.
- Differentiate primary CTAs with an `#fc5000` background and black text, while secondary actions use transparent backgrounds or dotted borders with blue text for links.
- Apply `dark_overlay_medium` (#15131733) sparingly for subtle visual depth in card shadows or interactive background states—never as a primary surface color.
- Ensure high contrast ratios when pairing white text (#ffffff) on dark surfaces (#151317, #070607) or black text (#000000) on light grounds—readability is non-negotiable in an infrastructure brand.
- Reserve the accent orange (#fc5000) exclusively for high-priority CTAs and critical wayfinding elements to preserve its signal strength. Overuse dilutes its effectiveness.
### Don't
- Avoid introducing light background canvases (whites, pastels, bright tints) that would undermine the high-contrast dark theme and diminish the visual impact of the primary orange accent.
- Refrain from using decorative, whimsical, or casual typography (script fonts, playful sans-serifs, exaggerated letter-spacing) that contradicts the brand's authoritative, technical, and forward-looking posture. Caldera is infrastructure, not lifestyle.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| Medium Desktop | (min-width: 1000px) and (max-width: 1299px) | Minor adjustments to spacing (e.g., 8px gap on `.framer-15mpuu1`) to optimize content flow within the specific width range. |
| Mobile | (max-width: 767px) | Horizontal padding reduced to 12px for main content areas and specific sections (e.g., 24px 12px for certain paddings).; Vertical spacing (gap) between elements significantly reduced, e.g., from 40-64px to 24px or 8px in various components.; Cluster structures reorient from mixed/grid layouts to primarily columnar stacking.; Overall visual density increases due to reduced whitespace, but remains breathable. |
| Tablet/Small Desktop | (min-width: 768px) and (max-width: 999px) | Intermediate adjustments to `gap` values (e.g., 24px, 40px, 32px) as content adapts between mobile stacking and larger desktop layouts. |
| tablet | (min-width: 768px) and (max-width: 999px) | Uses intermediate gap values (e.g., 24px, 32px, 40px).; Padding is 24px. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- tokens.shadows: The design does not appear to utilize direct CSS box-shadows or text-shadows for conveying depth or elevation. This indicates an intentional flat design approach.
- Some exact token values were not found in CSS/computed evidence.
- Font licensing (DM Sans, sans-serif): inferred
- Font licensing (sans-serif): system default
- Font licensing (PP Neue Corp Compact Ultrabold, sans-serif): inferred

## Agent Prompt Guide

Quick Color Reference:
- accent: `#fc5000`
- background: `#151317`
- inverse text: `#000000`

Quick Typography Reference:
- body: DM Sans, sans-serif, 18px, 500, line-height 1.2
- headings: PP Neue Corp Compact Ultrabold, sans-serif, 80px, 900

Implementation Rules:
- Always specify a generic 'sans-serif' fallback for all custom font families to ensure graceful degradation and consistent text rendering across diverse user environments.
- Apply rounded corner radii consistently: use 40px for primary container elements, 100px for input fields to create a 'pill' like effect, and 800px for explicitly pill-shaped components.
- Apply subtle transitions and transforms on interactive elements like buttons to provide visual feedback without being distracting.
- Center primary content blocks within their parent containers using flexbox `align-items: center` and `justify-content: center` to maintain visual balance.
- Differentiate primary CTAs with an `#fc5000` background and black text, while secondary actions use transparent backgrounds or dotted borders with blue text for links.
- Do apply `dark_overlay_medium` consistently for subtle visual depth like card shadows or interactive background states, avoiding overuse for primary elements.

Example Component Prompts:
1. Create a Default Content Sections section for Caldera - The Internet of Chains using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a Primary CTA Button component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.
3. Create a media block that uses illustration as explanatory_or_heroic; preserve crop, framing, aspect ratio, and forbidden substitutions.

## Similar Brands

No taste references were established from the available evidence.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-accent: #fc5000;
  --color-dark-overlay-medium: #15131733;
  --color-surface-dark: #151317;
  --color-ink: #000000;
  --color-interactive-blue: #1358df;
  --color-ink-inverse: #ffffff;
  --font-body-lg: "DM Sans, sans-serif", sans-serif;
  --font-body: "DM Sans, sans-serif", sans-serif;
  --font-caption: sans-serif;
  --font-display-xl: "PP Neue Corp Compact Ultrabold, sans-serif", sans-serif;
  --font-heading-lg: "PP Neue Corp Compact Ultrabold, sans-serif", sans-serif;
  --radius-input: 100px;
  --radius-32px: 32px;
  --radius-40px: 40px;
  --radius-pill: 800px;
  --layout-horizontal-content-padding-desktop: 56px;
  --layout-horizontal-content-padding-mobile: 12px;
  --layout-major-vertical-section-padding: 160px-200px;
  --layout-content-grid-gap-large: 64px;
  --layout-content-grid-gap-medium: 32px;
  --layout-content-grid-gap-small: 16px;
}
```

### Tailwind v4

```css
@theme {
  --color-accent: #fc5000;
  --color-dark-overlay-medium: #15131733;
  --color-surface-dark: #151317;
  --color-ink: #000000;
  --color-interactive-blue: #1358df;
  --color-ink-inverse: #ffffff;
  --font-body-lg: "DM Sans, sans-serif", sans-serif;
  --font-body: "DM Sans, sans-serif", sans-serif;
  --font-caption: sans-serif;
  --font-display-xl: "PP Neue Corp Compact Ultrabold, sans-serif", sans-serif;
  --font-heading-lg: "PP Neue Corp Compact Ultrabold, sans-serif", sans-serif;
  --radius-input: 100px;
  --radius-32px: 32px;
  --radius-40px: 40px;
  --radius-pill: 800px;
  --layout-horizontal-content-padding-desktop: 56px;
  --layout-horizontal-content-padding-mobile: 12px;
  --layout-major-vertical-section-padding: 160px-200px;
  --layout-content-grid-gap-large: 64px;
  --layout-content-grid-gap-medium: 32px;
  --layout-content-grid-gap-small: 16px;
}
```
