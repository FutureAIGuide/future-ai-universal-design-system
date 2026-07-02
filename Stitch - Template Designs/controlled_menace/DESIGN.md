---
name: Controlled Menace
colors:
  surface: '#1e100b'
  surface-dim: '#1e100b'
  surface-bright: '#47352f'
  surface-container-lowest: '#180b07'
  surface-container-low: '#271813'
  surface-container: '#2b1c17'
  surface-container-high: '#372621'
  surface-container-highest: '#42312b'
  on-surface: '#f9dcd4'
  on-surface-variant: '#e3bfb3'
  inverse-surface: '#f9dcd4'
  inverse-on-surface: '#3d2c27'
  outline: '#aa897f'
  outline-variant: '#5b4138'
  surface-tint: '#ffb59c'
  primary: '#ffb59c'
  on-primary: '#5c1900'
  primary-container: '#ff5f1f'
  on-primary-container: '#561700'
  inverse-primary: '#ab3600'
  secondary: '#9de32e'
  on-secondary: '#213600'
  secondary-container: '#83c600'
  on-secondary-container: '#314d00'
  tertiary: '#8dcdff'
  on-tertiary: '#00344f'
  tertiary-container: '#009de4'
  on-tertiary-container: '#00304a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcf'
  primary-fixed-dim: '#ffb59c'
  on-primary-fixed: '#390c00'
  on-primary-fixed-variant: '#832700'
  secondary-fixed: '#b0f743'
  secondary-fixed-dim: '#95da24'
  on-secondary-fixed: '#111f00'
  on-secondary-fixed-variant: '#324f00'
  tertiary-fixed: '#cae6ff'
  tertiary-fixed-dim: '#8dcdff'
  on-tertiary-fixed: '#001e30'
  on-tertiary-fixed-variant: '#004b70'
  background: '#1e100b'
  on-background: '#f9dcd4'
  surface-variant: '#42312b'
  fg-canvas: '#050505'
  fg-surface: rgba(255, 255, 255, 0.04)
  fg-surface-md: rgba(255, 255, 255, 0.06)
  fg-border: rgba(255, 255, 255, 0.08)
  fg-border-md: rgba(255, 255, 255, 0.14)
  fg-text-1: '#f5f5f5'
  fg-text-2: rgba(245, 245, 245, 0.64)
  fg-text-3: rgba(245, 245, 245, 0.42)
  fg-orange-lt: '#ff7a45'
  fg-orange-dk: '#d9480f'
  fg-amber: '#f59e0b'
  fg-rust: '#ff4444'
  fg-neutral-85: '#1a1a1a'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  display-md:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.35'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 19px
    fontWeight: '600'
    lineHeight: '1.35'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.5'
  mono-data:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  section-label:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.1em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  '1': 4px
  '2': 8px
  '3': 12px
  '4': 16px
  '6': 24px
  '8': 32px
  '12': 48px
  '16': 64px
  '20': 80px
---

## Brand & Style

This design system is engineered for an investigative AI intelligence network. The brand personality is **Professional, Cold, and Investigative**, characterized by a "controlled menace" aesthetic—a precise, data-driven atmosphere that prioritizes technical credibility over decorative flair.

The visual style leverages **Minimalism** combined with **Glassmorphism** to create a premium, high-density information environment. It draws inspiration from intelligence interfaces and financial terminals, favoring deep black canvases and high-contrast functional accents. Every design decision serves the narrative of "admissible evidence," ensuring that the UI feels authoritative, structured, and immune to superficial trends.

## Colors

The palette is built on a "Black Foundation." We use `#050505` as the primary canvas to ensure deep blacks that allow translucent glass surfaces to appear meaningful.

- **Primary (Action/Urgency):** `#ff5f1f` (Orange) is reserved for critical CTAs, active states, and high-priority alerts.
- **Secondary (Trust/Verification):** `#a3e935` (Lime) is used exclusively for verified signals and trusted data points.
- **Neutral/Surface:** A tiered system of semi-transparent whites (`rgba`) creates depth without introducing new hues.
- **Functional Accents:** Amber is used for investigation states; Rust is utilized for breaking news and critical system errors.

## Typography

This design system employs a tri-font strategy to distinguish between editorial authority, standard communication, and technical data.

- **Space Grotesk:** Used for all headings. Its geometric precision conveys a modern, institutional authority.
- **Inter:** The workhorse for body copy, chosen for its exceptional legibility in dark mode and high-density layouts.
- **JetBrains Mono:** Used for metadata, technical classifications, and labels. It reinforces the "investigative" feel of the platform.

Large display type should be tightly tracked to maintain the "controlled" visual tone. Labels should always be in Mono and uppercase when used as section descriptors.

## Layout & Spacing

The system is built on a strict **4px base unit**. We utilize an editorial spacing scale that alternates between "dense data clusters" and "massive editorial gaps" to create rhythm.

- **Grid Model:** 12-column fluid grid for desktop with 24px gutters.
- **Margins:** 64px on desktop, scaling down to 16px on mobile.
- **Logic:** Internal component spacing uses the lower end of the scale (4px–16px), while layout sectioning uses the upper end (48px–80px) to provide focus. 

Mobile layouts collapse into a single-column stack with increased vertical padding to maintain the "premium" feel on smaller viewports.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Glassmorphism**. We avoid traditional drop shadows in favor of surface luminosity.

- **The Base:** The canvas is always `#050505`.
- **Surfaces:** Floating panels use `backdrop-filter: blur(12px)` and a semi-transparent background (`fg-surface`).
- **Borders:** Surfaces are defined by subtle 1px outlines (`fg-border`). 
- **Shadows:** Use shadows sparingly as glows rather than depth indicators. `shadow-orange` and `shadow-lime` are used to indicate active "power-on" states for critical UI elements.
- **Hierarchy:** Elements higher in the stack use slightly more opaque backgrounds (`fg-surface-md`).

## Shapes

The shape language is **Soft (r-md)** but restrained. We use rounded corners to provide a "finished" feel to high-tech components without making them appear playful.

- **r-sm (4px):** Micro-elements, checkboxes, and nested inputs.
- **r-md (8px):** Standard buttons and small card components.
- **r-lg (16px):** Primary content containers and investigation cards.
- **r-full:** Reserved strictly for status badges and pill-style tags.

Vertical "Status Stripes" (3px width) are used on the left or top edge of cards to indicate classification without coloring the entire surface.

## Components

### Navigation Header
- **Style:** Sticky, full-width with `backdrop-filter: blur(20px)`.
- **Border:** 1px bottom border using `fg-border`.
- **Links:** JetBrains Mono, uppercase, `text-3` default, `text-1` hover.

### Investigation Cards
- **Structure:** 1px border (`fg-border`) with a 3px top "Status Stripe" (Orange, Lime, or Rust).
- **Content:** Headline LG for titles, Mono for metadata strings.
- **Interactive:** Slight increase in surface opacity on hover.

### Buttons
- **Primary:** Solid `fg-orange` background, black text, `shadow-orange` glow on hover.
- **Secondary:** Transparent background, 1px `fg-border-md` stroke, white text.
- **Ghost:** No background or border, `fg-text-2` color, transitions to `fg-text-1` with a subtle background tint.

### Status Badges
- **Style:** Pill-shaped (`r-full`), Mono font, extra-small tracking.
- **Verified:** Lime text, dark lime 10% opacity background.
- **Breaking:** Rust text, dark rust 10% opacity background.

### Input Fields
- **Style:** Deep black background (`#000000`), 1px `fg-border` stroke.
- **Focus State:** Stroke changes to `fg-orange` with a 2px inner glow.