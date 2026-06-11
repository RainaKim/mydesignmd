---
version: alpha
name: WHOOP \\| Unlock Human Performance & HealthspanWHOOP LogoWHOOP Logo
description: Optimize sleep, strain, and recovery with WHOOP, the most advanced fitness and health wearable. With personalized insights, improve performance, build healthier habits, and extend healthspan with continuous health monitoring.
colors:
  primary: "#fff"
  color.canvas: "#000"
  color.surface.dark: "#333"
  color.ink: "#999"
  color.focus-indicator-blue: "#2360c5"
  color.surface: "#f3f5f9"
  color.subtle-shadow-black-10: rgba(0,0,0,.1)
  color.ink.inverse: "#fff"
typography:
  font.body:
    fontFamily: ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace
    fontSize: 1rem
    fontWeight: 400
    lineHeight: 1.5rem
    role: Code snippets, monospace text
  font.ui:
    fontFamily: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji
    fontSize: 1.25rem
    fontWeight: 700
    lineHeight: 1.5rem
    role: Call to Action button text
  font.caption:
    fontFamily: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji
    fontSize: .75rem
    fontWeight: 400
    lineHeight: 1rem
    role: Smallest text, e.g., captions, timestamps, disclaimers
  font.display.md:
    fontFamily: Proxima Nova,sans-serif
    fontSize: 32px
    fontWeight: 700
    lineHeight: 110%
    role: Hero or prominent display heading
  font.heading.md:
    fontFamily: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji
    fontSize: 1.5rem
    fontWeight: 700
    lineHeight: 2rem
    role: Primary section heading
  font.heading.sm:
    fontFamily: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji
    fontSize: 1.25rem
    fontWeight: 600
    lineHeight: 1.75rem
    role: Secondary section heading or prominent sub-heading
rounded:
  radius.125rem: .125rem
  radius.375rem: .375rem
  radius.0: 0
  radius.1-875rem: 1.875rem
  radius.1rem: 1rem
  radius.2rem: 2rem
  radius.50: 50%
  radius.clamp-9375rem-1-41vw-6073943662rem-1-875rem: clamp(.9375rem,1.41vw + .6073943662rem,1.875rem)
components:
  primary-cta-button-dark-theme:
    backgroundColor: "#000"
    textColor: "#fff"
    rounded: 1rem
  secondary-button-light-theme:
    backgroundColor: transparent
    textColor: "#000"
    rounded: .5rem
  primary-button:
    backgroundColor: "#000"
    textColor: "#fff"
    rounded: 1rem
  secondary-button:
    backgroundColor: transparent
    textColor: "#000"
    rounded: .5rem
  icon-button:
    backgroundColor: transparent
    textColor: "#fff"
    rounded: 50%
sectionMap:
  page-background:
    background: "#000"
    text: "#fff"
    border: transparent
    media: auto
    layout: default
  module-wrapper-gray:
    background: "#f3f5f9"
    text: "#000"
    border: transparent
    media: auto
    layout: default
  footer:
    background: "#000"
    text: "#fff"
    border: transparent
    media: auto
    layout: default
buildTokens:
  layout.page-max-width: inferred
  layout.section-padding-vertical: 1.875rem
  layout.section-padding-horizontal: 1.25rem
  layout.grid-gap: 1.25rem
  layout.nav-height: inferred
  layout.footer-padding-bottom: 1.875rem
---

# WHOOP \\| Unlock Human Performance & HealthspanWHOOP LogoWHOOP Logo — Style Reference
> technical, clean, sophisticated, performance-oriented, data-driven

**Theme:** mixed

## Overview

WHOOP positions itself as a precision instrument for athletes, biohackers, and performance-minded individuals who treat their bodies as systems to optimize. The brand translates medical-grade sensor technology and computational analysis into actionable recovery and strain metrics, operating at the intersection of wearable hardware, biometric science, and behavior change.

The design system balances absolute black (#000) backgrounds with sharp white (#fff) type, creating the visual vocabulary of a diagnostic tool. This isn't aesthetic minimalism—it's functional clarity borrowed from medical devices and performance dashboards where contrast equals legibility and legibility equals safety.

**Voice:** headlines=authoritative, declarative, outcome-focused (e.g., "Unlock Human Performance"); body=data-informed, explanatory, rooted in physiological evidence; microcopy=terse, metric-specific, coaching-forward (e.g., "Recovery Score: 87%"); ctas=imperative, benefit-explicit, removing friction between insight and action (e.g., "Start Your Free Trial").

## Colors

### Color Philosophy

WHOOP's color system functions as environmental zoning rather than decorative palette. The #000 canvas establishes a default state—like a turned-off screen waiting for data—while #f3f5f9 gray modules provide contrast zones where forms, feature comparisons, or testimonials require visual separation from the primary canvas. This isn't "dark mode by default"; it's an intentional choice to make white text and colored data visualizations (when present) feel like transmitted information rather than printed matter.

Surface colors define contexts before they define objects. #000 signals the primary experience layer; #f3f5f9 signals utility, input, or secondary information; #333 appears on interactive surfaces in dark contexts. Color is restricted: the focus indicator blue (#2360c5) is the only consistent chromatic accent, reserved exclusively for keyboard navigation and active states—never decoration, never branding.

### Token Roles
#### Surface
- **{colors.color.canvas}** (`#000`): canvas_background. use for background.
- **{colors.color.surface.dark}** (`#333`): interactive_surface_dark. use for button_background.
- **{colors.color.surface}** (`#e5e5e5`): interactive_surface_light. use for button_background; input_background.
- **{colors.color.surface}** (`#f3f5f9`): surface_secondary. use for background; form_element_background; avoid primary_canvas_background.
#### Semantic
- **{colors.color.focus-indicator-blue}** (`#2360c5`): interactive_state_focus. use for outline; border; avoid background; primary_text.
- **{colors.color.subtle-shadow-black-10}** (`rgba(0,0,0,.1)`): shadow_default. use for box_shadow; avoid strong_elevation.
#### Text
- **{colors.color.ink}** (`#999`): text_disabled. use for text; icon; avoid primary_text; interactive_text.
#### Brand & Accent
- **{colors.color.ink.inverse}** (`#fff`): text_primary. use for foreground.

## Typography

### Typography Principles

WHOOP employs a three-family typographic system that separates display moments, interface utility, and technical specificity. Proxima Nova (32px, 700 weight, 110% line-height) appears exclusively in hero headings—its geometric proportions and slightly condensed letterforms convey precision without coldness. System UI sans-serif handles all navigation, body copy, CTAs, and data labels, ensuring instant rendering and maximum legibility across devices. The monospace stack (ui-monospace through Courier New fallbacks) is reserved for code snippets, API examples, or any context where character-width consistency matters—treating technical content as first-class, not afterthought.

Hierarchy is enforced through weight and size, not family swapping. A 700-weight 1.25rem CTA button sits visually distinct from a 600-weight 1.25rem subheading because weight alone shifts perceived importance. The .75rem caption size—used for timestamps, disclaimers, and metric footnotes—maintains 400 weight and 1rem line-height, ensuring legibility even at the smallest scale.

This isn't a brand font system; it's a performance-optimized hierarchy where every token serves a defined role in the information architecture.

### Font Family

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Call to Action button text.

- **ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace**; fallbacks: SFMono-Regular; Menlo; Monaco; Consolas; Liberation Mono; Courier New; monospace; role: Code snippets, monospace text.

- **Proxima Nova,sans-serif**; fallbacks: sans-serif; role: Hero or prominent display heading.

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Primary section heading.

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Secondary body text or descriptive labels.

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Secondary section heading or prominent sub-heading.

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Smallest text, e.g., captions, timestamps, disclaimers.

- **ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji**; fallbacks: system-ui; sans-serif; Apple Color Emoji; Segoe UI Emoji; Segoe UI Symbol; Noto Color Emoji; role: Standard body paragraph text.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.ui} | 1.25rem | 700 | 1.5rem |  | Call to Action button text |
| {typography.font.body} | 1rem | 400 | 1.5rem |  | Code snippets, monospace text |
| {typography.font.display.md} | 32px | 700 | 110% |  | Hero or prominent display heading |
| {typography.font.heading.md} | 1.5rem | 700 | 2rem |  | Primary section heading |
| {typography.font.ui} | .875rem | 400 | 1.25rem |  | Secondary body text or descriptive labels |
| {typography.font.heading.sm} | 1.25rem | 600 | 1.75rem |  | Secondary section heading or prominent sub-heading |
| {typography.font.caption} | .75rem | 400 | 1rem |  | Smallest text, e.g., captions, timestamps, disclaimers |
| {typography.font.body} | 1rem | 400 | 1.5rem |  | Standard body paragraph text |

### Principles

- **Call to Action button text**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `1.25rem`; weight `700`.

- **Code snippets, monospace text**: use `ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace`; size `1rem`; weight `400`.

- **Hero or prominent display heading**: use `Proxima Nova,sans-serif`; size `32px`; weight `700`.

- **Primary section heading**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `1.5rem`; weight `700`.

- **Secondary body text or descriptive labels**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `.875rem`; weight `400`.

- **Secondary section heading or prominent sub-heading**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `1.25rem`; weight `600`.

- **Smallest text, e.g., captions, timestamps, disclaimers**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `.75rem`; weight `400`.

- **Standard body paragraph text**: use `ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji`; size `1rem`; weight `400`.

## Layout

### Composition Principles

WHOOP's layout system treats sections as distinct environmental zones rather than stacked divs. Each section—whether page-background (#000), module-wrapper-gray (#f3f5f9), or footer (#000)—carries explicit surface treatment, determining not just background color but the contract for text color, media handling, and component behavior within that zone. This approach prevents "leakage" of dark-on-dark text or mismatched button styles across context boundaries.

Vertical rhythm follows a deliberate scale: 1.875rem establishes breathing room between major content blocks (section padding, footer padding-bottom), while 1.25rem defines grid gaps and horizontal section padding. Larger intervals—2.5rem on certain page sections, 3.125rem for prominent margin-bottom values—create intentional pauses in the scroll experience, separating hero moments from feature blocks or testimonials from CTAs. The smallest increment (.25rem) handles micro-spacing within components, maintaining precision at the pixel level.

The layout density sits between "balanced" and "generous." Fine-grained .25rem adjustments coexist with expansive 3.125rem section breaks, allowing dense data tables or form grids to sit comfortably alongside hero imagery with substantial margins. The clamp() function on footer column-gap (clamp(.9375rem, 1.41vw + .6073943662rem, 1.875rem)) reveals a fluid, viewport-responsive grid that contracts on mobile and expands on desktop without breakpoint jumps.

### Rhythm

Vertical rhythm operates on a multiplier system rooted in 1.875rem. Section padding, footer padding-bottom, and image margin-bottom all reference this base, creating a predictable cadence. Smaller increments (.625rem, 1rem, 1.25rem) subdivide this rhythm for internal component spacing—gap between grid items, padding within cards, margin-bottom on paragraph blocks. The py-10 utility (2.5rem vertical padding) appears on major page sections, signaling a tier-one content boundary.

Density varies by section type: the #000 page-background uses expansive vertical padding to let hero content breathe, while #f3f5f9 module-wrapper-gray sections apply tighter padding to accommodate form fields, comparison tables, or FAQ accordions. This isn't arbitrary—it's a functional response to content type, where data-heavy zones pack tighter and narrative zones expand.

### Implementation Notes

Grid behavior is implied through gap tokens (1rem, 1.25rem, 1.5rem, 2.5rem) and the fluid clamp() column-gap, but explicit grid-template-columns definitions remain outside the extracted tokens. This suggests either CSS Grid with auto-fit/auto-fill behavior or a component-level grid system where column counts vary by section. The presence of min-aspect-ratio: 1/1 media queries indicates layout adjustments for landscape orientations, likely affecting fullscreen modal padding (3.125rem horizontal and top padding) and image aspect ratios.

Alignment logic isn't globally prescribed. The section treatment map shows no forced center or left alignment—implying that alignment is component-specific or inherited from section-level layout definitions not captured in these tokens.

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Page Background | #000 | #fff | transparent | auto | default |  |
| Module Wrapper (Gray) | #f3f5f9 | #000 | transparent | auto | default |  |
| Footer | #000 | #fff | transparent | auto | default |  |
| page-background | #000 | #fff | transparent | auto | default |  |
| module-wrapper-gray | #f3f5f9 | #000 | transparent | auto | default |  |
| footer | #000 | #fff | transparent | auto | default |  |

### Implementation Notes
- **layout.page-max-width**: `inferred` — max-width
- **layout.section-padding-vertical**: `1.875rem` — padding
- **layout.section-padding-horizontal**: `1.25rem` — padding
- **layout.grid-gap**: `1.25rem` — grid-gap
- **layout.nav-height**: `inferred` — height
- **layout.footer-padding-bottom**: `1.875rem` — padding
### Build Notes

The clamp() function on footer column-gap (clamp(.9375rem, 1.41vw + .6073943662rem, 1.875rem)) must be tested across viewport widths to ensure the fluid calculation doesn't produce awkward mid-range values. Verify that the 1.41vw coefficient produces visually consistent gaps at common breakpoints (375px, 768px, 1024px, 1440px).

Button corner rounding must remain locked: 1rem for primary CTAs on #000 backgrounds, .5rem for secondary/ghost buttons, and 50% for icon-only buttons (likely nav menu toggles or social icons). Mixing these values breaks the visual contract between button priority and surface treatment.

## Elevation & Depth

No shadow or elevation system is evidenced.

### Borders

- **{borders.border.0625rem-solid-000}** (`.0625rem solid #000`): interactive_border

- **{borders.border.125rem-solid-2360c5}** (`.125rem solid #2360c5`): focus_outline

- **{borders.border.125rem-solid-31a2b1}** (`.125rem solid #31a2b1`): active_outline

- **{borders.border.125rem-solid-999}** (`.125rem solid #999`): input_border

- **{borders.border.1px-solid-e5e5e5}** (`1px solid #e5e5e5`): divider

- **{borders.border.1px-solid-var-module-text-color-rgba-0-0-0-2}** (`1px solid var(--module-text-color,rgba(0,0,0,.2))`): divider

- **{borders.border.2px-solid-transparent}** (`2px solid transparent`): default_outline

- **{borders.border.none}** (`none`): decorative_border

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 | corner_rounding |
| {rounded.radius.1rem} | 1rem | corner_rounding |
| {rounded.radius.1-875rem} | 1.875rem | corner_rounding |
| {rounded.radius.2rem} | 2rem | corner_rounding |
| {rounded.radius.125rem} | .125rem | corner_rounding |
| {rounded.radius.375rem} | .375rem | corner_rounding |
| {rounded.radius.50} | 50% | circular_shape |
| {rounded.radius.clamp-9375rem-1-41vw-6073943662rem-1-875rem} | clamp(.9375rem,1.41vw + .6073943662rem,1.875rem) | responsive_corner_rounding |

## Components

### Buildable Component Recipes
#### Primary CTA Button - Dark Theme
- **Component:** button
- **Background:** #000
- **Text:** #fff
- **Border:** none
- **Radius:** 1rem

#### Secondary Button - Light Theme
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** .063rem solid #000
- **Radius:** .5rem

#### Primary Button
- **Component:** button
- **Background:** #000
- **Text:** #fff
- **Border:** transparent
- **Radius:** 1rem

#### Secondary Button
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** #2360c5
- **Radius:** .5rem

#### Icon Button
- **Component:** button
- **Background:** transparent
- **Text:** #fff
- **Border:** transparent
- **Radius:** 50%

#### Primary CTA Button - Dark Theme
- **Component:** button
- **Background:** #000
- **Text:** #fff
- **Border:** none
- **Radius:** 1rem

#### Secondary Button - Light Theme
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** .063rem solid #000
- **Radius:** .5rem

#### Primary Button
- **Component:** button
- **Background:** #000
- **Text:** #fff
- **Border:** transparent
- **Radius:** 1rem

#### Secondary Button
- **Component:** button
- **Background:** transparent
- **Text:** #000
- **Border:** #2360c5
- **Radius:** .5rem

#### Icon Button
- **Component:** button
- **Background:** transparent
- **Text:** #fff
- **Border:** transparent
- **Radius:** 50%

### Button

WHOOP's button system operates on contextual inversion: primary CTAs use #000 fill with #fff text on light backgrounds, while secondary buttons remain transparent with .063rem solid #000 borders and #000 text. On dark (#000) page backgrounds, the primary CTA inverts to maintain contrast. Icon buttons—likely hamburger menus, close icons, or social links—use 50% border-radius (perfect circles) with transparent backgrounds and #fff text, relying on the icon glyph itself for recognition.

The 1rem radius on primary CTAs creates a distinctly rounded pill shape at typical button widths (e.g., "Start Free Trial"), while the .5rem radius on secondary buttons produces subtle corner softening that distinguishes them from sharp-cornered form inputs. Focus states apply the #2360c5 blue outline (.125rem solid), never filled backgrounds—ensuring accessibility without disrupting the monochrome palette.

### Photography & Media

- **photography:** role=hero; aspect=0.78:1 (portrait); crop=subject_focused; masking=none; frame=none
- **photography:** role=hero; aspect=inferred; crop=object-fit: cover; masking=none; frame=none
- **product-imagery:** role=feature-illustration; aspect=inferred; crop=contain; masking=none; frame=none
- **photography:** role=hero; aspect=0.78:1; crop=subject_focused; masking=none; frame=none

## Do's and Don'ts

### Do

- Use Proxima Nova exclusively for hero display headings (32px, 700 weight, 110% line-height). Reserve system UI sans-serif for all other type roles—headings, body, labels, captions—to maintain the intended hierarchy where display moments are typographically distinct but interface text remains universal and fast-rendering.
- Maintain 44×44 CSS pixel minimum touch targets for all interactive elements (buttons, links, form controls, icon buttons) to meet WCAG 2.5.5 Level AAA and ensure thumb-friendly interaction on mobile devices.
- Pair #000 backgrounds exclusively with #fff foreground text and interactive elements. Pair #f3f5f9 backgrounds exclusively with #000 foreground text. Never reverse this relationship—the high-contrast pairings are load-bearing for legibility and brand recognition.
- Apply border-radius values according to component category: 1rem for primary CTA buttons, .5rem for secondary/ghost buttons, .375rem or 1.875rem for content cards and image containers, and 50% for icon-only circular buttons. Do not interpolate or average these values.
- Use 1.875rem as the foundational vertical spacing unit between major page sections (section-padding-vertical, footer-padding-bottom). Use 1.25rem for grid gaps and horizontal section padding. Use 2.5rem (py-10) for tier-one section boundaries. Use .25rem for micro-spacing within components.
- Apply #2360c5 as the focus outline color (.125rem solid) for all interactive elements during keyboard navigation. This is the only chromatic accent in the system and must never be used for decorative purposes, backgrounds, or non-interactive visual elements.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- | --- |
| Desktop | min-width: 1024px | Horizontal padding (padding-left and padding-right) is set to 2.5rem (lg:px-10), indicating wider margins for content on larger screens. |
| Large Desktop | min-width: 1536px |  |
| Mobile | width <= 768px |  |
| Wide Aspect Ratio / Landscape | min-aspect-ratio: 1/1 | Fullscreen overlay modals adjust padding, with 3.125rem applied to both horizontal and top padding, providing more space on wider screens. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- Explicit Grid Column Definition: While `gap` properties suggest a grid system, explicit `grid-template-columns` or similar properties defining the specific column structure for the main page layout were not observed in the provided CSS tokens. This implies flexibility or reliance on implicit grid behavior or definitions outside of the extracted tokens.
- Font licensing (ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji): system
- Font licensing (ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace): system
- Font licensing (Proxima Nova,sans-serif): inferred

## Agent Prompt Guide

Quick Color Reference:
- background: `#000`
- text: `#999`
- inverse text: `#fff`

Quick Typography Reference:
- body: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji, 1rem, 400, line-height 1.5rem
- ui: ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji, .875rem, 400, line-height 1.25rem
- headings: Proxima Nova,sans-serif, 32px, 700, line-height 110%

Implementation Rules:
- Use Proxima Nova exclusively for hero display headings (32px, 700 weight, 110% line-height). Reserve system UI sans-serif for all other type roles—headings, body, labels, captions—to maintain the intended hierarchy where display moments are typographically distinct but interface text remains universal and fast-rendering.
- Maintain 44×44 CSS pixel minimum touch targets for all interactive elements (buttons, links, form controls, icon buttons) to meet WCAG 2.5.5 Level AAA and ensure thumb-friendly interaction on mobile devices.
- Pair #000 backgrounds exclusively with #fff foreground text and interactive elements. Pair #f3f5f9 backgrounds exclusively with #000 foreground text. Never reverse this relationship—the high-contrast pairings are load-bearing for legibility and brand recognition.
- Apply border-radius values according to component category: 1rem for primary CTA buttons, .5rem for secondary/ghost buttons, .375rem or 1.875rem for content cards and image containers, and 50% for icon-only circular buttons. Do not interpolate or average these values.
- Use 1.875rem as the foundational vertical spacing unit between major page sections (section-padding-vertical, footer-padding-bottom). Use 1.25rem for grid gaps and horizontal section padding. Use 2.5rem (py-10) for tier-one section boundaries. Use .25rem for micro-spacing within components.

Example Component Prompts:
1. Create a Page Background section for WHOOP using #000 background, #fff text, 1.875rem vertical padding, and 1.25rem horizontal padding. Use Proxima Nova 32px/700 for the hero heading and system UI sans-serif 1rem/400 for body copy. Maintain the documented section treatment and avoid adding decorative elements not evidenced in the system.
2. Create a Primary CTA Button using #000 background, #fff text (system UI sans-serif 1.25rem/700), 1rem border-radius, and #2360c5 .125rem solid focus outline. Include hover and focus-visible states. Do not add shadows or transitions unless evidenced.
3. Create a hero media block using photography with 0.78:1 aspect ratio, object-fit: cover crop, no masking, and no frame. Ensure the image sits cleanly against the #000 page background without borders or shadows.

## Similar Brands

- Linear — reference for restrained contrast, precise product UI, and monochrome-first interface discipline where color appears only for semantic states.
- Stripe — reference for documentation clarity, structured component systems, and polished implementation detail that scales from marketing to product.
- Vercel — reference for developer-facing typographic hierarchy, high-contrast monochrome palettes, and performance-optimized system fonts.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-canvas: #000;
  --color-surface-dark: #333;
  --color-ink: #999;
  --color-focus-indicator-blue: #2360c5;
  --color-surface: #e5e5e5;
  --color-subtle-shadow-black-10: rgba(0,0,0,.1);
  --color-ink-inverse: #fff;
  --font-body: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-ui: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-caption: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-display-md: "Proxima Nova,sans-serif", sans-serif;
  --font-heading-md: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-heading-sm: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --radius-125rem: .125rem;
  --radius-375rem: .375rem;
  --radius-0: 0;
  --radius-1-875rem: 1.875rem;
  --radius-1rem: 1rem;
  --radius-2rem: 2rem;
  --radius-50: 50%;
  --radius-clamp-9375rem-1-41vw-6073943662rem-1-875rem: clamp(.9375rem,1.41vw + .6073943662rem,1.875rem);
  --layout-page-max-width: inferred;
  --layout-section-padding-vertical: 1.875rem;
  --layout-section-padding-horizontal: 1.25rem;
  --layout-grid-gap: 1.25rem;
  --layout-nav-height: inferred;
  --layout-footer-padding-bottom: 1.875rem;
}
```

### Tailwind v4

```css
@theme {
  --color-canvas: #000;
  --color-surface-dark: #333;
  --color-ink: #999;
  --color-focus-indicator-blue: #2360c5;
  --color-surface: #e5e5e5;
  --color-subtle-shadow-black-10: rgba(0,0,0,.1);
  --color-ink-inverse: #fff;
  --font-body: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-ui: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-caption: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-display-md: "Proxima Nova,sans-serif", sans-serif;
  --font-heading-md: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --font-heading-sm: "ui-sans-serif,system-ui,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji", system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --radius-125rem: .125rem;
  --radius-375rem: .375rem;
  --radius-0: 0;
  --radius-1-875rem: 1.875rem;
  --radius-1rem: 1rem;
  --radius-2rem: 2rem;
  --radius-50: 50%;
  --radius-clamp-9375rem-1-41vw-6073943662rem-1-875rem: clamp(.9375rem,1.41vw + .6073943662rem,1.875rem);
  --layout-page-max-width: inferred;
  --layout-section-padding-vertical: 1.875rem;
  --layout-section-padding-horizontal: 1.25rem;
  --layout-grid-gap: 1.25rem;
  --layout-nav-height: inferred;
  --layout-footer-padding-bottom: 1.875rem;
}
```
