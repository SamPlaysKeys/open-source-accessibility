---
version: alpha
name: Open Source Accessibility Summit 2026
description: High-contrast, accessible brand system featuring Carbon Black, Graphite, Tuscan Sun gold, and architectural line geometry.
colors:
  canvas: "#212121"
  surface: "#303030"
  surface-light: "#C2C2C2"
  primary: "#EBC45E"
  secondary: "#C2C2C2"
  on-canvas: "#FFFFFF"
  on-surface: "#FFFFFF"
  on-primary: "#212121"
  border: "#303030"
  border-accent: "#EBC45E"
typography:
  display:
    fontFamily: "Lexend, sans-serif"
    fontWeight: 700
    letterSpacing: "0.02em"
    textTransform: "uppercase"
  heading:
    fontFamily: "Lexend, sans-serif"
    fontWeight: 600
  subtitle:
    fontFamily: "Lexend, sans-serif"
    fontWeight: 500
    color: "#EBC45E"
  body:
    fontFamily: "Arial, sans-serif"
    fontWeight: 400
    lineHeight: 1.6
rounded:
  sm: "4px"
  md: "8px"
  lg: "16px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  xxl: "48px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
    fontWeight: 600
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    borderColor: "{colors.secondary}"
    rounded: "{rounded.md}"
  card:
    backgroundColor: "{colors.surface}"
    borderColor: "{colors.border}"
    rounded: "{rounded.lg}"
---

# Design System: Open Source Accessibility Summit 2026 (OSA 26)

## 1. Visual Theme & Atmosphere

The Open Source Accessibility Summit 2026 design system builds on intentional structure and clarity to ensure accessible, inclusive products. Rich **Graphite** backgrounds with subtle elevated **Carbon Black** texture provide a dark interface that reduces visual fatigue while maintaining rigorous WCAG AAA contrast compliance. **Tuscan Sun** gold draws the eyes and serves as the primary color for buttons, accents, and key information.

The visual language is characterized by sharp, geometric features: crisp 119° diagonal stripes inspired by the summit emblem and offset double horizontal divider lines. The atmosphere feel technical, purposeful, and minimalist.  

---

## 2. Color Palette & Roles

| Swatch                                                          | Color Name       | Hex Code  | Functional Role                                                                                                                                                                                    |
| :-------------------------------------------------------------- | :--------------- | :-------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![#212121](https://via.placeholder.com/14/212121/000000?text=+) | **Carbon Black** | `#212121` | **Secondary Foreground / Secondary Background / Textural Interest**: Headings, title typography, and readable body copy on light backgrounds; page or card backgrounds; subtle background texture. |
| ![#303030](https://via.placeholder.com/14/303030/000000?text=+) | **Graphite**     | `#303030` | **Base Canvas / Page Background / Textural Interest**: Dark foundational background providing maximum contrast and reducing eye strain, subtle background texture.                                 |
| ![#EBC45E](https://via.placeholder.com/14/EBC45E/000000?text=+) | **Tuscan Sun**   | `#EBC45E` | **Brand Accent & Action**: Primary CTAs, active states, focus indicators, subtitle accents, line dividers, badges, and focal brand marks.                                                          |
| ![#C2C2C2](https://via.placeholder.com/14/C2C2C2/000000?text=+) | **Silver**       | `#C2C2C2` | **Secondary Neutral**: Supporting copy, metadata labels, icon accents, secondary borders, secondary containers, sidebars, and light badge backgrounds.                                             |
| ![#FFFFFF](https://via.placeholder.com/14/FFFFFF/000000?text=+) | **White**        | `#FFFFFF` | **Primary Foreground**: Headings, title typography, primary readable body copy, and high-contrast icons.                                                                                           |

---

## 3. Typography Rules

### Font Families
- **Display & Headings:** `Lexend` (Google Font engineered specifically to improve reading proficiency, reduce visual crowding, and maximize cognitive accessibility).
- **Body & Subtitles:** `Arial` (Universal, clean, high-legibility sans-serif standard with open counters and distinct character differentiation).

### Hierarchy & Stylings
- **H1 / Page Titles:** `Lexend`, 700 Bold or 800 ExtraBold, uppercase, color: `#FFFFFF`. Often paired with the signature offset horizontal underline.
- **H2 / Subtitles & Section Labeling:** `Lexend`, 500 Medium / 600 SemiBold, color: `#EBC45E` (Tuscan Sun), title case.
- **H3 Headings:** `Lexend`, 600 SemiBold, color: `#FFFFFF`.
- **Body Text:** `Arial`, 400 Regular, 16px minimum on web, line height 1.6 (`1.6em`), color: `#FFFFFF` (high contrast) or `#C2C2C2` (secondary descriptions).
- **Captions & Footnotes:** `Arial`, 400 Regular / 500 Medium, 12px–14px, color: `#C2C2C2`.

---

## 4. Component Stylings

### Buttons & Interactive Controls
- **Primary Action (CTA):**
  - Background: `#EBC45E` (Tuscan Sun)
  - Text: `#212121` (Carbon Black, 600 SemiBold)
  - Border Radius: `8px` (`rounded.md`)
  - Hover / Focus: Outline `2px solid #FFFFFF`, offset `2px`.
- **Secondary / Ghost Button:**
  - Background: Transparent or `#212121` (Carbon Black)
  - Text: `#FFFFFF`
  - Border: `1px solid #C2C2C2`
  - Hover: Border changes to `#EBC45E`, text to `#EBC45E`.

### Cards & Containers
- **Standard Card on Carbon Black Page:**
  - Background: `#303030` (Graphite)
  - Border Radius: `16px` (`rounded.lg`)
  - Padding: `24px` (`spacing.lg`)
- **Standard Card on Graphite Page:**
  - Background: `#212121 (Carbon Black)
  - Border Radius: `16px` (`rounded.lg`)
  - Padding: `24px` (`spacing.lg`)
- **Inverted / Light Badge Container:**
  - Background: `#C2C2C2` (Silver)
  - Content / Icon: `#212121` (Carbon Black)
  - Border Radius: `16px`
- **Bold Badge Container:**
  - Background: `#EBC45E (Tuscan Sun)
  - Content / Icon: `#212121` (Carbon Black)
  - Border Radius: `16px` (`rounded.lg`)

### Inputs & Forms
- Background: `#212121`
- Active / Focus: `2px solid #EBC45E` with `2px` focus ring offset
- Placeholder: `#C2C2C2` at 60% opacity

---

## 5. Graphic Patterns & Layout Principles

### 1. Offset Horizontal Lines (Section Framing)
- **Geometry:** Two paired horizontal rules: one thin line and one thick line.
- **Thickness & Space Ratio:** `5:15:1` (5 units thick line : 15 units gap : 1 unit thin line).
- **Rule:** The thin line must always be shorter than the thick line, offset horizontally to frame titles, subtitles, or badges.
- **Color:** `#EBC45E` (Tuscan Sun).

### 2. 119° Diagonal Stripe / Chevron Pattern
- **Angle:** Parallel lines drawn strictly at **`119°`** (matching the angled legs of the summit chevron "A" emblem).
- **Spacing Principle:** *Space between lines must be strictly equal to the width of the line.*
- **Modes of Application:**
  - **Ambient Depth Pattern:** Low-contrast `#303030` stripes on `#212121` canvas or `#212121` stripes on `#303030` canvas for background sections, cards, and footers.
  - **Light Depth Pattern:** Low-contrast `#C2C2C2` stripes on `#FFFFFF` canvas or `#FFFFFF` stripes on `#C2C2C2` canvas for light background sections, cards, and footers.
  - **Bold Brand Accent:** High-contrast `#EBC45E` stripes on any canvas for hero banners, conference badges, and keynote presentation slides.

### 3. Grid & Spacing Strategy
- **Base Grid:** 8px baseline grid (`8px`, `16px`, `24px`, `32px`, `48px`).
- **Whitespace:** Generous spacing around text blocks to enhance legibility and screen reader navigation boundaries.

