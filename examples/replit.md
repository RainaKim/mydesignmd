---
version: alpha
name: Replit – Build apps and sites with AI - Replit
description: Build and deploy software collaboratively with the power of AI without spending a second on setup.
components:
  clickable-text-link:
    backgroundColor: transparent
    textColor: rgb(0, 81, 195)
    rounded: 0px
sectionMap:
  page-background:
    background: white (inferred)
    text: rgb(64, 64, 64)
    border: transparent
    media: transparent
    layout: white
  primary-heading:
    background: transparent
    text: rgb(64, 64, 64)
    border: transparent
    media: transparent
    layout: transparent
  secondary-heading:
    background: transparent
    text: rgb(89, 89, 89)
    border: transparent
    media: transparent
    layout: transparent
  body-text-paragraph:
    background: transparent
    text: rgb(64, 64, 64)
    border: transparent
    media: transparent
    layout: transparent
  interactive-link-button:
    background: transparent
    text: rgb(0, 81, 195)
    border: transparent
    media: transparent
    layout: transparent
buildTokens:
  layout.content-max-width-desktop: 960px
  layout.content-max-width-mobile: 351px
  layout.paragraph-vertical-spacing: 15px
  layout.primary-heading-font-size-desktop: 60px
  layout.primary-heading-font-size-mobile: 36px
---

# Replit – Build apps and sites with AI - Replit — Style Reference
> functional, minimal, direct, typography and surface led, analysis hindered by security block page.

**Theme:** light

## Overview

The Replit.com website was inaccessible due to a security block page. This document outlines the foundational design system inferred from the limited visual elements available on that block page.

The observed styles represent a utilitarian aesthetic, characterized by clarity and directness, rather than the full, intended Replit brand experience. Key design principles prioritize readability and functional presentation.

**Key Characteristics:**
- Functional and minimal aesthetic.
- Direct communication style.
- Generous use of whitespace, contributing to a spacious, low-density layout.
- Restrained visual energy, prioritizing clarity over elaborate styling.
- Typography and surface treatments are the primary visual drivers.
- High contrast in text and background for optimal readability.
- Static visual presentation with no evident motion or transitions.

**Non-negotiables:**
- Ensure 'ABC Diatype Plus Variable' is consistently applied as the primary font for headings and body text, with a generic 'sans-serif' fallback. Consider `-apple-system` as an acceptable system-level fallback if custom fonts fail to load.
- Ensure all interactive elements provide a clear and sufficient visual focus indicator, preferably using the `2px solid var(--accent-primary-default)` style for keyboard navigation.
- Utilize a defined spacing scale (e.g., 2px, 4px, 8px, 12px, 16px, 20px) to ensure consistent and predictable rhythm between elements and sections.
- Utilize the 'monospace' font family exclusively for elements displaying code, command-line output, or other fixed-width text to maintain readability and distinction from proportional text.

## Colors

No specific color palette beyond functional grayscale and a primary link blue was captured due to the security block page. All primary surface treatments rely on white backgrounds and dark gray text for high contrast and readability. Further exploration of the full Replit brand is required to define a comprehensive color system.

## Typography

### Typography Principles

The Replit design system establishes clear typographic hierarchy through a careful selection of font family, size, weight, line-height, and case. The primary typeface, 'ABC Diatype Plus Variable', is used across headings and body text to maintain consistency and a modern, technical feel.

### Type Styles

- **display-hero**: `ABC Diatype Plus Variable`, `60px`, `300` weight, `89%` line-height. Used for prominent page titles and key statements.
- **title-md**: `ABC Diatype Plus Variable`, `32px`, `300` weight, `100%` line-height. Suitable for section headers and important sub-headings.
- **body-lg**: `ABC Diatype Plus Variable`, `18px`, `600` weight, `1.25` line-height. For emphasized body text or introductory paragraphs.
- **body-md**: `ABC Diatype Plus Variable`, `16px`, `400` weight, `120%` line-height. The standard text style for primary content paragraphs.
- **body-sm**: `ABC Diatype Plus Variable`, `14px`, `400` weight, `20px` line-height. For supporting text, detailed descriptions, or less prominent content.
- **caption**: `ABC Diatype Plus Variable`, `13px`, `400` weight, `16px` line-height. Small text for labels, annotations, or metadata.
- **caption-xs**: `ABC Diatype Plus Variable`, `11px`, `400` weight, `20px` line-height. Very small text for disclaimers or minor details.
- **code**: `monospace`, `13px`, `400` weight, `1` line-height. Dedicated for displaying code snippets, terminal output, or fixed-width textual information.

## Layout

### Composition Principles

The Replit layout emphasizes clarity and a sparse aesthetic with generous whitespace. This approach creates clear separation between major content blocks, enhancing readability and focus. Content is typically presented in a single, left-aligned column, which is horizontally centered on larger screens.

### Rhythm

Vertical rhythm is carefully managed through component-specific margins and padding. For instance, paragraphs maintain a `15px` vertical spacing, while larger implicit gaps separate primary headings from subsequent content. The overall density is 'generous', allowing content to breathe.

### Implementation Notes
- **Container Widths:** Desktop content is contained within a `960px` maximum width. Mobile layouts adapt to a fluid width, approximately 90% of the viewport (implying ~5% horizontal padding on each side).
- **Structure:** On mobile, content blocks primarily stack vertically. On desktop, informational blocks may adopt a simple two-column arrangement.
- **Alignment:** All content within the main container is left-aligned, with the container itself horizontally centered in the viewport.

### Section Treatment Map

This map outlines the default color application for various content sections and elements. Note that these are primarily based on the functional aesthetic of the security block page.

| Section | Background | Text | Border | Media | Layout | Treatment |
| --- | --- | --- | --- | --- | --- | --- |
| Page Background | white (inferred) | rgb(64, 64, 64) | transparent | transparent | white | The foundational canvas for all page content. |
| Primary Heading | transparent | rgb(64, 64, 64) | transparent | transparent | transparent | Key headlines and titles. |
| Secondary Heading | transparent | rgb(89, 89, 89) | transparent | transparent | transparent | Sub-headings and supporting titles. |
| Body Text / Paragraph | transparent | rgb(64, 64, 64) | transparent | transparent | transparent | Standard paragraph text. |
| Interactive Link/Button | transparent | rgb(0, 81, 195) | transparent | transparent | transparent | Links and call-to-action buttons. |

### Implementation Notes
- **layout.content-max-width-desktop**: `960px` — Defines the maximum width for content on desktop viewports.
- **layout.content-max-width-mobile**: `351px` — Defines the maximum width for content on mobile viewports.
- **layout.paragraph-vertical-spacing**: `15px` — Establishes consistent vertical spacing between paragraph elements.
- **layout.primary-heading-font-size-desktop**: `60px` — Specifies the font size for primary headings on desktop.
- **layout.primary-heading-font-size-mobile**: `36px` — Specifies the font size for primary headings on mobile.

### Build Notes
- The design observations are derived from a security block page, which is intentionally minimal. The full Replit site may exhibit a richer, more complex design system with additional components, layouts, and interactive elements.
- Ensure heading font sizes, particularly H1, scale effectively for mobile viewports to maintain readability and strong visual hierarchy across devices.

## Elevation & Depth

No distinct shadow or elevation system was evidenced on the block page. All surfaces appear flat, relying on solid fills and borders for visual separation. Similarly, no motion or transition system for interactive elements was observed, indicating a static visual experience.

## Shapes

The visual language does not employ prominent rounded corners or complex geometric shapes. Elements generally adhere to sharp, `0px` radius corners, contributing to a clean, precise, and functional aesthetic.

## Components

### Component Language

The observed components prioritize functionality and direct interaction. While the full suite of Replit components could not be assessed due to the block page, the evident interactive elements are stripped-back and high-contrast, designed for immediate comprehension.

### Buildable Component Recipes

#### Clickable Text Link
- **HTML Element:** `a` (anchor tag)
- **Background:** `transparent`
- **Text Color:** `rgb(0, 81, 195)` (a distinct blue for interactive elements)
- **Border:** `none`
- **Border Radius:** `0px`
- **Usage:** Standard interactive text links, typically found inline or as part of navigation.

#### Button
Interactive elements triggering actions or navigation, featuring various styles, sizes, and states. Designed for reusability across the application. While specific recipes were not fully captured, a general principle of clear visual feedback for interactive states (e.g., hover, focus) should be applied.

No rich media (images, video, or complex interactives) were present on the analyzed security block page. The design, therefore, relies entirely on typography, surface, and layout for communication. This absence suggests a highly functional and text-driven content strategy for such utility pages. Further investigation into full marketing and product pages would be necessary to define a comprehensive media strategy.

## Do's and Don'ts

### Do
- Adhere to the established font sizing hierarchy for buttons (e.g., 13px compact, 14px default, 24px large) to ensure readability and consistent visual weight.
- Adhere to the established line-height rhythm: tight for large display and title text to save vertical space and create impact, and more open for body and caption text to improve legibility.
- Apply smooth and quick transitions (e.g., `background-color .15s ease-out`, `color .2s`) for interactive states such as hover and focus, enhancing user feedback without distraction.
- Ensure 'ABC Diatype Plus Variable' is consistently applied as the primary font for headings and body text, with a generic 'sans-serif' fallback. Consider the observed `-apple-system` rendering as an acceptable system-level fallback if custom fonts fail to load.
- Ensure all interactive elements provide a clear and sufficient visual focus indicator, preferably using the `2px solid var(--accent-primary-default)` style for keyboard navigation.
- Maintain a consistent horizontal padding for fluid layouts on mobile devices to prevent content from touching screen edges, as seen with ~5% padding.
- Scale large heading font sizes down on mobile breakpoints to ensure readability and efficient use of screen space, while smaller headings may retain their size if already compact.
- Utilize a defined spacing scale (e.g., 2px, 4px, 8px, 12px, 16px, 20px) to ensure consistent and predictable rhythm between elements and sections.

## Responsive Behavior

### Breakpoints

The layout adapts to different screen sizes using distinct breakpoints, maintaining readability and usability across devices.

| Name | Width | Key Layout Changes |
| --- | --- | --- |
| **Desktop** | `>= 1024px` (inferred) | Content adheres to a fixed width of `960px`, horizontally centered. Informational sections (e.g., "Why have I been blocked?") arrange into a two-column layout. |
| **Mobile** | `<= 480px` (inferred) | Content adopts a fluid width, approximately `90%` of the viewport, with `5%` horizontal padding on each side. Informational sections stack vertically, adapting from the desktop's two-column presentation. |

### Implementation Notes
- **Heading Scaling**: Primary heading font sizes adjust from `60px` on desktop to `36px` on mobile to optimize for smaller screens.

## Iteration Guide

1. Prioritize using evidenced tokens and component names before introducing new variants.
2. Add new component variants only when supported by evidence or explicit product requirements.
3. Clearly mark all inferred guidance as extensions or recommendations, distinct from observed facts.

## Known Gaps

- **Limited Scope:** The analysis is based exclusively on a Cloudflare security block page, not the full Replit marketing or product website. This significantly limits the scope of observed design patterns, components, and brand expression.
- **Visual Personality:** The visual personality and brand elements described are heavily influenced by the utilitarian nature of the block page. The actual Replit brand is likely richer and more complex.
- **Complex Layouts:** The block page design is inherently simple, prioritizing direct content flow. Complex grid layouts (e.g., multi-column content areas beyond two basic divisions) were not evidenced.
- **Rich Media Usage:** There was no rich media (images, video, or complex interactive elements) on the analyzed page. A comprehensive media strategy cannot be fully defined from this limited context.
- **Elevation/Depth System:** No clear shadow or elevation system was observed, suggesting a flat design approach, but this may not be true for the full site.
- **Rounded Corners:** No consistent radius or shape system was evidenced beyond default square corners. The full site may feature a defined corner rounding strategy.

## Agent Prompt Guide

Implementation Rules:
- Adhere to the established font sizing hierarchy for buttons (e.g., 13px compact, 14px default, 24px large) to ensure readability and consistent visual weight.
- Adhere to the established line-height rhythm: tight for large display and title text to save vertical space and create impact, and more open for body and caption text to improve legibility.
- Apply smooth and quick transitions (e.g., `background-color .15s ease-out`, `color .2s`) for interactive states such as hover and focus, enhancing user feedback without distraction.
- Ensure 'ABC Diatype Plus Variable' is consistently applied as the primary font for headings and body text, with a generic 'sans-serif' fallback. Consider the observed `-apple-system` rendering as an acceptable system-level fallback if custom fonts fail to load.
- Ensure all interactive elements provide a clear and sufficient visual focus indicator, preferably using the `2px solid var(--accent-primary-default)` style for keyboard navigation.
- Maintain a consistent horizontal padding for fluid layouts on mobile devices to prevent content from touching screen edges, as seen with ~5% padding.

Example Component Prompts:
1. Create a `Page Background` section for Replit, employing the documented background (`white`), text color (`rgb(64, 64, 64)`), and layout (`white`) treatment. Ensure copy hierarchy follows the `Overview` section and avoid any unsupported decorative styles.
2. Develop a `Clickable Text Link` component using its exact background (`transparent`), text color (`rgb(0, 81, 195)`), radius (`0px`), and typography guidance. Implement `focus-visible` behavior following the non-negotiables.

## Similar Brands

- Aesop - as a reference for restrained retail/editorial pacing, not as a source to copy design elements directly.
- Le Labo - as a reference for monochrome product restraint and terse commerce language.
- COS - as a reference for quiet, image-led minimalism and disciplined neutral surfaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  --layout-content-max-width-desktop: 960px;
  --layout-content-max-width-mobile: 351px;
  --layout-paragraph-vertical-spacing: 15px;
  --layout-primary-heading-font-size-desktop: 60px;
  --layout-primary-heading-font-size-mobile: 36px;
}
```

### Tailwind v4

```css
@theme {
  --layout-content-max-width-desktop: 960px;
  --layout-content-max-width-mobile: 351px;
  --layout-paragraph-vertical-spacing: 15px;
  --layout-primary-heading-font-size-desktop: 60px;
  --layout-primary-heading-font-size-mobile: 36px;
}
```

