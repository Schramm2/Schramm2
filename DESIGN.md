---
name: Matthew Schramm GitHub Profile
description: A professional profile built around connected AI and robot-data work.
colors:
  cobalt: "#1638c9"
  cobalt-dark: "#102775"
  soft-white: "#f4f7ff"
  signal-mint: "#89e5c6"
  signal-amber: "#ffcc66"
typography:
  display:
    fontFamily: "Manrope, outlined as SVG paths"
    fontSize: "82px first line and 96px second line desktop; 58px both lines mobile"
    lineHeight: 1
  body:
    fontFamily: '-apple-system, BlinkMacSystemFont, "Segoe UI", "Noto Sans", Helvetica, Arial, sans-serif'
    fontSize: "16px"
    lineHeight: 1.5
  label:
    fontFamily: "Arial, Helvetica, sans-serif"
    fontSize: "16px–27px"
---

# Design System: Matthew Schramm GitHub Profile

## Overview

**Creative North Star: "Woven Systems"**

Three interlocking paths identify the profile's work across context, agents, and robot data. Cobalt fields hold the graphic. Mint, white, and amber paths connect its parts. The name uses Manrope outlines. Plain Arial labels keep the SVG portable.

The profile text and links use GitHub Markdown. Keep all key information readable when the header is still. The header adapts to GitHub's light and dark themes and to narrow screens.

**Key Characteristics:**
- Original geometric SVG artwork.
- Native, selectable GitHub Markdown for the profile content.
- Finite path motion with reduced-motion support.

## Colors

The palette uses theme-specific cobalt fields and three clear path colors.

### Primary
- **Cobalt Field** (`cobalt`): Background for the light-theme header.
- **Deep Cobalt Field** (`cobalt-dark`): Background for the dark-theme header.

### Secondary
- **Signal Mint** (`signal-mint`): First woven path.

### Tertiary
- **Warm Amber** (`signal-amber`): Third woven path.

### Neutral
- **Soft White** (`soft-white`): Name, supporting labels, and the second path.

**The Woven Paths Rule.** Keep the three paths tied to context, agents, and robot data.

## Typography

**Display Font:** Manrope, outlined as SVG paths.
**Body Font:** GitHub's native system sans-serif stack.
**Label Font:** Arial, Helvetica, sans-serif.

**Character:** Thin outlined lettering gives the name space. Plain sans-serif labels keep the role and location clear.

### Hierarchy
- **Display** (82px first line and 96px second line desktop; 58px both lines mobile): Name mark in the SVG header. See OFL-Manrope.txt for the Manrope license.
- **Label** (role: 27px desktop and 20px mobile; subtitle: 23px desktop; location and footer: 20px desktop and 16px mobile): SVG role, subtitle, location, and path captions.
- **Body** (16px, 1.5 line-height): GitHub Markdown copy and links.

## Layout

The desktop SVG artboard is 1100 × 460px. It places the name and role on the left and the woven paths on the right. The mobile artboard is 440 × 490px, with the name and labels above the paths. The README selects the mobile SVG at a 600px viewport width. GitHub Markdown controls the profile text layout.

## Elevation & Depth

The header uses flat color fields and no shadows. The broad strokes, contrast, and path crossings provide depth.

## Shapes

The three paths use 26px strokes with round caps. The SVG field has square corners. It has no card frame or decorative border.

## Components

**Original SVG masthead.** The responsive header combines the outlined name, plain labels, and three interlocking paths. Its signal dash moves for two 2.4-second passes, then stops. Reduced-motion settings disable the animation. The production graphic stays as SVG.

Profile links, headings, lists, and body text use GitHub's native Markdown presentation.

## Do's and Don'ts

### Do:
- **Do** keep profile facts and links in native GitHub Markdown.
- **Do** use the theme and viewport-specific SVG variants, with the 600px breakpoint.
- **Do** keep motion finite and disable it for reduced-motion settings.

### Don't:
- **Don't** add scripts, external font downloads, or generated raster artwork to the production header.
- **Don't** make essential profile information depend on the animation.
- **Don't** add shadows or extra colors to the header.
