---
version: alpha
name: Home \\| Microsoft AIYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out Icon
description: Balancing cutting-edge AI superintelligence with a humanist, responsible approach to empower humanity.
typography:
  font.ui:
    fontFamily: Red Hat Mono, monospace
    fontSize: 14.2222px
    fontWeight: 500
    lineHeight: 1.25
    role: Body copy / UI element text
  font.caption:
    fontFamily: Red Hat Mono, monospace
    fontSize: 11.5556px
    fontWeight: 400
    lineHeight: 1.4
    role: Small caption / Description text
  font.display:
    fontFamily: Red Hat Mono, monospace
    fontSize: 21.3333px
    fontWeight: 500
    lineHeight: 1.2
    role: Secondary display / Navigation group heading
components:
  primary-button:
    backgroundColor: rgb(93, 82, 75)
    textColor: rgb(247, 236, 217)
    rounded: 28.4444px
    padding: 14.2222px 42.6667px
    typography: Red Hat Mono
  secondary-button:
    backgroundColor: rgb(247, 236, 217)
    textColor: rgb(93, 82, 75)
    rounded: 28.4444px
    padding: 14.2222px 42.6667px
    typography: Red Hat Mono
  tertiary-button:
    backgroundColor: rgb(251, 240, 220)
    textColor: rgb(93, 82, 75)
    rounded: 0px
    padding: 5px 15px
    typography: Bradford LL
  dark-feature-card:
    backgroundColor: rgb(251, 211, 190)
    textColor: rgb(254, 249, 237)
    rounded: 0px
  light-feature-card:
    backgroundColor: rgb(254, 249, 237)
    textColor: rgb(93, 82, 75)
    rounded: 3.33333px
sectionMap:
  generic:
    background: rgb(251, 240, 220)
    text: rgb(93, 82, 75)
  feature-grid:
    background: rgb(254, 249, 237)
    text: rgb(93, 82, 75)
---

# Home \\| Microsoft AIYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out Icon — Style Reference
> sophisticated, thoughtful, natural, precise, modern_editorial

**Theme:** light

## Overview

This design system balances the gravitas of enterprise-grade AI with an unexpectedly warm, human-scaled visual language. The result is a digital environment that acknowledges both the transformative power of superintelligence and the critical importance of responsible, human-centered development.

The interface conveys technical precision through Red Hat Mono's monospaced rhythm and Bradford LL's editorial authority, while warm neutral backgrounds (cream, sand, pale peach) soften the typically austere tech aesthetic. This duality—between computational rigor and approachable warmth—reflects Microsoft's commitment to democratizing advanced AI without sacrificing trustworthiness or accessibility.

**Voice:** headlines=informative_aspirational; body=professional_descriptive; microcopy=functional_concise; ctas=direct_action_oriented

## Colors

No supported color palette was captured.

## Typography

### Typography Principles

- Treat typography as a system of distinct roles, not interchangeable styles. Red Hat Mono's monospaced geometry anchors UI elements, navigation, and body text with systematic precision. Bradford LL's editorial character reserves itself for primary headlines and moments of brand distinction.

- The monospace rhythm of Red Hat Mono creates a subtle technical cadence across the interface—visible in equal-width characters, tabular alignment opportunities, and a disciplined horizontal pace that evokes code editors and terminal interfaces without feeling overly technical.

- Resist the temptation to use Bradford LL for utility text or dense controls. Its letterforms carry too much personality for functional microcopy. Similarly, Red Hat Mono should not appear in large display sizes unless the context specifically calls for technical authority.

### Font Family

- **Red Hat Mono, monospace**; role: Body copy / UI element text.

- **Bradford LL, sans-serif**; role: Primary display headline.

- **Red Hat Mono, monospace**; role: Secondary display / Navigation group heading.

- **Red Hat Mono, monospace**; role: Small caption / Description text.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
| --- | --- | --- | --- | --- | --- |
| {typography.font.ui} | 14.2222px | 500 | 1.25 |  | Body copy / UI element text |
| {typography.font.display} | 21.3333px | 450 | 0.97 |  | Primary display headline |
| {typography.font.display} | 21.3333px | 500 | 1.2 |  | Secondary display / Navigation group heading |
| {typography.font.caption} | 11.5556px | 400 | 1.4 |  | Small caption / Description text |

## Layout

### Composition Principles
- Structure pages as semantically distinct sections, each with explicit background, text, and component treatment—not as one undifferentiated container. This approach allows different content zones (hero, feature grid, testimonials, footer) to establish their own tonal registers within a cohesive whole.
- grid_based_content

### Section Treatment Map

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| generic | rgb(254, 249, 237) | rgb(93, 82, 75) |  |  |  |  |
| generic | rgb(251, 240, 220) | rgb(93, 82, 75) |  |  |  |  |
| feature_grid | rgb(254, 249, 237) | rgb(254, 249, 237) |  |  |  |  |
| feature_grid | rgb(254, 249, 237) | rgb(93, 82, 75) |  |  |  |  |

## Elevation & Depth

No shadow or elevation system is evidenced.

No motion or transition system is evidenced.

## Shapes

No radius or shape system is evidenced.

## Components

### Buildable Component Recipes
#### primary_button
- **Component:** Primary Button
- **Background:** rgb(93, 82, 75)
- **Text:** rgb(247, 236, 217)
- **Border:** 0px
- **Radius:** 28.4444px
- **Padding:** 14.2222px 42.6667px
- **Typography:** Red Hat Mono

#### secondary_button
- **Component:** Secondary Button
- **Background:** rgb(247, 236, 217)
- **Text:** rgb(93, 82, 75)
- **Border:** 0px
- **Radius:** 28.4444px
- **Padding:** 14.2222px 42.6667px
- **Typography:** Red Hat Mono

#### tertiary_button
- **Component:** Tertiary Button
- **Background:** rgb(251, 240, 220)
- **Text:** rgb(93, 82, 75)
- **Border:** 0px
- **Radius:** 0px
- **Padding:** 5px 15px
- **Typography:** Bradford LL

#### Dark Feature Card
- **Component:** Feature Card
- **Background:** rgb(251, 211, 190)
- **Text:** rgb(254, 249, 237)
- **Border:** 0px
- **Radius:** 0px

#### Light Feature Card
- **Component:** Feature Card
- **Background:** rgb(254, 249, 237)
- **Text:** rgb(93, 82, 75)
- **Border:** 0px
- **Radius:** 3.33333px

### Button (Primary)

The primary action button uses a deep taupe background (rgb(93, 82, 75)) paired with a soft cream text (rgb(247, 236, 217)), creating high contrast without the harshness of pure black-and-white. The 28.4444px border radius produces a pill-shaped silhouette that feels approachable and contemporary, while the asymmetric horizontal padding (3:1 ratio) gives the button generous breathing room. Red Hat Mono's monospace letterforms inside the button reinforce the system's technical lineage, while the rounded edges prevent the UI from feeling cold or utilitarian. On hover, the button inverts its colors—a subtle but tactile interaction that avoids the need for shadows or scale transforms.

### Feature Card (Dark Background)

This card variant uses a warm terracotta background (rgb(251, 211, 190)) with light cream text (rgb(254, 249, 237)), creating an inviting, almost tactile surface that stands apart from typical tech interfaces. The square corners (0px radius) give the card architectural solidity, while the warm color pairing suggests accessibility and human warmth rather than corporate distance. Use this variant to highlight editorial content, testimonials, or feature announcements where a less transactional, more narrative tone is appropriate. The color contrast is lower than the light variant, so reserve it for contexts where extended reading is not required.

### Feature Card (Light Background)

The light feature card pairs a near-white background (rgb(254, 249, 237)) with the system's primary text color (rgb(93, 82, 75)), establishing the interface's default reading environment. The subtle 3.33333px border radius softens corners just enough to distinguish cards from the page canvas without introducing overt "card-ness." This variant serves as the workhorse for feature grids, product listings, and informational modules—any context where clarity, scannability, and sustained reading matter more than dramatic visual impact. The minimal rounding and high text contrast make this card ideal for dense, information-rich layouts.

## Do's and Don'ts

### Do
- Use Red Hat Mono at 14.2222px / weight 500 / line-height 1.25 for body copy, navigation labels, and UI text. The monospace rhythm creates a disciplined horizontal pace that unifies disparate interface elements.
- Set backgrounds to rgb(254, 249, 237) or rgb(247, 236, 217) for primary content zones. These warm, low-saturation neutrals provide a soft, approachable canvas that differentiates this system from the stark whites and grays typical of enterprise software.
- Compress line heights for display text to 0.97 or below (as in Bradford LL headlines at 21.3333px / 450 weight). This tightness increases visual impact and creates breathing room around headings without requiring oversized type.
- Implement primary buttons with a 28.4444px border radius and 14.2222px vertical padding. On hover, invert background and text colors (rgb(93, 82, 75) ↔ rgb(247, 236, 217)) rather than adding shadows or scale effects.
- Maintain text color at rgb(93, 82, 75)—a warm taupe rather than pure black—against light backgrounds. This choice reduces eye strain and reinforces the system's humanist, non-corporate aesthetic.
- Reserve Bradford LL exclusively for primary headlines and high-level messaging. Its editorial authority should punctuate the interface, not dominate it.
- Use Red Hat Mono for technical content, subheadings, metadata, and UI controls where systematic precision and scannability outweigh expressive personality.

## Responsive Behavior

No breakpoint-specific responsive behavior is evidenced.

## Iteration Guide

1. Start from the evidenced tokens and component names before inventing variants.
2. Add new variants as separate component entries when evidence or product requirements justify them.
3. Keep inferred guidance marked as an extension, not an observed fact.

## Known Gaps

- No major evidence gaps were reported.

## Agent Prompt Guide

Quick Typography Reference:
- ui: Red Hat Mono, monospace, 14.2222px, 500, line-height 1.25
- body: Red Hat Mono, monospace, 11.5556px, 400, line-height 1.4
- headings: Bradford LL, sans-serif, 21.3333px, 450, line-height 0.97

Implementation Rules:
- Use Red Hat Mono at 14.2222px / weight 500 / line-height 1.25 for body copy, navigation labels, and UI text. The monospace rhythm creates a disciplined horizontal pace that unifies disparate interface elements.
- Set backgrounds to rgb(254, 249, 237) or rgb(247, 236, 217) for primary content zones. These warm, low-saturation neutrals provide a soft, approachable canvas that differentiates this system from the stark whites and grays typical of enterprise software.
- Compress line heights for display text to 0.97 or below (as in Bradford LL headlines at 21.3333px / 450 weight). This tightness increases visual impact and creates breathing room around headings without requiring oversized type.
- Implement primary buttons with a 28.4444px border radius and 14.2222px vertical padding. On hover, invert background and text colors (rgb(93, 82, 75) ↔ rgb(247, 236, 217)) rather than adding shadows or scale effects.
- Maintain text color at rgb(93, 82, 75)—a warm taupe rather than pure black—against light backgrounds. This choice reduces eye strain and reinforces the system's humanist, non-corporate aesthetic.
- Reserve Bradford LL exclusively for primary headlines and high-level messaging. Its editorial authority should punctuate the interface, not dominate it.

Example Component Prompts:
1. Create a generic section for Home \\| Microsoft AIYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out IconYour Privacy Choices Opt-Out Icon using the documented background, text color, layout, and media treatment. Keep copy hierarchy faithful to the Overview and avoid unsupported decorative styles.
2. Create a primary_button component using its exact background, text, radius, padding, typography, state, and motion guidance. Include focus-visible behavior.

## Similar Brands

- Aesop - reference for restrained retail/editorial pacing, not a source to copy.
- Le Labo - reference for monochrome product restraint and terse commerce language.
- COS - reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --font-ui: "Red Hat Mono, monospace";
  --font-caption: "Red Hat Mono, monospace";
  --font-display: "Bradford LL, sans-serif";
}
```

### Tailwind v4

```css
@theme {
  --font-ui: "Red Hat Mono, monospace";
  --font-caption: "Red Hat Mono, monospace";
  --font-display: "Bradford LL, sans-serif";
}
```
