---
name: Pristine Precision
colors:
  surface: '#faf8fe'
  surface-dim: '#dbd9df'
  surface-bright: '#faf8fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#efedf3'
  surface-container-high: '#e9e7ed'
  surface-container-highest: '#e3e2e7'
  on-surface: '#1a1b1f'
  on-surface-variant: '#414753'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f6'
  outline: '#717785'
  outline-variant: '#c1c6d6'
  surface-tint: '#005cbb'
  primary: '#0059b5'
  on-primary: '#ffffff'
  primary-container: '#0071e3'
  on-primary-container: '#fcfbff'
  inverse-primary: '#abc7ff'
  secondary: '#5f5e60'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfe1'
  on-secondary-container: '#636264'
  tertiary: '#9b3f00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c25100'
  on-tertiary-container: '#fffaf9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#abc7ff'
  on-primary-fixed: '#001b3f'
  on-primary-fixed-variant: '#00458f'
  secondary-fixed: '#e4e2e4'
  secondary-fixed-dim: '#c8c6c8'
  on-secondary-fixed: '#1b1b1d'
  on-secondary-fixed-variant: '#474649'
  tertiary-fixed: '#ffdbcb'
  tertiary-fixed-dim: '#ffb693'
  on-tertiary-fixed: '#341000'
  on-tertiary-fixed-variant: '#7a3000'
  background: '#faf8fe'
  on-background: '#1a1b1f'
  surface-variant: '#e3e2e7'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.022em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.019em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.017em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.014em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.011em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.006em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.006em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-xs:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-dense: 1rem
  margin: 2rem
  margin-compact: 1.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system channels an exacting, premium editorial aesthetic tailored for the operational control center of a high-end Peruvian commercial brand. Rooted in disciplined minimalism, it prioritizes pure typographic clarity, deliberate spatial rhythm, and tactile confidence over superficial ornamentation.

The visual language mirrors the restrained elegance of native operating systems: immaculate starkness, ultra-precise hairline delineations, and high typographic contrast. Interfaces must feel immediate, frictionless, and institutional yet refined—empowering merchants to command complex catalog matrices, international logistics, and localized transactions with zero visual fatigue.

## Colors

The palette relies on strict chromatic hierarchy:
- **Base Canvas (`#FFFFFF`):** Absolute white foundation providing high dynamic range and pristine visual breathing room.
- **Structural Neutral & Panels (`#F5F5F7`):** The signature off-white surface tone used for grouped data panels, alternating data table rows, search bars, and subtle container beds.
- **Primary Ink (`#1D1D1F`):** Deep, non-harsh charcoal-black applied to headers, metric figures, active states, and critical data labels.
- **Secondary Ink (`#6E6E73`):** Neutral gray calibrating metadata, column labels, microcopy, breadcrumbs, and inactive glyphs.
- **Action Electric Blue (`#0071E3`):** The singular high-contrast focal color reserved strictly for interactive affordances: primary CTA triggers, active pagination tabs, text links, selected indicators, and affirmative control toggles.
- **Functional Hairline (`rgba(0, 0, 0, 0.08)`):** Micro-borders for strict pixel definition across modular cards and data table dividers.

## Typography

The typographical engine leverages **Inter** for its neutral Swiss geometry and high legibility across dense administrative screens.

- Negative tracking is strictly applied to larger headers (`-0.022em` down to `-0.014em`) to mirror native industrial OS styling.
- Metric values and currency figures (Peruvian Soles `S/.` and `USD`) rely on tabular numeric figures (`tnum`) with semi-bold weights for rapid scanning.
- Micro-labels and table headings maintain a deliberate balance between medium weight (`500`) and slight positive letter-spacing (`0.01em` to `0.03em`) when rendered in sub-12px scales.

## Layout & Spacing

The architecture operates on an 8-point base spatial cadence tailored for expansive desktop workflows:

- **Desktop Shell:** Fixed 240px collateral navigation sidebar on the left, flanked by a fluid primary canvas utilizing `margin: 2rem` (32px) and an inner container maximum constraint of 1440px for wide displays.
- **Data Grids:** 12-column layout with standard `1.5rem` (24px) gutters between metrics and chart modules; tight `1rem` (16px) gutters applied when displaying segmented multi-metric rows.
- **Vertical Rhythm:** Dashboard modules stack with a strict `2rem` (32px) gap. Internal container padding matches `1.5rem` (24px) along edges to create breathable spatial zones around high-density tables.

## Elevation & Depth

Depth is established primarily through tonal contrast and structural containment rather than dramatic drop shadows.

- **Flat Separation:** Primary panels rely on clean tonal shifts (`#FFFFFF` resting atop `#F5F5F7` or vice-versa), bound by a 1px boundary of `rgba(0, 0, 0, 0.06)`.
- **Level 1 (Panels & Tables):** Elevated zero-shadow surfaces with a pristine border: `border: 1px solid rgba(0, 0, 0, 0.05)`.
- **Level 2 (Popovers, Select Menus, Dropdowns):** Subtle ambient diffusion: `box-shadow: 0 4px 20px -2px rgba(0, 0, 0, 0.08), 0 2px 6px -1px rgba(0, 0, 0, 0.04)` wrapped in a 1px `rgba(0, 0, 0, 0.06)` boundary.
- **Level 3 (Modal Sheets & Drawers):** High-clarity ambient depth: `box-shadow: 0 16px 40px -8px rgba(0, 0, 0, 0.12)`, set against a frosted dim backdrop: `background: rgba(255, 255, 255, 0.8)`, `backdrop-filter: blur(20px)`.

## Shapes

The geometric framework is unified around consistent, organic roundedness:

- **Standard Radius (12px / `0.75rem`):** The primary radius applied to all cards, interactive form fields, action buttons, table wrappers, and segmented control containers.
- **Inner Controls (8px / `0.5rem`):** Applied to badges, table tags, nested control chips, and interior list selection pills.
- **Pill Elements (`9999px`):** Reserved exclusively for status indicators, toggle switches, and quick-filter pills.

## Components

### Buttons
- **Primary:** Solid `#0071E3`, white text (`#FFFFFF`), `font-weight: 500`, height 38px, padding 0 16px, border-radius 12px. Subtle brightness change on hover (`brightness(1.05)`), active scale compression (`scale(0.99)`).
- **Secondary:** Surface `#F5F5F7`, text `#1D1D1F`, border 1px solid `rgba(0, 0, 0, 0.04)`. Hover transitions to `#E8E8ED`.
- **Ghost:** Transparent background, text `#0071E3`, no border, padding 0 8px. Hover receives a light `#F5F5F7` background wash.

### Form Inputs & Search Fields
- Height 40px, background `#F5F5F7`, border-radius 12px, border 1px solid transparent.
- Primary text `#1D1D1F`, placeholder text `#6E6E73`.
- **Focus State:** Background transitions to `#FFFFFF`, surrounded by a 1px border of `#0071E3` with an outer focus halo: `box-shadow: 0 0 0 3px rgba(0, 113, 227, 0.15)`.

### Cards & Metrics Tiles
- Background `#FFFFFF`, border-radius 12px, 1px border in `rgba(0, 0, 0, 0.06)`, internal padding `1.5rem`.
- KPI blocks feature secondary text (`#6E6E73`, 12px uppercase) above dominant numeric metrics (`#1D1D1F`, 28px semi-bold).

### Tables & Data Grids
- Wrapped in a single continuous card with 12px rounded outer corners and a 1px border.
- Header row: `#FFFFFF`, 36px height, text `#6E6E73`, 12px semi-bold uppercase, subtle bottom border `1px solid rgba(0, 0, 0, 0.06)`.
- Body rows: 48px height, alternating fills (`#FFFFFF` and `#F5F5F7`), hover row highlight in `#EBEBED` with seamless instant transition. Cell text aligned to `#1D1D1F` (14px).

### Status Chips & Badges
- Height 22px, border-radius 6px, padding 0 8px, font-size 11px, font-weight 600.
- Paid/Delivered: Soft mint tint background `rgba(52, 199, 89, 0.12)`, text `#248A3D`.
- Pending/Processing: Soft amber tint background `rgba(255, 149, 0, 0.12)`, text `#B25000`.
- Cancelled: Soft rose tint background `rgba(255, 59, 48, 0.12)`, text `#D70015`.

### Checkboxes & Segmented Toggles
- Checkboxes: 18x18px, border-radius 5px, border `1.5px solid #6E6E73`. Checked state fills `#0071E3` with a sharp white checkmark.
- Segmented Control: Container filled with `#F5F5F7`, 4px internal padding, border-radius 10px. Active tab is an elevated `#FFFFFF` pill with `box-shadow: 0 1px 3px rgba(0, 0, 0, 0.08)`.