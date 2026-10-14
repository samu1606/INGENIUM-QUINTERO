---
name: Ingenium Quintero
colors:
  surface: '#f8f9fe'
  surface-dim: '#d9dadf'
  surface-bright: '#f8f9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f8'
  surface-container: '#edeef3'
  surface-container-high: '#e7e8ed'
  surface-container-highest: '#e1e2e7'
  on-surface: '#191c1f'
  on-surface-variant: '#3b4a3f'
  inverse-surface: '#2e3134'
  inverse-on-surface: '#f0f0f5'
  outline: '#6b7b6e'
  outline-variant: '#b9cbbc'
  surface-tint: '#006d3f'
  primary: '#006d3f'
  on-primary: '#ffffff'
  primary-container: '#26ff9d'
  on-primary-container: '#007242'
  inverse-primary: '#00e389'
  secondary: '#006971'
  on-secondary: '#ffffff'
  secondary-container: '#46effe'
  on-secondary-container: '#006a71'
  tertiary: '#725c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffdd70'
  on-tertiary-container: '#776000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#57ffa6'
  primary-fixed-dim: '#00e389'
  on-primary-fixed: '#00210f'
  on-primary-fixed-variant: '#00522e'
  secondary-fixed: '#83f3ff'
  secondary-fixed-dim: '#1fdbea'
  on-secondary-fixed: '#002023'
  on-secondary-fixed-variant: '#004f55'
  tertiary-fixed: '#ffe081'
  tertiary-fixed-dim: '#e4c45a'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#564500'
  background: '#f8f9fe'
  on-background: '#191c1f'
  surface-variant: '#e1e2e7'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-xl:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
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
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  code-mono:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style
The design system articulates an architectural, ultra-clean editorial tech aesthetic tailored for an enterprise AI and business automation agency. It conveys intelligent restraint, structural precision, and frictionless leverage. 

The emotional signature is airy, confident, and luminous—avoiding heavy cyberpunk darkness or aggressive novelty in favor of light-drenched executive clarity. The visual language blends Swiss modernist grid discipline with soft-tech dimensionality: ample negative space, bento-grid modules, soft atmospheric gradients, generous radii, and micro-precision line detailing. Photography is strictly eschewed; visual proof is supplied via interactive bento previews, abstract topological workflows, precision metric badges, and mathematical telemetry graphs.

## Colors
The color foundation relies on high-luminance layering, grounded by deep structural ink tones and activated by hyper-modern luminous accents.

- **Canvas & Gradients:** The baseline canvas rests on `#f6f8fb` (cool near-white). The hero background employs an atmospheric wash flowing from `#eaf4ff` (soft sky) to `#ffffff`.
- **Surfaces:** Floating cards, modal sheets, and bento components use pure `#ffffff` layered over the `#f6f8fb` base to produce clean, sharp contrast. Borders utilize an exacting `#e2e8f0`.
- **Typography:** Display, titles, and high-impact counters use deep ink `#05070a`. Secondary text and long-form narrative use a disciplined cool slate `#55617a`. Muted hints, metadata, and timestamps sit on `#8c9bb0`.
- **Accents:** 
  - *Primary Accent (`#26ff9d` Fresh Mint):* Reserved for primary high-conversion call-to-actions, live status nodes, and metric highlights. Must pair with `#05070a` ink typography for accessible, striking contrast.
  - *Secondary Accent (`#00d4e3` Soft Electric Cyan):* Used selectively for automation data streams, connection wires, subtle gradient borders, and visual anchors.

## Typography
The typographic system pairs the structural, idiosyncratic geometry of Space Grotesk for architectural headlines with the utilitarian legibility of Inter for body copy. Plus Jakarta Sans serves as an expressive, high-legibility interface font for pill badges, buttons, and navigation nodes.

Headings leverage tight negative letter-spacing to emphasize authority and tension, while body text uses a relaxed 1.6-to-1.65 line-height ratio to preserve the airy feel of the editorial grid. Numbers inside metrics or analytical dashboards always use tabular lining figures to maintain column alignment.

## Layout & Spacing
The layout system is founded on a 12-column responsive fluid grid structured around modular bento layouts. 

- **Desktop (>= 1280px):** 12-column layout, max-width `1280px` or `1440px` for wide hero canvases, `5rem` page margins, `2rem` column gutters. Section padding utilizes generous `space-3xl` (96px) to maintain the airy editorial baseline.
- **Tablet (768px - 1279px):** 8-column layout, `2.5rem` margins, `1.5rem` gutters. Bento cards collapse into dual-column modules.
- **Mobile (< 768px):** 4-column layout, `1.25rem` margins, `1rem` gutters. Stacks vertically with zero horizontal horizontal clipping; cards maintain full-width spans.

The vertical rhythm is intentional: dense, micro-spaced clusters inside cards (`space-xs` through `space-md`) stand in high contrast to the generous negative spacing between bento structures and page sections (`space-2xl` and `space-3xl`).

## Elevation & Depth
Elevation mimics clean architectural planes suspended in atmospheric light. Shadows are extra-diffused, cool-tinted, and decoupled from archaic dark drop-shadows.

- **Level 0 (Canvas Base):** Flat `#f6f8fb` background with no elevation.
- **Level 1 (Bento Surfaces & Cards):** Pure `#ffffff` surface, bounded by an exact `1px solid #e2e8f0` border, resting on an ambient diffuse shadow: `0 12px 32px -4px rgba(16, 24, 40, 0.06), 0 4px 12px -2px rgba(16, 24, 40, 0.02)`.
- **Level 2 (Interactive Floating Hero / Modals / Active Flyouts):** Suspended high above the canvas: `0 24px 48px -12px rgba(16, 24, 40, 0.10), 0 8px 16px -4px rgba(16, 24, 40, 0.04)`.
- **Glassmorphic Floating Bars (Nav & Sticky Action Bars):** Translucent white surface `rgba(255, 255, 255, 0.82)` with `backdrop-filter: blur(16px)` and a hairline border `rgba(226, 232, 240, 0.80)`.

## Shapes
The shape philosophy employs hyperbolic, sweeping curves combined with strict interior lines. Outer card surfaces embrace sweeping `rounded-2xl` (1.5rem / 24px) or `rounded-3xl` (2rem / 32px) silhouettes, conveying friendly digital tactility and high polish.

Interactive controls (buttons, badges, pills, search bars, category tags) are strictly pill-shaped (`rounded-full` / 9999px). Sub-containers and nested analytical chips within bento boxes scale down harmoniously to `rounded-lg` (0.75rem / 12px) to guarantee optical balance.

## Components

- **Buttons:**
  - *Primary Pill Button:* Background `#26ff9d`, text `#05070a`, font `Plus Jakarta Sans` semi-bold. Height 48px (desktop) / 44px (mobile), horizontal padding 28px, full pill curve. Hover state subtle translate `translate-y-[-1px]` with soft glow `0 8px 24px -2px rgba(38, 255, 157, 0.35)`.
  - *Secondary Pill Button:* Background `#ffffff`, text `#05070a`, border `1px solid #e2e8f0`. Hover adds subtle border darken to `#cbd5e1` and minimal ambient lift.
  - *Ghost / Tertiary Button:* Transparent background, text `#55617a`, hover color `#05070a` accompanied by an animated line-art arrow icon sliding 4px right.

- **Bento Cards & Surfaces:**
  - Constructed with `rounded-3xl`, background `#ffffff`, border `1px solid #e2e8f0`, diffuse ambient shadow.
  - Features internal padding of `space-xl` (2.5rem). Bento blocks group automation metrics, dynamic workflow trees, and operational statistics.

- **Badges & Chips:**
  - Pill-shaped (`rounded-full`), height 28px, padding 4px 12px.
  - *Mint Status Badge:* Background `rgba(38, 255, 157, 0.15)`, text `#05070a`, accompanied by a solid `#26ff9d` 6px pulsating dot.
  - *Neutral Metric Chip:* Background `#f1f5f9`, text `#55617a`, border `1px solid #e2e8f0`.

- **Input Fields:**
  - Full pill or `rounded-2xl` container, pure `#ffffff` fill, border `1px solid #e2e8f0`, text `#05070a`, placeholder `#8c9bb0`.
  - Focus state applies a crisp outline: `border-color: #00d4e3` with an outer glow `0 0 0 3px rgba(0, 212, 227, 0.15)`.

- **Checkboxes & Radios:**
  - Checkboxes use `rounded-md` (6px) with an unselected `#e2e8f0` border. Active state fills with `#05070a` housing a pure white checkmark.
  - Radio buttons use concentric circles with a `#26ff9d` active core.

- **Iconography & Visual Assets:**
  - Strictly monochrome line-style icons (stroke-width: 1.5px, rounded caps). Never solid colored or decorative multi-tone.
  - Zero stock photography. Data diagrams, automation pipeline schema lines, and topological UI wireframes represent product capabilities.