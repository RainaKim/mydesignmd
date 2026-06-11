---
version: alpha
name: Supabase \\| The Postgres Development Platform.OpenAI logoHugging Face logo
description: Build production-grade applications with a Postgres database, Authentication, instant APIs, Realtime, Functions, Storage and Vector embeddings. Start for free.
colors:
  primary: "#030a0c"
  color.surface.dark: "#1c1c1c"
  color.gray-300: "#232323"
  color.gray-400: "#ededed"
  color.gray-500: "#2e2e2e"
  color.colors-gray-dark-alpha-800: "#ffffff40"
  color.surface: "#0000"
  color.ink.inverse: white
typography:
  font.body:
    fontFamily: Courier New,Courier,monospace
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  font.caption:
    fontFamily: Circular, sans-serif
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
  font.body.sm:
    fontFamily: Ubuntu,Droid Sans,-apple-system,BlinkMacSystemFont,Segoe WPC,Segoe UI,sans-serif
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.5
  font.ui:
    fontFamily: Circular, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
rounded:
  radius.25rem: .25rem
  radius.0: 0
  radius.3-40282e-38px: 3.40282e+38px
  radius.4px: 4px
  radius.6px: 6px
  radius.8px: 8px
shadows:
  shadow.0-0-4px-ffffff40: "0 0 4px #ffffff40"
  shadow.0-13px-27px-5px-rgba-50-50-93-25-0-8px-16px-8px-rgba-0-0-0-3-0-6px-16px-6px-rgba-0-0-0-025: 0 13px 27px -5px rgba(50,50,93,.25),0 8px 16px -8px rgba(0,0,0,.3),0 -6px 16px -6px rgba(0,0,0,.025)
  shadow.none: none
  shadow.var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)
  shadow.var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
  shadow.var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)
components:
  button-primary:
    backgroundColor: rgb(114, 227, 173)
    textColor: rgb(23, 23, 23)
    rounded: 6px
  button-secondary:
    backgroundColor: rgb(253, 253, 253)
    textColor: rgb(23, 23, 23)
    rounded: 6px
  navigation-link:
    backgroundColor: transparent
    textColor: rgb(23, 23, 23)
    rounded: 0px
  card:
    backgroundColor: rgb(255, 255, 255)
    textColor: rgb(23, 23, 23)
    rounded: 0px
  button:
    backgroundColor: transparent \| rgb(114, 227, 173)
    textColor: rgb(23, 23, 23) \| rgb(112, 112, 112)
    rounded: 6px
  feature-card:
    backgroundColor: rgb(255, 255, 255)
    textColor: rgb(23, 23, 23)
    rounded: 0px
  primary-button:
    backgroundColor: rgb(114, 227, 173)
    textColor: rgb(23, 23, 23)
    rounded: 6px
    padding: 4px 10px
    typography: Circular
  secondary-button:
    backgroundColor: rgb(253, 253, 253)
    textColor: rgb(23, 23, 23)
    rounded: 6px
    padding: 4px 10px
    typography: Circular
sectionMap:
  header:
    background: white
    text: dark
    border: none
    media: dark
    layout: balanced
  hero:
    background: white
    text: dark
    border: none
    media: dark
    layout: generous
  feature-grid:
    background: white
    text: dark
    border: none
    media: dark
    layout: balanced
  footer:
    background: rgb(0, 0, 0)
    text: rgb(255, 255, 255)
    border: N/A
    media: N/A
    layout: Standard footer layout
  header-nav:
    background: rgb(253, 253, 253)
    text: rgb(23, 23, 23)
    border: transparent
    media: N/A
    layout: Transparent background on hover/focus for links
  hero-feature-grids:
    background: rgb(255, 255, 255)
    text: rgb(23, 23, 23)
    border: rgb(212, 212, 212)
    media: Varies, often dark SVG illustrations
    layout: Generous padding
buildTokens:
  layout.spacing-base: 8px
  layout.radius-sm: 6px
  layout.font-size-base: 14px
  layout.font-size-heading: 16px
  layout.page-width-max: 1440px
  layout.grid-gap: 20px
  layout.section-padding-y: 96px
  layout.section-padding-x: 80px
  layout.nav-height: 65px
---

# Supabase \\| The Postgres Development Platform.OpenAI logoHugging Face logo — Style Reference
> Developer-first infrastructure tools presented with restrained precision and clarity

**Theme:** dark

## Overview

Supabase positions itself as the open-source alternative to Firebase, offering developers a complete Postgres-powered backend toolkit. The platform promises production-ready infrastructure—authentication, real-time subscriptions, storage, and serverless functions—deployable in minutes but scalable to millions of users.

The design system balances technical credibility with approachability: it must speak confidently to senior engineers evaluating database architecture while remaining accessible to developers shipping their first production app. Visual restraint reinforces the platform's core promise—no-nonsense tooling that handles complexity under the hood so developers can focus on building features.

**Voice:** headlines=direct_declarative; body=informative_technical_accessible; microcopy=functional_instructional; ctas=action_oriented_empowering

## Colors

### Color Philosophy

Surface colors establish atmospheric hierarchy before serving decorative purposes. The nearly-black `#030a0c` and charcoal `#1c1c1c` create depth without pure black, maintaining readability for extended technical documentation sessions. Foreground tokens remain role-specific—primary text (`#ededed`), inverse text (`white`), and placeholder states should never collapse into an undifferentiated gray scale.

### Token Roles
#### Surface
- **{colors.color.surface.dark}** (`#030a0c`): background.
- **{colors.color.surface.dark}** (`#1c1c1c`): background.
- **{colors.color.surface}** (`#0000`): background.
#### Hairlines & Borders
- **{colors.color.gray-300}** (`#232323`): border.
- **{colors.color.gray-500}** (`#2e2e2e`): border.
#### Semantic
- **{colors.color.colors-gray-dark-alpha-800}** (`#ffffff40`): depth.
#### Text
- **{colors.color.gray-400}** (`#ededed`): foreground.
- **{colors.color.ink.inverse}** (`white`): foreground.

## Typography

### Typography Principles

Typography functions as a system of distinct roles, not a universal font swap. Circular (sans-serif) carries UI labels and navigation. Courier New and Ubuntu handle code samples and technical specifications. Each typeface signals content type at a glance—developers scanning documentation should instantly differentiate product messaging from implementation details.

Type hierarchy reinforces voice: headlines adopt a declarative posture, utility labels remain neutral, and CTAs inject action-oriented momentum. Avoid collapsing these tonal registers into a single typographic treatment.

### Font Family

- **Circular, sans-serif**; fallbacks: sans-serif.

- **Circular, sans-serif**; fallbacks: sans-serif.

- **monospace**.

- **Courier New,Courier,monospace**; fallbacks: Courier; monospace.

- **Ubuntu,Droid Sans,-apple-system,BlinkMacSystemFont,Segoe WPC,Segoe UI,sans-serif**; fallbacks: Droid Sans; -apple-system; BlinkMacSystemFont; Segoe WPC; Segoe UI; sans-serif.

- **Circular, sans-serif**; fallbacks: sans-serif.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body} | 16px | 400 | 1.5 |  |  |
| {typography.font.caption} | 12px | 400 | 1.5 |  |  |
| {typography.font.body} | 1rem | 400 | 1.2rem |  |  |
| {typography.font.body} | 14px | 400 | 1.5 |  |  |
| {typography.font.body.sm} | 12px | 400 | 1.5 |  |  |
| {typography.font.ui} | 14px | 400 | 1.5 |  |  |

## Layout

### Composition Principles

Page composition follows a vertical stacking model: each section receives explicit treatment for surface color, text hierarchy, media style, and component behavior rather than inheriting from a single global container. This section-by-section approach allows feature grids to breathe with generous 96px vertical padding while header navigation remains compact at 65px height.

Content aligns left within a central column (maxing at 1440px on desktop), though CTAs and navigational clusters center-align for emphasis. Whitespace operates as a first-class design element—16px horizontal padding on mobile expands contextually on larger viewports, and 24px/96px vertical rhythms prevent visual crowding across documentation-heavy pages.

### Rhythm

Vertical rhythm relies on two core padding values: 24px for compact informational blocks and 96px for primary feature sections. Horizontal padding starts at 16px on mobile and scales with viewport width. This sparse, breathing layout prioritizes readability during extended technical reading sessions—developers should be able to scan API documentation without visual fatigue.

### Implementation Notes

Container widths max at 1440px for primary layout regions on desktop, then adapt fluidly to viewport width on smaller screens with centered horizontal padding. Column-based layouts within sections reflow to single-column vertical stacks below the mobile breakpoint. No named grid system is enforced; instead, individual sections define their own flexible column structures.

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Header | white | dark | none | dark | balanced |  |
| Hero | white | dark | none | dark | generous |  |
| Feature Grid | white | dark | none | dark | balanced |  |
| Footer | dark | light | none | light | balanced |  |
| Header/Nav | rgb(253, 253, 253) | rgb(23, 23, 23) | transparent | N/A | Transparent background on hover/focus for links |  |
| Hero/Feature Grids | rgb(255, 255, 255) | rgb(23, 23, 23) | rgb(212, 212, 212) | Varies, often dark SVG illustrations | Generous padding |  |
| Footer | rgb(0, 0, 0) | rgb(255, 255, 255) | N/A | N/A | Standard footer layout |  |
| header | white | dark | none | dark | balanced |  |
| hero | white | dark | none | dark | generous |  |
| feature-grid | white | dark | none | dark | balanced |  |
| footer | rgb(0, 0, 0) | rgb(255, 255, 255) | N/A | N/A | Standard footer layout |  |
| header-nav | rgb(253, 253, 253) | rgb(23, 23, 23) | transparent | N/A | Transparent background on hover/focus for links |  |

### Implementation Notes
- **layout.spacing-base**: `8px` — padding, margin
- **layout.radius-sm**: `6px` — border-radius
- **layout.font-size-base**: `14px` — typography
- **layout.font-size-heading**: `16px` — typography
- **layout.page-width-max**: `1440px` — max-container-width
- **layout.grid-gap**: `20px` — grid-gutter
- **layout.section-padding-y**: `96px` — section-padding
- **layout.section-padding-x**: `80px` — section-padding
- **layout.nav-height**: `65px` — navigation-height
- **layout.page-width-max**: `1440px` — max_container_width
### Build Notes
- All interactive elements must surface clear focus states for keyboard navigation—particularly critical in documentation-heavy interfaces where developers rely on tab-based browsing.
- Maintain absolute consistency in spacing and alignment across sections to reinforce the platform's infrastructure-grade reliability.
- Prioritize legibility and WCAG AA contrast compliance in all typography pairings, especially when rendering code samples on dark backgrounds.
- Navigation clusters collapse into a hamburger menu below 768px viewport width.
- Feature grids reflow from multi-column to single-column layouts below 768px, preserving vertical rhythm with consistent inter-card spacing.

## Elevation & Depth

### Elevation

- **{shadows.shadow.0-0-4px-ffffff40}** (`0 0 4px #ffffff40`):

- **{shadows.shadow.0-13px-27px-5px-rgba-50-50-93-25-0-8px-16px-8px-rgba-0-0-0-3-0-6px-16px-6px-rgba-0-0-0-025}** (`0 13px 27px -5px rgba(50,50,93,.25),0 8px 16px -8px rgba(0,0,0,.3),0 -6px 16px -6px rgba(0,0,0,.025)`):

- **{shadows.shadow.none}** (`none`):

- **{shadows.shadow.var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow}** (`var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,)`):

- **{shadows.shadow.var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow}** (`var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)`):

- **{shadows.shadow.var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow}** (`var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow)`):

### Borders

- **{borders.border.0}** (`0`):

- **{borders.border.1px}** (`1px`):

- **{borders.border.1px-solid}** (`1px solid`):

- **{borders.border.1px-solid-hsl-var-border-default}** (`1px solid hsl(var(--border-default))`):

- **{borders.border.2px-solid-0000}** (`2px solid #0000`):

- **{borders.border.none}** (`none`):

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 |  |
| {rounded.radius.4px} | 4px |  |
| {rounded.radius.6px} | 6px |  |
| {rounded.radius.8px} | 8px |  |
| {rounded.radius.25rem} | .25rem |  |
| {rounded.radius.3-40282e-38px} | 3.40282e+38px |  |

## Components

### Buildable Component Recipes
#### button-primary
- **Component:** button
- **Background:** rgb(114, 227, 173)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px solid oklab(0.685565 -0.144466 0.057858 / 0.75)
- **Radius:** 6px

#### button-secondary
- **Component:** button
- **Background:** rgb(253, 253, 253)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px solid rgb(212, 212, 212)
- **Radius:** 6px

#### navigation-link
- **Component:** link
- **Background:** transparent
- **Text:** rgb(23, 23, 23)
- **Border:** none
- **Radius:** 0px

#### card
- **Component:** card
- **Background:** rgb(255, 255, 255)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px solid rgb(223, 223, 223)
- **Radius:** 0px

#### Button
- **Component:** button
- **Background:** transparent \\| rgb(114, 227, 173)
- **Text:** rgb(23, 23, 23) \\| rgb(112, 112, 112)
- **Border:** transparent \\| 1px solid rgba(0,0,0,0.15)
- **Radius:** 6px

#### Feature Card
- **Component:** card
- **Background:** rgb(255, 255, 255)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px solid rgb(212, 212, 212)
- **Radius:** 0px

#### primary_button
- **Component:** Primary Button
- **Background:** rgb(114, 227, 173)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px
- **Radius:** 6px
- **Padding:** 4px 10px
- **Typography:** Circular

#### secondary_button
- **Component:** Secondary Button
- **Background:** rgb(253, 253, 253)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px
- **Radius:** 6px
- **Padding:** 4px 10px
- **Typography:** Circular

#### navigation-link
- **Component:** link
- **Background:** transparent
- **Text:** rgb(23, 23, 23)
- **Border:** none
- **Radius:** 0px

#### card
- **Component:** card
- **Background:** rgb(255, 255, 255)
- **Text:** rgb(23, 23, 23)
- **Border:** 1px solid rgb(223, 223, 223)
- **Radius:** 0px

### Button

Primary actions leverage the signature `rgb(114, 227, 173)` green paired with `rgb(23, 23, 23)` text and 6px border-radius. Secondary buttons use near-white `rgb(253, 253, 253)` backgrounds with matching radius. Both variants require distinct hover and active states—typically a subtle darkening or border emphasis—to provide immediate interaction feedback. Navigation links remain transparent with 0px radius, relying on text color shifts to signal interactivity.

### Card

Containers for feature descriptions and informational blocks use `rgb(255, 255, 255)` backgrounds with `rgb(23, 23, 23)` text. Borders appear at 1px solid in light gray tones (`rgb(212, 212, 212)` or `rgb(223, 223, 223)`) and corners remain sharp at 0px radius, reinforcing the functional aesthetic. Cards in feature grids receive 1px borders to define boundaries without relying on shadow elevation.

### Photography & Media

- **icon:** Serves feature identification; maintains 1:1 aspect ratio with no cropping, masking, or frame treatment.
- **illustration:** Primary product showcase assets presented in various aspect ratios (often 16:9 for feature visuals); rendered with contain crop behavior to preserve full artwork within bounds; no masking or decorative frames applied.
- **photography:** Supporting social proof and team imagery; aspect ratios vary by context; no masking or decorative frames; crop behavior avoids cutting key content.
- **illustration (product-feature-visual):** Aspect ratio inferred from container dimensions; typically dark-toned SVG illustrations that maintain readability against white backgrounds.

## Do's and Don'ts

### Do
- Apply Circular font family consistently across all UI elements, navigation, and body copy to maintain brand cohesion and readability.
- Deploy monospace families (Courier New, Office Code Pro) exclusively for code snippets, terminal outputs, and technical examples—never for marketing copy or UI labels.
- Ensure WCAG AA contrast compliance between foreground and background pairings; use `#ededed` for text on dark surfaces where specified.
- Reserve the `rgb(114, 227, 173)` green accent for interactive elements and strategic highlights—overuse dilutes its wayfinding power in dense technical interfaces.
- Maintain generous whitespace and sparse layouts to reduce cognitive load during extended documentation sessions.
- Provide explicit hover, focus, and active states for all interactive components, particularly in keyboard-navigable documentation interfaces.
- Preserve the section-by-section treatment model: each layout region should define its own surface color, text hierarchy, and component behavior rather than inheriting global defaults.
- Keep visual hierarchy crisp through typography and color contrast—primary actions and critical information must remain instantly scannable.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | 1280px and above | Primary navigation displays all links horizontally.; Content sections typically present multi-column layouts. |
| mobile | Up to 390px | Primary navigation collapses into a hamburger menu.; Multi-column layouts (e.g., feature grids) re-stack vertically to a single column. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- extraction_artifact: Source references are constrained by a 'raw_markdown' source_type requirement, despite evidence originating from CSS and runtime samples. Specific line numbers and section titles for CSS evidence are not available in the input pack, leading to placeholder values and generic source paths for references.
- Some exact token values were not found in CSS/computed evidence.

## Agent Prompt Guide

Quick Color Reference:
- background: `#030a0c`
- border: `#232323`
- text: `#ededed`
- inverse text: `white`

Quick Typography Reference:
- body: Circular, sans-serif, 16px, 400, line-height 1.5
- ui: Circular, sans-serif, 14px, 400, line-height 1.5

Implementation Rules:
- Provide distinct hover and active states for all buttons to ensure immediate interaction feedback.
- Use monospace font families (Courier New, Office Code Pro) exclusively for code snippets, terminal outputs, and technical examples—never for UI text or marketing copy.
- Ensure WCAG AA contrast compliance between foreground and background elements; apply `#ededed` for foreground text on dark backgrounds as specified.
- Apply Circular font family consistently to all UI elements, body copy, and navigation to maintain brand cohesion and readability.
- Reserve the `rgb(114, 227, 173)` green accent for interactive elements and strategic highlights—avoid overuse in dense informational interfaces.

Example Component Prompts:
1. Create a Header section using white background, dark text treatment, and balanced layout rhythm. Maintain 65px navigation height and ensure navigation links collapse into a hamburger menu below 768px viewport width.
2. Build a button-primary component with `rgb(114, 227, 173)` background, `rgb(23, 23, 23)` text, 6px border-radius, and 4px-10px padding. Include distinct hover state (subtle darkening or border emphasis) and focus-visible ring for keyboard navigation.
3. Construct a feature card using `rgb(255, 255, 255)` background, `rgb(23, 23, 23)` text, 1px solid `rgb(212, 212, 212)` border, and 0px border-radius. Preserve 1:1 aspect ratio for feature icons with no masking or decorative frames.

## Similar Brands

- Linear - reference for disciplined contrast ratios, restrained component palettes, and typographic hierarchy in technical product interfaces.
- Stripe - reference for polished implementation detail, clear product storytelling, and accessible documentation design patterns.
- Vercel - reference for developer-facing typographic systems, monochrome surface discipline, and functional aesthetic restraint.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-surface-dark: #030a0c;
  --color-gray-300: #232323;
  --color-gray-400: #ededed;
  --color-gray-500: #2e2e2e;
  --color-colors-gray-dark-alpha-800: #ffffff40;
  --color-surface: #0000;
  --color-ink-inverse: white;
  --font-body: "Circular, sans-serif", sans-serif;
  --font-caption: "Circular, sans-serif", sans-serif;
  --font-body-sm: "Ubuntu,Droid Sans,-apple-system,BlinkMacSystemFont,Segoe WPC,Segoe UI,sans-serif", "Droid Sans", -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", sans-serif;
  --font-ui: "Circular, sans-serif", sans-serif;
  --radius-25rem: .25rem;
  --radius-0: 0;
  --radius-3-40282e-38px: 3.40282e+38px;
  --radius-4px: 4px;
  --radius-6px: 6px;
  --radius-8px: 8px;
  --shadow-0-0-4px-ffffff40: 0 0 4px #ffffff40;
  --shadow-0-13px-27px-5px-rgba-50-50-93-25-0-8px-16px-8px-rgba-0-0-0-3-0-6px-16px-6px-rgba-0-0-0-025: 0 13px 27px -5px rgba(50,50,93,.25),0 8px 16px -8px rgba(0,0,0,.3),0 -6px 16px -6px rgba(0,0,0,.025);
  --shadow-none: none;
  --shadow-var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  --shadow-var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow);
  --shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow);
  --layout-spacing-base: 8px;
  --layout-radius-sm: 6px;
  --layout-font-size-base: 14px;
  --layout-font-size-heading: 16px;
  --layout-page-width-max: 1440px;
  --layout-grid-gap: 20px;
  --layout-section-padding-y: 96px;
  --layout-section-padding-x: 80px;
  --layout-nav-height: 65px;
}
```

### Tailwind v4

```css
@theme {
  --color-surface-dark: #030a0c;
  --color-gray-300: #232323;
  --color-gray-400: #ededed;
  --color-gray-500: #2e2e2e;
  --color-colors-gray-dark-alpha-800: #ffffff40;
  --color-surface: #0000;
  --color-ink-inverse: white;
  --font-body: "Circular, sans-serif", sans-serif;
  --font-caption: "Circular, sans-serif", sans-serif;
  --font-body-sm: "Ubuntu,Droid Sans,-apple-system,BlinkMacSystemFont,Segoe WPC,Segoe UI,sans-serif", "Droid Sans", -apple-system, BlinkMacSystemFont, "Segoe WPC", "Segoe UI", sans-serif;
  --font-ui: "Circular, sans-serif", sans-serif;
  --radius-25rem: .25rem;
  --radius-0: 0;
  --radius-3-40282e-38px: 3.40282e+38px;
  --radius-4px: 4px;
  --radius-6px: 6px;
  --radius-8px: 8px;
  --shadow-0-0-4px-ffffff40: 0 0 4px #ffffff40;
  --shadow-0-13px-27px-5px-rgba-50-50-93-25-0-8px-16px-8px-rgba-0-0-0-3-0-6px-16px-6px-rgba-0-0-0-025: 0 13px 27px -5px rgba(50,50,93,.25),0 8px 16px -8px rgba(0,0,0,.3),0 -6px 16px -6px rgba(0,0,0,.025);
  --shadow-none: none;
  --shadow-var-tw-blur-var-tw-brightness-var-tw-contrast-var-tw-grayscale-var-tw-hue-rotate-var-tw-invert-var-tw-saturate-var-tw-sepia-var-tw-drop-shadow: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  --shadow-var-tw-inset-shadow-var-tw-inset-ring-shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-inset-shadow),var(--tw-inset-ring-shadow),var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow);
  --shadow-var-tw-ring-offset-shadow-var-tw-ring-shadow-var-tw-shadow: var(--tw-ring-offset-shadow),var(--tw-ring-shadow),var(--tw-shadow);
  --layout-spacing-base: 8px;
  --layout-radius-sm: 6px;
  --layout-font-size-base: 14px;
  --layout-font-size-heading: 16px;
  --layout-page-width-max: 1440px;
  --layout-grid-gap: 20px;
  --layout-section-padding-y: 96px;
  --layout-section-padding-x: 80px;
  --layout-nav-height: 65px;
}
```
