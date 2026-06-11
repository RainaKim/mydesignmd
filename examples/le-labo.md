---
version: alpha
name: Le Labo Fragrances \\| Niche Perfumes and Candles
description: Explore Le Labo's fine fragrances in personalized perfumes, candles, shampoo, lotion and more. Shop women's and men's signature scents online.
colors:
  primary: "#000"
  color.ink: "#6c6c6c"
  color.border: "#e5e5e5"
  color.text.muted: "#424242"
  color.action: "#595959"
  color.canvas: "#f6f8f6"
  color.surface: "#ffffff"
typography:
  font.body:
    fontFamily: "Bell Gothic Std", "Arial", "Helvetica", sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.3
  font.ui:
    fontFamily: "Bell Gothic Std", "Arial", "Helvetica", sans-serif
    fontSize: 15px
    fontWeight: normal
    lineHeight: 1.5
  font.heading.md:
    fontFamily: "Bell Gothic Std", "Arial", "Helvetica", sans-serif
    fontSize: 23px
    fontWeight: normal
    lineHeight: 1.2
  font.display:
    fontFamily: "Bell Gothic Std", "Arial", "Helvetica", sans-serif
    fontSize: 30px
    fontWeight: normal
    lineHeight: 1.3
rounded:
  radius.0: 0
  radius.30px: 30px
  radius.3px: 3px
  radius.4px: 4px
  radius.50: 50%
  radius.5px: 5px
shadows:
  shadow.0-0-0-1px-ebebeb: "0 0 0 1px #ebebeb"
  shadow.0-0-2px-1px-rgba-0-0-0-15: 0 0 2px 1px rgba(0,0,0,.15)
  shadow.0-0-2px-1px-rgba-0-0-0-2: 0 0 2px 1px rgba(0,0,0,.2)
  shadow.0-0-3px-1px-rgb-94-158-214: 0 0 3px 1px rgb(94,158,214)
  shadow.0-0-5px-666: "0 0 5px #666"
  shadow.0-0-5px-rgba-0-0-0-0-1: 0 0 5px rgba(0, 0, 0, 0.1)
  shadow.0-1px-0-rgba-0-0-0-0-05-inset-0-1px-0-rgba-255-255-255-0-8: 0 1px 0 rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.8)
  shadow.none: none
components:
  button-primary:
    backgroundColor: "#000"
    textColor: "#FFF"
    rounded: 50px
  button-secondary:
    backgroundColor: transparent
    textColor: "#000"
    rounded: 50px
  navigation-link:
    backgroundColor: transparent
    textColor: "#424242"
    rounded: 0px
  primary-button:
    backgroundColor: rgb(0, 0, 0)
    textColor: rgb(255, 255, 255)
    rounded: 50px
    padding: 10px 10px
    typography: Bell Gothic Std
sectionMap:
  header:
    background: "#FFF"
    text: "#000"
    border: "#ebebeb"
    media: N/A
    layout: "inferred: standard height with logo and navigation"
  hero-main-content:
    background: "#f6f8f6"
    text: "#404040"
    border: "#ebebeb"
    media: N/A
    layout: "inferred: full-width or container-constrained"
  footer:
    background: "#000"
    text: "#FFF"
    border: "#ebebeb"
    media: N/A
    layout: multi-column with navigation links
buildTokens:
  layout.page-max-width: "inferred: ~1440px for desktop"
  layout.page-padding: "inferred: 15px to 40px depending on viewport and section"
  layout.section-gap: "inferred: 40px+"
  layout.header-height: "inferred: ~80px desktop, ~80px mobile"
  layout.card-gutter: "inferred: 20px"
---

# Le Labo Fragrances \\| Niche Perfumes and Candles — Style Reference
> elegant, minimalist, monochromatic, understated, sophisticated

**Theme:** light

## Overview

Le Labo is rooted in the craft of fine fragrance: hand-blended, personalized scents made from high-quality raw materials. The brand's identity hinges on artisanal production, olfactory authenticity, and an editorial sensibility that appeals to discerning customers seeking unique, luxurious experiences beyond mass-market perfumery.

The central design challenge is balancing Le Labo's distinct, opinionated point of view with an online presence that feels effortlessly navigable, never precious or inaccessible.

**Voice:** headlines=Direct_and_evocative; body=Descriptive_and_refined; microcopy=Clear_and_instructive; ctas=Action-oriented_and_understated

## Colors

### Color Philosophy

Le Labo's palette is fundamentally monochromatic: black (`#000`) serves as the primary text and accent color, while subtle mid-grays (`#6c6c6c`, `#424242`, `#595959`) differentiate secondary text, muted UI elements, and interactive states. Borders and dividers live at `#e5e5e5` and `#ebebeb`—faint but legible hairlines that structure the page without adding visual weight. The near-white canvas (`#f6f8f6`) creates breathing room around hero content, while pure white (`#ffffff`) is reserved for cards, modals, and content surfaces.

This system prioritizes hierarchy through tone, not hue. Contrast is achieved through black-on-white relationships rather than color accents, reinforcing the brand's editorial restraint and refusing decorative flourish.

### Token Roles
#### Brand & Accent
- **{colors.color.action}** (`#595959`): action_primary. use for button.
- **{colors.color.border}** (`#ebebeb`): border_primary. use for input_field; container; divider.
- **{colors.color.ink}** (`#000`): text_primary. use for text; icon; body_overlay.
#### Hairlines & Borders
- **{colors.color.border}** (`#e5e5e5`): border_secondary. use for input_field; container; mini_cart_item.
#### Surface
- **{colors.color.surface}** (`#ffffff`): surface_base. use for page; card; modal; dropdown_menu.
- **{colors.color.canvas}** (`#f6f8f6`): surface_subtle. use for page; header; popup.
#### Text
- **{colors.color.text.muted}** (`#424242`): text_secondary. use for text; link; button_background.
- **{colors.color.ink}** (`#6c6c6c`): text_tertiary. use for text; button_link.

## Typography

### Typography Principles

Bell Gothic Std is the sole typeface, deployed uniformly across headlines, body copy, navigation, and UI labels. The system relies on size, weight, and line-height variation—not font switching—to establish hierarchy. This mono-typeface approach reinforces editorial consistency and restraint: every piece of text reads as part of a unified voice.

Type hierarchy serves content, not decoration. Headlines (30px) anchor attention without shouting. Body text (14px at 400 weight, 1.3 line-height) is set tight for legibility at small sizes. UI labels (15px, normal weight, 1.5 line-height) give interactive elements slightly more air. All type is left-aligned within content blocks, never centered unless framing an isolated CTA or logotype.

### Font Family

- **"Bell Gothic Std", "Arial", "Helvetica", sans-serif**; fallbacks: Arial; Helvetica; sans-serif.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 14px | 400 | 1.3 |  |  |
| {typography.font.ui} | 16px | 100 | 1.5 |  |  |
| {typography.font.heading.md} | 23px | normal | 1.2 |  |  |
| {typography.font.display} | 30px | normal | 1.3 |  |  |
| {typography.font.ui} | 15px | normal | 1.5 |  |  |

### Principles

- **Body Copy**: use `"Bell Gothic Std", "Arial", "Helvetica", sans-serif`; size `14px`; weight `400`.

- **Button Text**: use `"Bell Gothic Std", "Arial", "Helvetica", sans-serif`; size `16px`; weight `100`.

- **Hero Headline**: use `"Bell Gothic Std", "Arial", "Helvetica", sans-serif`; size `30px`; weight `normal`.

- **Navigation Menu Item**: use `"Bell Gothic Std", "Arial", "Helvetica", sans-serif`; size `15px`; weight `normal`.

- **Section Headline**: use `"Bell Gothic Std", "Arial", "Helvetica", sans-serif`; size `23px`; weight `normal`.

## Layout

### Composition Principles

Le Labo's layout system prioritizes generous whitespace and vertical rhythm over dense information architecture. Content is organized into named sections (header, hero, footer), each with its own explicit background, text treatment, and structural logic. Spacing between sections follows a stepped rhythm: 20px for tight internal groupings, 30px for component separation, 40px+ for major section breaks.

Horizontal padding shifts responsively—15px on mobile, scaling to 40px on larger viewports—while content never exceeds an inferred ~1440px max-width on desktop. The header maintains a consistent ~80px height across breakpoints. Product grids are spaced with 20px gutters, creating a clean matrix that allows imagery to lead without crowding.

Text is predominantly left-aligned within content blocks, with centered treatments reserved for isolated CTAs, mobile navigation states, or hero lockups. The system is built on a hybrid layout approach: flexbox and table-cell for content flow, explicit grid for modals and structured overlays.

### Rhythm

- stepped vertical rhythm (20px, 30px, 40px)
- consistent vertical separation using padding and margins, often at 20px, 30px, or 40px intervals
- balanced, media-led content with generous padding around main sections

### Implementation Notes

- hybrid (flex/table-cell for content, explicit grid for modals)
- predominantly left-aligned within content blocks, with centered elements for actions and navigation on smaller viewports

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Header | #FFF | #000 | #ebebeb | N/A | inferred: standard height with logo and navigation |  |
| Hero/Main Content | #f6f8f6 | #404040 | #ebebeb | N/A | inferred: full-width or container-constrained |  |
| Footer | #000 | #FFF | #ebebeb | N/A | multi-column with navigation links |  |
| header | #FFF | #000 | #ebebeb | N/A | inferred: standard height with logo and navigation |  |
| hero-main-content | #f6f8f6 | #404040 | #ebebeb | N/A | inferred: full-width or container-constrained |  |
| footer | #000 | #FFF | #ebebeb | N/A | multi-column with navigation links |  |

### Implementation Notes
- **layout.page-max-width**: `inferred: ~1440px for desktop` — container max width
- **layout.page-padding**: `inferred: 15px to 40px depending on viewport and section` — page horizontal padding
- **layout.section-gap**: `inferred: 40px+` — vertical spacing between sections
- **layout.header-height**: `inferred: ~80px desktop, ~80px mobile` — header height
- **layout.card-gutter**: `inferred: 20px` — grid gap for product cards
- **layout.page-max-width**: `inferred: ~1440px for desktop` — container-max-width
- **layout.page-padding**: `inferred: 15px to 40px depending on viewport and section` — page-horizontal-padding
- **layout.section-gap**: `inferred: 40px+` — vertical-spacing-between-sections
- **layout.header-height**: `inferred: ~80px desktop, ~80px mobile` — header-height
- **layout.card-gutter**: `inferred: 20px` — grid-gap-for-product-cards

### Build Notes

- When implementing navigation, ensure the mobile menu state is clearly defined and animated.
- For product grids, use a responsive grid system that adjusts the number of columns based on viewport size.
- Footer links should be clearly distinguishable from body text.

## Elevation & Depth

### Elevation

- **{shadows.shadow.0-0-0-1px-ebebeb}** (`0 0 0 1px #ebebeb`): box-shadow

- **{shadows.shadow.0-0-2px-1px-rgba-0-0-0-15}** (`0 0 2px 1px rgba(0,0,0,.15)`): box-shadow

- **{shadows.shadow.0-0-2px-1px-rgba-0-0-0-2}** (`0 0 2px 1px rgba(0,0,0,.2)`): box-shadow

- **{shadows.shadow.0-0-3px-1px-rgb-94-158-214}** (`0 0 3px 1px rgb(94,158,214)`): box-shadow

- **{shadows.shadow.0-0-5px-666}** (`0 0 5px #666`): box-shadow

- **{shadows.shadow.0-0-5px-rgba-0-0-0-0-1}** (`0 0 5px rgba(0, 0, 0, 0.1)`): box-shadow

- **{shadows.shadow.0-1px-0-rgba-0-0-0-0-05-inset-0-1px-0-rgba-255-255-255-0-8}** (`0 1px 0 rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.8)`): box-shadow

- **{shadows.shadow.none}** (`none`): box-shadow

### Borders

- **{borders.border.0}** (`0`): border

- **{borders.border.0-1px}** (`0 1px`): border-width

- **{borders.border.1px-solid-e5e5e5}** (`1px solid #e5e5e5`): border-bottom

- **{borders.border.1px-solid-ebebeb}** (`1px solid #ebebeb`): border-left

- **{borders.border.none}** (`none`): outline

- **{borders.border.solid-ebebeb}** (`solid #ebebeb`): border

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 | border-radius |
| {rounded.radius.3px} | 3px | border-radius |
| {rounded.radius.4px} | 4px | border-radius |
| {rounded.radius.5px} | 5px | border-radius |
| {rounded.radius.30px} | 30px | border-radius |
| {rounded.radius.50} | 50% | border-radius |

## Components

### Buildable Component Recipes
#### button-primary
- **Component:** button
- **Background:** #000
- **Text:** #FFF
- **Border:** 1px solid #000
- **Radius:** 50px

#### button-secondary
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** 1px solid #000
- **Radius:** 50px

#### navigation-link
- **Component:** link
- **Background:** transparent
- **Text:** #424242
- **Border:** none
- **Radius:** 0px

#### primary_button
- **Component:** Primary Button
- **Background:** rgb(0, 0, 0)
- **Text:** rgb(255, 255, 255)
- **Border:** 1px
- **Radius:** 50px
- **Padding:** 10px 10px
- **Typography:** Bell Gothic Std

#### button-primary
- **Component:** button
- **Background:** #000
- **Text:** #FFF
- **Border:** 1px solid #000
- **Radius:** 50px

#### button-secondary
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** 1px solid #000
- **Radius:** 50px

#### navigation-link
- **Component:** link
- **Background:** transparent
- **Text:** #424242
- **Border:** none
- **Radius:** 0px

### button-primary

The primary button uses a solid black (`#000`) background with white text, 50px border-radius for pill-shaped ends, and 1px black border. This creates high contrast and immediate visual weight—appropriate for cart actions, "Add to Bag," or account sign-in.

### button-secondary

The secondary button inverts the hierarchy: transparent background, black (`#000`) text, 1px black border, and the same 50px pill radius. This lower-prominence treatment is suited to "Learn More," "View Details," or alternative actions that shouldn't compete with the primary CTA.

### navigation-link

Navigation links are bare: transparent background, muted text (`#424242`), no border, 0px radius. They rely entirely on typography and hover states to signal interactivity, keeping the header minimal and uncluttered.

### Photography & Media

- **photography:** role=hero; aspect=variable; crop=fill_and_crop; masking=none; frame=none
- **video:** role=hero; aspect=1.565:1 (desktop); crop=fill_and_crop; masking=none; frame=none
- **hero-video:** role=immersive-introduction; aspect=inferred: 16:9 or similar; crop=inferred: center-focused; masking=none; frame=none
- **product-image:** role=product-showcase; aspect=inferred: square or portrait; crop=inferred: centered, showcasing product details; masking=none; frame=none

## Do's and Don'ts

### Do

- Adapt primary navigation to a stacked vertical layout with increased touch targets on mobile viewports (max-width: 767px) to ensure usability.
- Apply `#ebebeb` for subtle UI dividers and input field borders to maintain a clean aesthetic, reserving `#e5e5e5` for more prominent content boundaries—this distinction preserves hierarchy in the monochrome palette.
- Apply border-radius values consistently: 3px for form elements like dropdowns, 50px for pill-shaped buttons, 50% for circular decorative elements (e.g., radio button indicators).
- Emphasize high-quality product photography as the primary visual storytelling mechanism. Product imagery should be centered, editorial in style, and given ample whitespace—never cropped awkwardly or surrounded by busy UI chrome.
- Ensure all interactive elements (buttons, links) have a minimum touch target size of 44x44px on mobile viewports to meet accessibility and usability standards.
- Maintain generous whitespace around content blocks, especially for editorial text and product showcases. Padding should feel abundant, never cramped, to preserve the premium, breathable aesthetic.
- Implement button hover states with subtlety: a background shift from `#595959` to `#333` on primary buttons, or a border color change on secondary buttons, without introducing new colors or heavy shadows.

### Don't

- Do not introduce bright, saturated colors (e.g., vibrant reds, blues, or greens) or complex gradients. The brand's identity is anchored in monochrome restraint—any added color would undermine the editorial, gallery-like atmosphere.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | 1440px+ | Multi-column layout for product listings and content grids.; Horizontal navigation menu. |
| mobile | max-width: 767px | Main page shell padding shifts to 0px horizontal padding on the homepage, with content elements taking specific horizontal padding (e.g., 20px).; Primary navigation transforms from horizontal to stacked vertical links. |
| small-desktop | max-width: 1199px | X-large and XX-large content shells apply 40px horizontal padding. |
| tablet | max-width: 1023px | Footer column padding adjusts to 30px left/right.; Header logo margin-top is adjusted to 17px. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- explicit, site-wide max-width container: No single, explicit `max-width` property on a common 'container' class was found in the evidence, suggesting layout responsiveness might rely more on adaptive padding and flexible content rather than a fixed-width shell for all content. The `.shell` classes modify padding rather than explicit width.
- explicitly named spacing scales: While distinct spacing values are used, there is no evidence of a semantic naming convention (e.g., 'spacing-sm', 'spacing-md') beyond pixel values, potentially leading to inconsistent application.
- typography: No explicit definition found for 'display' or 'heading-xl' type styles.
- extraction_artifact: The 'font_family' value '"Magda", sans-serif' was applied to elements like '.header-inner', but no specific token for 'Magda' font family was created as per rubric.
- extraction_artifact: The evidence provides many specific pixel values for spacing but lacks higher-level, named spacing tokens, making it challenging to infer a clear spacing scale or design system principles for vertical/horizontal rhythm beyond directly observed values. This aligns with the 'token-rich but guidance-poor' quality risk.
- Some exact token values were not found in CSS/computed evidence.

## Agent Prompt Guide

Quick Color Reference:
- text: `#000`
- border: `#ebebeb`
- muted text: `#424242`
- primary action: `#595959`
- background: `#f6f8f6`

Quick Typography Reference:
- body: "Bell Gothic Std", "Arial", "Helvetica", sans-serif, 14px, 400, line-height 1.3
- ui: "Bell Gothic Std", "Arial", "Helvetica", sans-serif, 16px, 100, line-height 1.5
- headings: "Bell Gothic Std", "Arial", "Helvetica", sans-serif, 30px, normal, line-height 1.3

Implementation Rules:
- Adapt primary navigation to a stacked vertical layout with increased touch targets on mobile viewports (max-width: 767px) to ensure usability.
- Apply `#ebebeb` for subtle UI dividers and input field borders to maintain a clean aesthetic, reserving `#e5e5e5` for more prominent content boundaries—this distinction preserves hierarchy in the monochrome palette.
- Apply border-radius values consistently: 3px for form elements like dropdowns, 50px for pill-shaped buttons, 50% for circular decorative elements (e.g., radio button indicators).
- Emphasize high-quality product photography as the primary visual storytelling mechanism. Product imagery should be centered, editorial in style, and given ample whitespace—never cropped awkwardly or surrounded by busy UI chrome.
- Ensure all interactive elements (buttons, links) have a minimum touch target size of 44x44px on mobile viewports to meet accessibility and usability standards.

Example Component Prompts:
1. Create a Header section for Le Labo Fragrances using white background (`#FFF`), black text (`#000`), and `#ebebeb` border treatment. Logo should be left-aligned, navigation horizontal on desktop, with ~80px total height. Avoid adding unsupported decorative elements.
2. Create a button-primary component with `#000` background, white text, 50px border-radius, 1px black border, and 10px padding. Include a subtle hover state (background shifts to `#333`). Ensure focus-visible behavior for accessibility.
3. Create a product media block using hero photography: variable aspect ratio, fill-and-crop treatment, no masking or frame. Image should be centered with generous surrounding whitespace, never cropped awkwardly or overlaid with heavy UI chrome.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing, not a source to copy.
- Le Labo - reference for monochrome product restraint and terse commerce language.
- COS - reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-ink: #000;
  --color-border: #ebebeb;
  --color-text-muted: #424242;
  --color-action: #595959;
  --color-canvas: #f6f8f6;
  --color-surface: #ffffff;
  --font-body: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-ui: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-heading-md: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-display: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --radius-0: 0;
  --radius-30px: 30px;
  --radius-3px: 3px;
  --radius-4px: 4px;
  --radius-50: 50%;
  --radius-5px: 5px;
  --shadow-0-0-0-1px-ebebeb: 0 0 0 1px #ebebeb;
  --shadow-0-0-2px-1px-rgba-0-0-0-15: 0 0 2px 1px rgba(0,0,0,.15);
  --shadow-0-0-2px-1px-rgba-0-0-0-2: 0 0 2px 1px rgba(0,0,0,.2);
  --shadow-0-0-3px-1px-rgb-94-158-214: 0 0 3px 1px rgb(94,158,214);
  --shadow-0-0-5px-666: 0 0 5px #666;
  --shadow-0-0-5px-rgba-0-0-0-0-1: 0 0 5px rgba(0, 0, 0, 0.1);
  --shadow-0-1px-0-rgba-0-0-0-0-05-inset-0-1px-0-rgba-255-255-255-0-8: 0 1px 0 rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.8);
  --shadow-none: none;
  --layout-page-max-width: inferred: ~1440px for desktop;
  --layout-page-padding: inferred: 15px to 40px depending on viewport and section;
  --layout-section-gap: inferred: 40px+;
  --layout-header-height: inferred: ~80px desktop, ~80px mobile;
  --layout-card-gutter: inferred: 20px;
}
```

### Tailwind v4

```css
@theme {
  --color-ink: #000;
  --color-border: #ebebeb;
  --color-text-muted: #424242;
  --color-action: #595959;
  --color-canvas: #f6f8f6;
  --color-surface: #ffffff;
  --font-body: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-ui: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-heading-md: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --font-display: "Bell Gothic Std, Arial, Helvetica, sans-serif", Arial, Helvetica, sans-serif;
  --radius-0: 0;
  --radius-30px: 30px;
  --radius-3px: 3px;
  --radius-4px: 4px;
  --radius-50: 50%;
  --radius-5px: 5px;
  --shadow-0-0-0-1px-ebebeb: 0 0 0 1px #ebebeb;
  --shadow-0-0-2px-1px-rgba-0-0-0-15: 0 0 2px 1px rgba(0,0,0,.15);
  --shadow-0-0-2px-1px-rgba-0-0-0-2: 0 0 2px 1px rgba(0,0,0,.2);
  --shadow-0-0-3px-1px-rgb-94-158-214: 0 0 3px 1px rgb(94,158,214);
  --shadow-0-0-5px-666: 0 0 5px #666;
  --shadow-0-0-5px-rgba-0-0-0-0-1: 0 0 5px rgba(0, 0, 0, 0.1);
  --shadow-0-1px-0-rgba-0-0-0-0-05-inset-0-1px-0-rgba-255-255-255-0-8: 0 1px 0 rgba(0, 0, 0, 0.05), inset 0 1px 0 rgba(255, 255, 255, 0.8);
  --shadow-none: none;
  --layout-page-max-width: inferred: ~1440px for desktop;
  --layout-page-padding: inferred: 15px to 40px depending on viewport and section;
  --layout-section-gap: inferred: 40px+;
  --layout-header-height: inferred: ~80px desktop, ~80px mobile;
  --layout-card-gutter: inferred: 20px;
}
```
