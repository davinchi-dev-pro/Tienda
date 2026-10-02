---
name: Apex Recharge LatAm
colors:
  surface: '#0b1229'
  surface-dim: '#0b1229'
  surface-bright: '#323851'
  surface-container-lowest: '#060d24'
  surface-container-low: '#141a32'
  surface-container: '#181e36'
  surface-container-high: '#222941'
  surface-container-highest: '#2d344c'
  on-surface: '#dce1ff'
  on-surface-variant: '#bbc9cf'
  inverse-surface: '#dce1ff'
  inverse-on-surface: '#292f48'
  outline: '#859399'
  outline-variant: '#3c494e'
  surface-tint: '#47d6ff'
  primary: '#a5e7ff'
  on-primary: '#003543'
  primary-container: '#00d2ff'
  on-primary-container: '#00566a'
  inverse-primary: '#00677f'
  secondary: '#b7c4ff'
  on-secondary: '#002682'
  secondary-container: '#0052fe'
  on-secondary-container: '#dfe3ff'
  tertiary: '#ffd1de'
  on-tertiary: '#640036'
  tertiary-container: '#ffa8c6'
  on-tertiary-container: '#9c0057'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b6ebff'
  primary-fixed-dim: '#47d6ff'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e60'
  secondary-fixed: '#dde1ff'
  secondary-fixed-dim: '#b7c4ff'
  on-secondary-fixed: '#001452'
  on-secondary-fixed-variant: '#0038b6'
  tertiary-fixed: '#ffd9e3'
  tertiary-fixed-dim: '#ffb0ca'
  on-tertiary-fixed: '#3e001f'
  on-tertiary-fixed-variant: '#8d004e'
  background: '#0b1229'
  on-background: '#dce1ff'
  surface-variant: '#2d344c'
typography:
  display-hero:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-md:
    fontFamily: Sora
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-sm:
    fontFamily: Sora
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-numeric:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '800'
    lineHeight: 24px
    letterSpacing: 0.02em
  label-tag:
    fontFamily: Sora
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  label-action:
    fontFamily: Sora
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system drives a premium, hyper-responsive digital top-up experience for competitive mobile gamers across Latin America, specifically tailored to the fast-paced culture of Free Fire players in Colombia. The atmosphere balances tactical esports precision with the adrenaline rush of live gaming drop events. It is built to elicit immediate trust, speed, security, and prestige.

The design movement combines **Cyber-Tactical Glassmorphism** with **High-Contrast Neon Precision**:
- Surfaces are deep, cold obsidian and navy voids punctuated by energized electric cyan and laser blue lines.
- Translucent layered cards mimic holographic battle HUDs, optimized for fast checkout flows under high mobile traffic.
- Micro-interactions emit reactive glows, reinforcing transactional velocity and instant delivery confidence.
- Trust cues (instant diamond delivery badges, regional payment credentials like Nequi and PSE) are stylized as native tactical certifications rather than external enterprise marks.

## Colors

The palette is engineered around pure dark mode dominance, utilizing deep oceanic slates to maximize the visual punch of electric luminescent accents.

- **Primary (`#00d2ff` - Cyan Strike)**: The focal beacon. Represents diamond currency, interactive affordances, active recharge states, and positive confirmations. Used for primary CTAs, glowing package borders, and dynamic currency readouts.
- **Secondary (`#0052ff` - Apex Blue)**: Structural reinforcement. Governs primary container gradients, secondary actions, active tabs, and tactical structural highlights.
- **Tertiary (`#ff1493` - Neon Magenta / Nequi Accent)**: High-voltage callout color used specifically for local payment integration badges (Nequi, instant promotions, flash discounts, and limited-time bonus chips). Contrasts sharply against the cyan foundation.
- **Neutral Base (`#0a1128` - Deep Abyssal Navy)**: Root canvas backdrop. Extended by `#101c3d` for elevated cards and `#050814` for sunken input wells.
- **Surface Accent Tokens**:
  - `surface-glass`: `rgba(16, 28, 61, 0.65)` with a `16px` blur filter.
  - `border-tactical`: `rgba(0, 210, 255, 0.2)` resting, transitioning to `rgba(0, 210, 255, 0.8)` on hover/focus.
  - `text-high-contrast`: `#ffffff` for optimal readouts on OLED mobile displays.
  - `text-subtle`: `#8a9bb8` for meta descriptions, rates, and platform timestamps.

## Typography

Typography establishes an assertive visual rhythm. Sora provides geometric, high-tech angularity across headlines, conversion labels, currency quantities, and tactical markers. Inter handles data entry, user identity fields (Player ID), legal guarantees, and transactional breakdown lines with pristine utilitarian legibility.

All diamond amounts and pricing tags leverage `label-numeric` set in Sora with tabular numerical alignment to eliminate jitter when updating recharge packages. Badges, tags, and promotional ribbons use `label-tag` set to uppercase for military HUD telemetry aesthetics.

## Layout & Spacing

The layout model is a modular, fluid 12-column grid on desktop collapsing to a dense 4-column structure on mobile devices to preserve thumb-reach efficiency.

- **Mobile Viewport (< 768px)**: 4 columns, `margin: 1rem` (`16px`), `gutter: 1rem` (`16px`). Compact vertical rhythm prioritizes top diamond package tiers with sticky thumb-accessible checkout triggers.
- **Tablet (768px - 1024px)**: 8 columns, `margin: 2rem` (`32px`), `gutter: 1.25rem` (`20px`).
- **Desktop (> 1024px)**: 12 columns, max-width `1280px`, `margin: 3rem` (`48px`), `gutter: 1.5rem` (`24px`).
- **Card Grids**: Diamond bundles use auto-fit CSS grids collapsing from 4 columns (desktop) to 2 columns (mobile) so packages remain chunky, touchable, and legible.

## Elevation & Depth

Visual hierarchy does not rely on traditional muddy drop shadows; instead, it utilizes **layered luminescence, neon ambient diffusion, and dark tinted glass panels**.

1. **Base Layer (L0 - Background Canvas)**: `#0a1128` deep navy matte canvas with faint radial gradient spotlights behind active selection tiers.
2. **Surface Layer (L1 - Resting Panels & Forms)**: Solidified `#101c3d` or glassmorphic `rgba(16, 28, 61, 0.75)` with `1px` inner border `rgba(255, 255, 255, 0.08)` and `backdrop-filter: blur(12px)`.
3. **Elevated Layer (L2 - Selected Bundle / Interactive Hover)**: Background shifts to `linear-gradient(180deg, rgba(0, 82, 255, 0.2) 0%, rgba(16, 28, 61, 0.9) 100%)`, outlined with a 1px border of `#00d2ff`. Shadow: `0 0 24px -4px rgba(0, 210, 255, 0.45)`.
4. **Overlay Layer (L3 - Modal Dialogs & Sticky Checkout Bar)**: `#0d1733` with `backdrop-filter: blur(20px)`, top-edged with an energetic `1px` beam of `linear-gradient(90deg, transparent, #00d2ff, transparent)`, paired with `0 20px 40px rgba(0, 0, 0, 0.8)`.

## Shapes

The system uses crisp, technical chamfers and low-radius curves (Level 1: Soft), steering clear of overly bubbly, casual interfaces in favor of angular esports gear.

- Standard interactive components and utility cards feature `0.25rem` (`4px`) to `0.5rem` (`8px`) outer corner curvature.
- Badges, status pills, and tactical flags retain precise, compact boundaries (`0.25rem` radius or pure clipped HUD corners).
- Package selector cards utilize micro-corner accents to resemble high-tech inventory cartridges.

## Components

### Buttons
- **Primary Action (Instant Top-Up)**: Background in continuous horizontal gradient `linear-gradient(90deg, #0052ff 0%, #00d2ff 100%)`. High-contrast pure white uppercase Sora bold text, subtle letter spacing. Box shadow: `0 0 20px rgba(0, 210, 255, 0.4)`. When active/pressed, scale down to `0.98` with enhanced core brightness.
- **Secondary (Player ID Check / Methods)**: Semi-transparent background `rgba(0, 210, 255, 0.08)`, border `1px solid rgba(0, 210, 255, 0.3)`, text `#00d2ff`. Hover shifts border to `1px solid #00d2ff` with a localized aura.

### Diamond Bundle Cards
- Rectangular modular format with an integrated diamond crystal asset slot.
- Top right incorporates an absolute-positioned promotional chip.
- Resting state: Dark glass backdrop, fine-line border `rgba(255, 255, 255, 0.08)`.
- Selected state: Cyan border `#00d2ff`, subtle internal cyan radial wash, glowing outer halo. Displays both nominal diamond count and dynamic bonus values (+10% Bonus) in high-contrast cyan.

### Chips & Badges
- **Nequi / Colombian Regional Badges**: Hot magenta accent `#ff1493` pill, text pure white, icon of payment network alongside `SIN COMISIÓN` or `INSTANTÁNEO` tags.
- **Discount & Bonus Chips**: Sharp-cornered neon badges placed on the top border of bundle cards with electric gradient backgrounds, uppercase 11px Sora typography.
- **Trust & Verification Badges**: Shield or verified check mark with label `ID VERIFICADO` using `#00d2ff` tinted glass styling.

### Input Fields (Free Fire UID Entry)
- Deep sunken navy containers (`#050814`) with a rigid `1px` border of `rgba(255, 255, 255, 0.15)`.
- Large, high-visibility input characters with `label-numeric` formatting.
- Integrated validation indicator on the right edge: flashes a pulsing neon cyan checkmark badge once the Free Fire nickname is queried and verified.

### Payment Selection Radio Grid
- Horizontal cards featuring major Colombian payment channels (Nequi, DaviPlata, PSE, Bancolombia, Cash/Efecty).
- Selected payment channel displays an active cyan outer boundary and a lit-up selector bead on the upper-right corner.