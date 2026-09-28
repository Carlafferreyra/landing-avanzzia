---
name: Avanzzia Monograph
colors:
  surface: '#f9faf5'
  surface-dim: '#d9dad5'
  surface-bright: '#f9faf5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4ef'
  surface-container: '#edeee9'
  surface-container-high: '#e8e9e4'
  surface-container-highest: '#e2e3de'
  on-surface: '#1a1c19'
  on-surface-variant: '#45474d'
  inverse-surface: '#2f312e'
  inverse-on-surface: '#f0f1ec'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f75'
  primary: '#051124'
  on-primary: '#ffffff'
  primary-container: '#1b263a'
  on-primary-container: '#828da6'
  inverse-primary: '#bcc7e1'
  secondary: '#47607e'
  on-secondary: '#ffffff'
  secondary-container: '#bfd9fd'
  on-secondary-container: '#465f7d'
  tertiary: '#001226'
  on-tertiary: '#ffffff'
  tertiary-container: '#10273f'
  on-tertiary-container: '#7a8fac'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2fe'
  primary-fixed-dim: '#bcc7e1'
  on-primary-fixed: '#101c2f'
  on-primary-fixed-variant: '#3c475c'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#afc9eb'
  on-secondary-fixed: '#001d36'
  on-secondary-fixed-variant: '#2f4865'
  tertiary-fixed: '#d2e4ff'
  tertiary-fixed-dim: '#b3c8e7'
  on-tertiary-fixed: '#041c34'
  on-tertiary-fixed-variant: '#334862'
  background: '#f9faf5'
  on-background: '#1a1c19'
  surface-variant: '#e2e3de'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 4.5rem
    fontWeight: '400'
    lineHeight: 4.75rem
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2.75rem
    fontWeight: '400'
    lineHeight: 3rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 3rem
    fontWeight: '400'
    lineHeight: 3.5rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: 2.35rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Newsreader
    fontSize: 2rem
    fontWeight: '400'
    lineHeight: 2.5rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Newsreader
    fontSize: 1.375rem
    fontWeight: '500'
    lineHeight: 1.75rem
    letterSpacing: 0em
  subhead-lg:
    fontFamily: Newsreader
    fontSize: 1.25rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Manrope
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Manrope
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Manrope
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Manrope
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.1em
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  gutter-desktop: 2rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system expresses digital architecture through the deliberate rigor of architectural monographs and technical blueprints. Designed for high-tier enterprise decision-makers and scaling brands, it balances engineering authority with editorial elegance. The aesthetic rejects decorative softness in favor of structural clarity, orthogonal precision, and measured typographic scale.

The visual tone is intellectual, architectural, and restrained. Surfaces evoke fine textured paper stock, while sharp linear grids delineate functional zones without clutter. Interaction states favor micro-transitions of color and line weight rather than synthetic dimension.

## Colors

The palette translates architectural materials into digital interfaces:
- **Base Canvas (`#E0E1DC`)**: A concrete/limestone neutral paper tone providing a warm, tactile foundation without stark white glare.
- **Deep Slate / Ink (`#1B263A`)**: The primary structural color used for core text, structural framing, high-emphasis containers, and primary CTA buttons.
- **Structural Blue (`#415A78`)**: The secondary color handling secondary interactive controls, tabular headers, and active states.
- **Technical Steel (`#788DAA`)**: Tertiary tone reserved for blueprint coordinate markers, delicate dividing lines, muted metadata, and inactive outlines.
- **Midnight Navy (`#0E1B2A`)**: The deepest structural shade, deployed for high-contrast inverted case studies, footers, and foundational navigational bars.

Contrast ratios prioritize WCAG AAA compliance for body text on the `#E0E1DC` canvas using `#1B263A` ink.

## Typography

The typography pairs the editorial authority of **Newsreader** with the clean geometric functionalism of **Manrope**.

- **Editorial Headlines**: Display and headline tiers employ Newsreader at light and regular weights. Subheadings leverage italicized Newsreader to provide monograph-level narrative pacing.
- **Architectural Body & Labels**: Manrope provides clarity for dense content, specifications, and service descriptions. Upper-case labels with expanded letter-spacing (`0.08em` to `0.1em`) evoke architectural blueprint coordinate tags and project codification.

## Layout & Spacing

Layout adheres to an explicit 12-column architectural grid on desktop and 4-column layout on mobile devices. 

- **Grid Alignment**: Outer boundaries conform to structural gutters (`1.5rem` standard, expanding to `2rem` on wide desktop screens). Structural sections separate with full-bleed `1px` lines utilizing `#788DAA` at 30% opacity.
- **Vertical Rhythm**: Generous whitespace (`space-2xl` to `space-3xl`) isolates major conceptual zones, ensuring the reading experience feels deliberate, expansive, and high-end.
- **Modular Tiers**: Card groups and deliverables utilize continuous hairline borders, snapping to common column baselines.

## Elevation & Depth

This system avoids blurred drop shadows and skeuomorphic bevels. Elevation is achieved exclusively through **planar zoning and linear boundaries**:

1. **Planar Tiers**:
   - Level 0 (Ground Canvas): `#E0E1DC`
   - Level 1 (Surface Modals & Cards): `#FFFFFF` or elevated `#ECECE8`
   - Level 2 (Inverted Anchor Zones): `#0E1B2A` with `#E0E1DC` text
2. **Crisp Blueprint Separation**:
   - Elevation and compartmentalization rely on 1px solid hairline borders (`#1B263A` at 15% opacity or `#788DAA` at 40% opacity).
   - In interactive hover states, depth shifts not through Z-axis shadows, but through 1px border contrast shifts to solid `#1B263A` or a sharp 2px solid offset outline.

## Shapes

Every component adheres to a strict **0px border-radius** (Sharp). Corners are razor-sharp across buttons, inputs, tags, dialogs, and image viewports, reflecting architectural drawings, drafting tables, and systemic precision. No rounded corners or pill badges are permitted.

## Components

### Buttons
- **Primary Action**: Solid `#1B263A` background, `#E0E1DC` uppercase text (`label-md`), 0px radius, padding `0.875rem 2rem`. On hover, background shifts to `#415A78`.
- **Secondary Action**: Transparent background with a 1px solid `#1B263A` stroke, `#1B263A` text. On hover, fills with `#1B263A` and inverts text to `#E0E1DC`.
- **Text Link Button**: Editorial underline spaced 4px below text, `#1B263A`, with an accompanying directional arrow indicator (`→`).

### Input Fields & Selects
- Single-line or surface input set with 1px solid `#788DAA` border, background `#FFFFFF` or transparent on `#E0E1DC`.
- Label placed externally above input in uppercase `label-sm` (`#415A78`). Focus state deepens border to a 1px solid `#1B263A` with zero glow.

### Cards & Modules
- Modules maintain flat surfaces with a 1px outline of `#1B263A` at 20% opacity.
- Top header zones contain an index numbering system (e.g., `01 / ARQUITECTURA`, `02 / E-COMMERCE`) styled in `label-sm` using `#788DAA`.

### Badges & Chips
- Sharp rectangular enclosures (0px radius) with 1px perimeter border.
- Background uses transparent fill or 5% tint of `#415A78`. Text uses `label-sm` in `#1B263A`.

### Checkboxes & Radio Controls
- Checkboxes: 16x16px square, 0px radius, 1px solid `#1B263A`. Checked state displays a solid inner square fill with 3px internal padding.
- Radio buttons: 16x16px square containing a nested square dot indicator (rejecting rounded circles to reinforce the orthogonal architectural theme).

### Technical Tables & Data Grids
- Full-width dividers at 1px solid `#788DAA` (20% opacity).
- Headers set in `label-md` with tracking. Numeric tabular data rendered cleanly with monospace or lining figures in `body-md`.