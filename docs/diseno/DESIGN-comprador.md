---
name: Andean Precision
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
  display-hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: -0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.25rem
---

## Brand & Style
The design system embodies a calm, precise, and premium retail experience tailored for mobile-first commerce. Rooted in deliberate simplicity, it merges the technological clarity of modern industrial hardware with the disciplined elegance of Peruvian craft culture—prioritizing restraint, intentional negative space, and uncompromised clarity over decorative excess.

### Visual Style
- **Pure Minimalism:** Pure white canvases punctuated by cool-neutral surface layers and precise typography.
- **Zero Distraction:** Elimination of non-essential badges, promotional ribbons, decorative borders, and saturated graphic treatments.
- **Hardware-Focused:** Visual weight is deferred entirely to crisp product imagery and deliberate typography.

## Colors
The palette is built strictly around high clarity, tactile focus, and deliberate functional hierarchy:

- **Canvas (`#FFFFFF`):** The primary backdrop, providing boundless white space and framing products with gallery-level focus.
- **Surface (`#F5F5F7`):** The singular substrate for cards, inset wells, segmented bars, and search inputs. It provides subtle boundary definition without relying on harsh divider lines.
- **Text Primary (`#1D1D1F`):** Deep charcoal-black for headline hierarchies, key metrics, and primary titles.
- **Text Secondary (`#6E6E73`):** Neutral gray for specifications, product series metadata, and supporting microcopy.
- **Interactive Accent (`#0071E3`):** Reserved exclusively for primary actions, system status, active controls, and verified state indicators. Never used decoratively.
- **Active Neutral (`#E8E8ED`):** Reserved for subtle pressed states and disabled UI chips.

## Typography
Inter delivers a geometric, neutral, and meticulously legible structure across all digital viewport sizes. 

### Typographic Principles
- **Tracking:** Headings feature tightened negative tracking to establish cohesive editorial lockups, while micro-labels utilize slight positive tracking for scannability.
- **Hierarchy:** Strict two-weight balance (`400` Regular and `600` Semi-Bold) avoids visual noise. `500` Medium is reserved purely for interactive touch targets and specs labels.
- **Price Treatment:** Currency notations (e.g., `S/. 4,299`) inherit `headline-md` or `headline-sm` with tabular numerals to ensure alignment consistency across catalog views.

## Layout & Spacing
A fluid, mobile-centric grid prioritizes immediate single-thumb accessibility and vertical rhythm.

### Grid & Breakpoints
- **Mobile (< 768px):** 4-column layout with 16px (`1rem`) outer margins and 12px (`0.75rem`) gutters. Content cards snap edge-to-edge or fit evenly into single and double column matrices.
- **Tablet / Desktop (≥ 768px):** 12-column layout centered with max width 1120px, 24px (`1.5rem`) margins, and 16px (`1rem`) gutters.

### Spacing Philosophy
Layout decisions favor generous empty space (`space-lg` and `space-xl`) between distinct product groups over artificial divider lines. In-card padding strictly adheres to 20px (1.25rem) to maintain balanced negative space framing the product hardware.

## Elevation & Depth
Depth is created strictly through flat tonal surfaces and soft ambient atmosphere—eschewing heavy dropshadows, distinct strokes, or heavy multi-level layering.

### Surface Tiers
- **Layer 0 (Base):** Pure `#FFFFFF` canvas.
- **Layer 1 (Card & Well):** Solid `#F5F5F7` filled containers. Zero border strokes; edge definition occurs entirely through the shift from pure white to off-white.
- **Layer 2 (Floating Action Bars & Overlays):** Translucent `#FFFFFF` with `backdrop-filter: blur(20px)` and an ambient shadow (`0 8px 32px rgba(0, 0, 0, 0.04)`). Used only for sticky navigation and bottom checkout drawers.

## Shapes
The structural geometry is unified around gentle, fluid curvatures:

- **Cards & Sheets:** Fixed at `18px` (`rounded-2xl` equivalent) with continuous corner curves to evoke precision-milled hardware aesthetics.
- **Interactive Targets (Buttons, Tags, Form Fields):** Fully rounded pill geometry (`9999px`), creating immediate visual affordance and soft interaction surfaces.
- **Sub-elements:** Product thumbnails and internal media nests utilize `12px` border radii to sit harmoniously within parent containers.

## Components

### Buttons
- **Primary:** Full pill (`border-radius: 9999px`), solid `#0071E3` fill, white `#FFFFFF` text in `label-lg`, zero border, 48px minimum height for touch accessibility. Hover/Press state adjusts to `#0077ED` with a smooth `scale(0.98)` tactile transform.
- **Secondary / Ghost:** Full pill, `#F5F5F7` fill with `#1D1D1F` text. Active state dims to `#E8E8ED`.
- **Text Action:** Inline `#0071E3` label accompanied by a subtle directional chevron; no background pill.

### Cards
- **Product Card:** Surface `#F5F5F7`, radius `18px`, 20px uniform internal padding. Pure white PNG or transparent appliance photography positioned centrally. Titles use `headline-sm`, subtitle/spec details use `body-sm` (`#6E6E73`), followed by clean price display. No promotional banners, tags, or rating stars.

### Chips & Filters
- **Filter Chip:** Pill-shaped (`border-radius: 9999px`), height 36px, horizontal padding 16px. Inactive state: `#F5F5F7` with `#1D1D1F` text. Active state: `#1D1D1F` background with `#FFFFFF` text.

### Form Fields & Inputs
- **Text Input:** Pill-shaped or 18px rounded surface, height 52px, filled with `#F5F5F7`, zero border. Placeholder text in `#6E6E73`. Focus state introduces a refined 2px solid `#0071E3` outer ring with zero shadow offset.

### Selection Controls
- **Radio & Switches:** Smooth mechanical switches with `#E8E8ED` track transitioning to `#0071E3` on active state; pure white circular thumb with ultra-soft ambient shadow (`0 2px 4px rgba(0,0,0,0.1)`).

### Bottom Sticky Bar (Mobile Checkout)
- **Container:** Grounded fixed bar with frosted `#FFFFFF` backing (`backdrop-filter: blur(20px)`), containing total price (`headline-sm`) and full-width pill primary button (`#0071E3`) for friction-free purchasing.