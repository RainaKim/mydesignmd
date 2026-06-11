---
version: alpha
name: Home \ Anthropic
description: Anthropic is an AI safety and research company that's working to build reliable, interpretable, and steerable AI systems.
colors:
  primary: "#3898ec"
  color.surface: "#fff"
  color.ink: "#333"
  color.border: "#ccc"
  color.surface.dark: "#222"
  color.action: "#3898ec"
  color.transparent-black-0-05: "#00000005"
  color.transparent-black-0-10: "#0000000a"
typography:
  font.body.lg:
    fontFamily: Anthropic Serif, sans-serif
    fontSize: 18px
    fontWeight: 400
    lineHeight: 20px
    role: Body copy
  font.caption:
    fontFamily: Anthropic Sans, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    role: Caption or meta text
  font.ui:
    fontFamily: Anthropic Sans, sans-serif
    fontSize: .9375rem
    fontWeight: 600
    lineHeight: 1.2
    role: Button text
  font.display.xl:
    fontFamily: Anthropic Sans, sans-serif
    fontSize: 60.8653px
    fontWeight: 300
    role: Secondary display headline
  font.heading.lg:
    fontFamily: Anthropic Sans, sans-serif
    fontSize: 40.2939px
    fontWeight: 300
    role: Major section heading
  font.heading.md:
    fontFamily: Anthropic Serif, sans-serif
    fontSize: 24px
    fontWeight: 700
    lineHeight: 18px
    role: Section heading
  font.heading.sm:
    fontFamily: Anthropic Serif, sans-serif
    fontSize: 20px
    fontWeight: 400
    lineHeight: 20px
    role: Sub-heading
rounded:
  radius.round: 100vw
  radius.0: 0
  radius.1-5rem: 1.5rem
  radius.100: 100%
  radius.100rem: 100rem
  radius.2px: 2px
  radius.3px: 3px
  radius.50: 50%
shadows:
  shadow.0-0-0000-0-0-0000-0-0-0000: "0 0 #0000,0 0 #0000,0 0 #0000"
  shadow.0-0-0-1px-0000001a-0-1px-3px-0000001a: "0 0 0 1px #0000001a,0 1px 3px #0000001a"
  shadow.0-0-0-2px-fff: "0 0 0 2px #fff"
  shadow.0-0-3px-1px-3898ec: "0 0 3px 1px #3898ec"
  shadow.0-2px-2px-00000003-0-4px-4px-00000005-0-16px-24px-0000000a: "0 2px 2px #00000003,0 4px 4px #00000005,0 16px 24px #0000000a"
  shadow.0-4px-3px-00000005-0-10px-8px-00000008-0-19px-15px-0000000a-0-34px-27px-0000000a-0-63px-50px-0000000d-0-150px-120px-00000012: "0 4px 3px #00000005,0 10px 8px #00000008,0 19px 15px #0000000a,0 34px 27px #0000000a,0 63px 50px #0000000d,0 150px 120px #00000012"
  shadow.none: none
  shadow.unset: unset
components:
  navigation-link:
    backgroundColor: transparent
    textColor: "#141413"
    rounded: 0px
  primary-button:
    backgroundColor: "#3898ec"
    textColor: "#fff"
    rounded: 0px
  card:
    backgroundColor: "#f0ede2"
    textColor: "#141413"
    rounded: 0px
sectionMap:
  header-navigation:
    background: "#f0ede2"
    text: "#141413"
    border: inferred
    media: inferred
    layout: inferred
  hero:
    background: "#f0ede2"
    text: "#141413"
    border: inferred
    media: inferred
    layout: inferred
  content-blocks-e-g-products-solutions-resources:
    background: "#141413"
    text: "#f0ede2"
    border: inferred
    media: inferred
    layout: inferred
  footer:
    background: "#141413"
    text: "#f0ede2"
    border: inferred
    media: inferred
    layout: inferred
buildTokens:
  layout.page-max-width: 1440px
  layout.nav-height: 4.375rem
  layout.section-padding-vertical: inferred
  layout.section-padding-horizontal: inferred
  layout.grid-gap: inferred
  layout.card-padding: 31.4776px
---

# Home \ Anthropic — Style Reference
> scholarly restraint, typographic precision, high-contrast sections, unembellished interaction

**Theme:** mixed

## Overview

Anthropic positions itself at the intersection of frontier AI research and safety engineering. The visual language reflects this duality: warm, neutral backgrounds (#f0ede2, #fff) signal accessibility and openness, while inverted dark sections (#141413) anchor technical content and footer information. The design conveys intellectual rigor without academic stuffiness—typography does the expressive work, not decoration.

The tension here is between pioneering ambition in AI development and deep responsibility for long-term safety outcomes. The interface must feel both forward-looking and grounded, ambitious yet considered. Color inversions, typographic hierarchy, and deliberate white space manage this balance without resorting to futuristic tropes or heavy ornamentation.

**Voice:** headlines=measured, authoritative, clear; body=informative, thoughtful, precise; microcopy=functional, clear, helpful; ctas=direct, clear, slightly formal

## Colors

### Color Philosophy

Anthropic's palette is fundamentally about surface and text, not accent-driven branding. The warm off-white (#f0ede2) and pure white (#fff) establish a readable, scholarly canvas. Dark backgrounds (#141413, #222) create high-contrast zones for footer content and inverted sections, reinforcing information hierarchy without relying on decorative color blocking.

The accent blue (#3898ec) appears sparingly—on primary CTAs and focus states—ensuring it retains its signal value. Transparent blacks (#00000005, #0000000a) provide subtle layering for cards and elevation without introducing chromatic noise. Borders use a neutral gray (#ccc) that recedes visually, maintaining clean separation without hard lines.

This is not a vibrant, gradient-heavy brand palette. It's a typographic system supported by a carefully restrained color logic where background, text, and accent roles remain distinct and legible.

### Token Roles
#### Brand & Accent
- **{colors.color.action}** (`#3898ec`): accent.
#### Surface
- **{colors.color.surface}** (`#0000`): background.
- **{colors.color.surface.dark}** (`#222`): background.
- **{colors.color.surface}** (`rgb(250, 249, 245)`): background.
- **{colors.color.surface}** (`#ddd`): background.
- **{colors.color.surface}** (`#fff`): background.
#### Hairlines & Borders
- **{colors.color.border}** (`#ccc`): border.
#### Semantic
- **{colors.color.transparent-black-0-05}** (`#00000005`): depth.
- **{colors.color.transparent-black-0-10}** (`#0000000a`): depth.
#### Text
- **{colors.color.ink}** (`rgb(20, 20, 19)`): foreground.
- **{colors.color.ink}** (`rgb(176, 174, 165)`): foreground.
- **{colors.color.ink}** (`#141413`): foreground.
- **{colors.color.ink}** (`#333`): foreground.

## Typography

### Typography Principles

Anthropic uses a dual-family system where **Anthropic Serif** anchors body copy, section headings, and primary display moments, while **Anthropic Sans** handles UI controls, captions, and secondary display text. This creates a visual rhythm that distinguishes content hierarchy from functional interface elements.

The Serif family appears at 90.7755px for hero headlines, 24px for section headings, and 18px/20px for body text—each weight and size calibrated to its role. The Sans family takes over for lighter-weight display type (60.8653px, 40.2939px) and compact UI labels (.9375rem at 600 weight). This deliberate split prevents the expressive Serif from bleeding into dense controls, where legibility and neutrality are paramount.

Line heights remain tight for headings (24px headings render at 18px line-height; 20px subheads hold a 20px rhythm) while body text at 18px/20px maintains reading comfort. The consistent 300 weight across display and heading scales reinforces a scholarly, understated tone—no heavy black weights or condensed urgency, just measured authority.

### Font Family

- **Anthropic Serif, sans-serif**; role: Body copy.

- **Anthropic Sans, sans-serif**; role: Button text.

- **Anthropic Sans, sans-serif**; role: Caption or meta text.

- **Anthropic Serif, sans-serif**; role: Hero / primary display headline.

- **Anthropic Sans, sans-serif**; role: Major section heading.

- **Anthropic Sans, sans-serif**; role: Secondary display headline.

- **Anthropic Serif, sans-serif**; role: Section heading.

- **Anthropic Serif, sans-serif**; role: Sub-heading.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.body.lg} | 18px | 400 | 20px |  | Body copy |
| {typography.font.ui} | .9375rem | 600 | 1.2 |  | Button text |
| {typography.font.caption} | 14px | 400 | 20px |  | Caption or meta text |
| {typography.font.display.xl} | 90.7755px | 300 |  |  | Hero / primary display headline |
| {typography.font.heading.lg} | 40.2939px | 300 |  |  | Major section heading |
| {typography.font.display.xl} | 60.8653px | 300 |  |  | Secondary display headline |
| {typography.font.heading.md} | 24px | 700 | 18px |  | Section heading |
| {typography.font.heading.sm} | 20px | 400 | 20px |  | Sub-heading |

## Layout

### Composition Principles

Anthropic's layouts are built from named, high-contrast sections rather than a single continuous scroll. The header and hero sit on warm off-white (#f0ede2), content blocks invert to dark backgrounds (#141413) with light text (#f0ede2), and the footer repeats the dark treatment. This creates visual chapters that guide the eye through informational zones without requiring decorative dividers.

Each section carries explicit surface, text, and media treatment—pages are not generic containers but composed environments where background color, typography, and content align to a single purpose. White space is generous but not excessive; the 1440px max-width container and 4.375rem nav height establish proportional constraints that prevent sprawl.

The design avoids complex grid acrobatics in favor of readable, article-like layouts with prominent headings and clear type hierarchy. Cards use 31.4776px padding and minimal rounding (0px on most components), reinforcing the straightforward, unembellished aesthetic.

### Rhythm
- inferred
- inferred
- balanced layout
### Implementation Notes
- inferred
- inferred

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Header/Navigation | #f0ede2 | #141413 | inferred | inferred | inferred |  |
| Hero | #f0ede2 | #141413 | inferred | inferred | inferred |  |
| Content Blocks (e.g., Products, Solutions, Resources) | #141413 | #f0ede2 | inferred | inferred | inferred |  |
| Footer | #141413 | #f0ede2 | inferred | inferred | inferred |  |

### Implementation Notes
- **layout.page-max-width**: `1440px` — overall container width
- **layout.nav-height**: `4.375rem` — navigation bar height
- **layout.section-padding-vertical**: `inferred` — vertical padding for main content sections
- **layout.section-padding-horizontal**: `inferred` — horizontal padding for main content sections
- **layout.grid-gap**: `inferred` — gap between grid items
- **layout.card-padding**: `31.4776px` — padding within content cards
### Build Notes
- Ensure navigation items correctly transition to a mobile hamburger menu.
- Implement responsive scaling for typography to maintain readability across all breakpoints.

## Elevation & Depth

### Elevation

- **{shadows.shadow.0-0-0000-0-0-0000-0-0-0000}** (`0 0 #0000,0 0 #0000,0 0 #0000`):

- **{shadows.shadow.0-0-0-1px-0000001a-0-1px-3px-0000001a}** (`0 0 0 1px #0000001a,0 1px 3px #0000001a`):

- **{shadows.shadow.0-0-0-2px-fff}** (`0 0 0 2px #fff`):

- **{shadows.shadow.0-0-3px-1px-3898ec}** (`0 0 3px 1px #3898ec`):

- **{shadows.shadow.0-2px-2px-00000003-0-4px-4px-00000005-0-16px-24px-0000000a}** (`0 2px 2px #00000003,0 4px 4px #00000005,0 16px 24px #0000000a`):

- **{shadows.shadow.0-4px-3px-00000005-0-10px-8px-00000008-0-19px-15px-0000000a-0-34px-27px-0000000a-0-63px-50px-0000000d-0-150px-120px-00000012}** (`0 4px 3px #00000005,0 10px 8px #00000008,0 19px 15px #0000000a,0 34px 27px #0000000a,0 63px 50px #0000000d,0 150px 120px #00000012`):

- **{shadows.shadow.none}** (`none`):

- **{shadows.shadow.unset}** (`unset`):

### Borders

- **{borders.border.0}** (`0`):

- **{borders.border.1px-solid-ccc}** (`1px solid #ccc`):

- **{borders.border.1px-solid-var-color-theme-border-hover}** (`1px solid var(--_color-theme---border-hover)`):

- **{borders.border.4px}** (`4px`):

- **{borders.border.4px-solid-transparent}** (`4px solid transparent`):

- **{borders.border.5px}** (`5px`):

- **{borders.border.none}** (`none`):

- **{borders.border.var-border-width-main-solid-var-color-theme-border}** (`var(--border-width--main)solid var(--_color-theme---border)`):

No motion or transition system is evidenced.

## Shapes

### Border Radius Scale

| Token | Value | Use |
| --- | --- | --- |
| {rounded.radius.0} | 0 |  |
| {rounded.radius.2px} | 2px |  |
| {rounded.radius.3px} | 3px |  |
| {rounded.radius.1-5rem} | 1.5rem |  |
| {rounded.radius.100rem} | 100rem |  |
| {rounded.radius.round} | 100vw |  |
| {rounded.radius.100} | 100% |  |
| {rounded.radius.50} | 50% |  |

## Components

### Buildable Component Recipes
#### navigation-link
- **Component:** link
- **Background:** transparent
- **Text:** #141413
- **Border:** none
- **Radius:** 0px

**Implementation guidance:**
- Navigation links sit flush against the warm off-white header background (#f0ede2) with no rounding, no background fill, and dark text (#141413). This creates a high-contrast, text-forward navigation that relies on typographic clarity rather than button-like affordances.
- Hover and focus states should introduce the accent blue (#3898ec) as an underline or text color shift, maintaining the minimal, scholarly tone without adding heavy button chrome.

#### primary-button
- **Component:** button
- **Background:** #3898ec
- **Text:** #fff
- **Border:** none
- **Radius:** 0px

**Implementation guidance:**
- Primary CTAs use the accent blue (#3898ec) with white text and zero border radius, creating sharp, unambiguous action targets. The absence of rounding reinforces the restrained, no-nonsense interaction model.
- Typography should match the .9375rem UI token at 600 weight for legibility and visual authority. Focus states can use the 0 0 3px 1px #3898ec shadow to maintain accessibility without introducing soft, rounded glows.

#### card
- **Component:** card
- **Background:** #f0ede2
- **Text:** #141413
- **Border:** none
- **Radius:** 0px

**Implementation guidance:**
- Cards inherit the warm off-white background (#f0ede2) and dark text (#141413), maintaining the page's scholarly, readable baseline. The 31.4776px padding provides breathing room without excessive ornament.
- Cards should rely on subtle shadows (e.g., 0 2px 2px #00000003, 0 4px 4px #00000005) for layering rather than heavy borders or colored backgrounds. This keeps the focus on content hierarchy and typography.

### Photography & Media
- **photography:** role=inferred; aspect=inferred; crop=inferred; masking=none; frame=none

## Do's and Don'ts

### Do
- Always use Anthropic Serif for primary display headings and Anthropic Sans for secondary display headings.
- Apply the primary accent color (`#3898ec`) to all primary calls-to-action for consistent brand recognition.
- Ensure all text has a minimum contrast ratio of 4.5:1 against its background for accessibility.
- Implement a standard hamburger menu pattern for navigation on mobile viewports.
- Maintain a clear typographic hierarchy using Anthropic's branded fonts, ensuring readability across all text scales.
- Maintain a consistent font weight of 300 for display and heading elements.
- Maintain a light canvas primarily using white and off-white tones (e.g., #fff, #f0ede6) for primary content areas. Use dark colors (#141413, #000) strategically for background elements in footers or specific sections.
- Maintain consistent horizontal padding for content sections across all breakpoints.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| desktop | >=768px | Navigation is horizontally displayed in the header. |
| mobile | <768px | Navigation is collapsed into a hamburger menu in the header. |

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- letter_spacing: No explicit letter spacing values were found for any text tokens. This may indicate a default browser behavior or a lack of specific typographic design for this property.
- extraction_artifact: The `corpus_rubric_notes` were included in the output, violating the instruction to only generate JSON matching the DesignDocFragment schema.
- extraction_artifact: Line height for 'h3' (mapped to heading-medium) is '24px', but the specimen text 'Latest releases' is 24px. This could indicate a typographic issue or a need for adjustment to match visual design intent.
- extraction_artifact: The font weight for 'h5' (mapped to heading-small) is declared as '700' in the CSS, but the corresponding specimen text 'Commitments' has a computed font size of 20px, typically associated with a lighter weight. The actual rendered weight should be verified.
- extraction_artifact: The font-family 'Tiempos Text' is used for elements with sizes that suggest it might be a display font, but 'Anthropic Serif' is also used for display text. Further investigation is needed to confirm the intended usage and hierarchy between these fonts.

## Agent Prompt Guide

Quick Color Reference:
- background: `#0000`
- text: `rgb(20, 20, 19)`
- border: `#ccc`
- primary action: `#3898ec`

Quick Typography Reference:
- body: Anthropic Serif, sans-serif, 18px, 400, line-height 20px
- ui: Anthropic Sans, sans-serif, .9375rem, 600, line-height 1.2
- headings: Anthropic Serif, sans-serif, 90.7755px, 300

Implementation Rules:
- Always use Anthropic Serif for primary display headings and Anthropic Sans for secondary display headings.
- Apply the primary accent color (`#3898ec`) to all primary calls-to-action for consistent brand recognition.
- Ensure all text has a minimum contrast ratio of 4.5:1 against its background for accessibility.
- Implement a standard hamburger menu pattern for navigation on mobile viewports.
- Maintain a clear typographic hierarchy using Anthropic's branded fonts, ensuring readability across all text scales.
- Maintain a consistent font weight of 300 for display and heading elements.

Example Component Prompts:
1. Create a Header/Navigation section for Home \ Anthropic using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a navigation-link component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.

## Similar Brands

No taste references were established from the available evidence.

## Quick Start

### CSS Custom Properties

```css
:root {
  --color-surface: #0000;
  --color-ink: rgb(20, 20, 19);
  --color-border: #ccc;
  --color-surface-dark: #222;
  --color-action: #3898ec;
  --color-transparent-black-0-05: #00000005;
  --color-transparent-black-0-10: #0000000a;
  --font-body-lg: "Anthropic Serif, sans-serif";
  --font-caption: "Anthropic Sans, sans-serif";
  --font-ui: "Anthropic Sans, sans-serif";
  --font-display-xl: "Anthropic Serif, sans-serif";
  --font-heading-lg: "Anthropic Sans, sans-serif";
  --font-heading-md: "Anthropic Serif, sans-serif";
  --font-heading-sm: "Anthropic Serif, sans-serif";
  --radius-round: 100vw;
  --radius-0: 0;
  --radius-1-5rem: 1.5rem;
  --radius-100: 100%;
  --radius-100rem: 100rem;
  --radius-2px: 2px;
  --radius-3px: 3px;
  --radius-50: 50%;
  --shadow-0-0-0000-0-0-0000-0-0-0000: 0 0 #0000,0 0 #0000,0 0 #0000;
  --shadow-0-0-0-1px-0000001a-0-1px-3px-0000001a: 0 0 0 1px #0000001a,0 1px 3px #0000001a;
  --shadow-0-0-0-2px-fff: 0 0 0 2px #fff;
  --shadow-0-0-3px-1px-3898ec: 0 0 3px 1px #3898ec;
  --shadow-0-2px-2px-00000003-0-4px-4px-00000005-0-16px-24px-0000000a: 0 2px 2px #00000003,0 4px 4px #00000005,0 16px 24px #0000000a;
  --shadow-0-4px-3px-00000005-0-10px-8px-00000008-0-19px-15px-0000000a-0-34px-27px-0000000a-0-63px-50px-0000000d-0-150px-120px-00000012: 0 4px 3px #00000005,0 10px 8px #00000008,0 19px 15px #0000000a,0 34px 27px #0000000a,0 63px 50px #0000000d,0 150px 120px #00000012;
  --shadow-none: none;
  --shadow-unset: unset;
  --layout-page-max-width: 1440px;
  --layout-nav-height: 4.375rem;
  --layout-section-padding-vertical: inferred;
  --layout-section-padding-horizontal: inferred;
  --layout-grid-gap: inferred;
  --layout-card-padding: 31.4776px;
}
```

### Tailwind v4

```css
@theme {
  --color-surface: #0000;
  --color-ink: rgb(20, 20, 19);
  --color-border: #ccc;
  --color-surface-dark: #222;
  --color-action: #3898ec;
  --color-transparent-black-0-05: #00000005;
  --color-transparent-black-0-10: #0000000a;
  --font-body-lg: "Anthropic Serif, sans-serif";
  --font-caption: "Anthropic Sans, sans-serif";
  --font-ui: "Anthropic Sans, sans-serif";
  --font-display-xl: "Anthropic Serif, sans-serif";
  --font-heading-lg: "Anthropic Sans, sans-serif";
  --font-heading-md: "Anthropic Serif, sans-serif";
  --font-heading-sm: "Anthropic Serif, sans-serif";
  --radius-round: 100vw;
  --radius-0: 0;
  --radius-1-5rem: 1.5rem;
  --radius-100: 100%;
  --radius-100rem: 100rem;
  --radius-2px: 2px;
  --radius-3px: 3px;
  --radius-50: 50%;
  --shadow-0-0-0000-0-0-0000-0-0-0000: 0 0 #0000,0 0 #0000,0 0 #0000;
  --shadow-0-0-0-1px-0000001a-0-1px-3px-0000001a: 0 0 0 1px #0000001a,0 1px 3px #0000001a;
  --shadow-0-0-0-2px-fff: 0 0 0 2px #fff;
  --shadow-0-0-3px-1px-3898ec: 0 0 3px 1px #3898ec;
  --shadow-0-2px-2px-00000003-0-4px-4px-00000005-0-16px-24px-0000000a: 0 2px 2px #00000003,0 4px 4px #00000005,0 16px 24px #0000000a;
  --shadow-0-4px-3px-00000005-0-10px-8px-00000008-0-19px-15px-0000000a-0-34px-27px-0000000a-0-63px-50px-0000000d-0-150px-120px-00000012: 0 4px 3px #00000005,0 10px 8px #00000008,0 19px 15px #0000000a,0 34px 27px #0000000a,0 63px 50px #0000000d,0 150px 120px #00000012;
  --shadow-none: none;
  --shadow-unset: unset;
  --layout-page-max-width: 1440px;
  --layout-nav-height: 4.375rem;
  --layout-section-padding-vertical: inferred;
  --layout-section-padding-horizontal: inferred;
  --layout-grid-gap: inferred;
  --layout-card-padding: 31.4776px;
}
```
