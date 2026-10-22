---
name: Atelier Obsidian
colors:
  surface: '#131317'
  surface-dim: '#131317'
  surface-bright: '#39393d'
  surface-container-lowest: '#0e0e12'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#2a292e'
  surface-container-highest: '#353439'
  on-surface: '#e4e1e7'
  on-surface-variant: '#d4c4b0'
  inverse-surface: '#e4e1e7'
  inverse-on-surface: '#303034'
  outline: '#9d8f7c'
  outline-variant: '#504535'
  surface-tint: '#fabc4d'
  primary: '#ffc665'
  on-primary: '#432c00'
  primary-container: '#e5a93c'
  on-primary-container: '#5e4000'
  inverse-primary: '#7e5700'
  secondary: '#ddb8ff'
  on-secondary: '#490081'
  secondary-container: '#62259b'
  on-secondary-container: '#d1a1ff'
  tertiary: '#ffc57e'
  on-tertiary: '#472a00'
  tertiary-container: '#f8a111'
  on-tertiary-container: '#643d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdead'
  primary-fixed-dim: '#fabc4d'
  on-primary-fixed: '#281900'
  on-primary-fixed-variant: '#604100'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb8ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#62259b'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#131317'
  on-background: '#e4e1e7'
  surface-variant: '#353439'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-lg: 2.5rem
  margin: 1.5rem
  margin-md: 3rem
  margin-lg: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system embodies the dark studio aesthetic: an intimate, spotlight-lit private salon tailored for premier fine artists, sculptors, and digital creators. The atmosphere mirrors an exclusive after-hours gallery viewing—quiet, contemplative, and cinematic. The interface recedes entirely, treating the canvas as sacred physical space where artworks function as the primary light sources.

The target audience bridges two worlds: discerning art collectors, curators, and institutional buyers seeking an uncompromised viewing environment, alongside visionary artists managing high-value inventory, provenance, and private client viewing rooms.

The design movement synthesizes **Minimalism** with subtle **Glassmorphism** and cinematic chiaroscuro. Deep obsidian layers, ultra-fine hair-thin borders, and selective luminous amber-violet accents create an understated architectural tension, evoking reverence, prestige, and laser-focused attention on visual crafts.

## Colors

The palette operates under a strict luminance hierarchy grounded in deep midnight obsidian values, minimizing eye fatigue during long cataloguing sessions while granting high contrast to visual media:

- **Canvas & Backgrounds:** Base obsidian `#0a0a0c` anchors the overall viewport. Layered surfaces graduate softly into charcoal `#121216` (containers and side rails) and elevated midnight slate `#1a1a22` (interactive modals and floating viewports).
- **Primary Accent (`#e5a93c`):** An incandescent gallery amber reminiscent of focused museum halogen spotlights. Applied sparingly to primary calls-to-action, active curation states, and certification seals.
- **Secondary Accent (`#c084fc`):** An ethereal violet-orchid hue reserved for private studio indications, edition tiers, and specialized metadata tags.
- **Tertiary Accent (`#f59e0b`):** A warm radiant gold used for alerts, price markers, and interactive hover highlights.
- **Neutrals & Borders:** Foreground typography scales from pure pearl `#f4f4f6` down to muted gallery mist `#9494a0`. Structural delineation strictly utilizes subtle ghost borders (`rgba(255, 255, 255, 0.07)` on resting surfaces, warming to `rgba(229, 169, 60, 0.25)` on active focus states).

## Typography

The typographical tension pairing editorial luxury with modernist clarity drives the platform's visual maturity:

- **Artistic Titles & Headlines (Playfair Display):** Conveys the intellectual heritage of traditional monographs and exhibition catalogs. Used for series titles, artwork naming, curatorial statements, and top-level portfolio milestones. Large-scale headings employ delicate negative tracking to maintain tight, sculpted visual density.
- **Interface & Administrative Body (Plus Jakarta Sans):** Selected for its geometric clarity, tall x-height, and neutral precision. Powers metadata panels, pricing schedules, provenance logs, and gallery management controls.
- **Labeling & Metadata (`label-caps`):** Rendered in uppercase with generous letter tracking (`0.08em`) to mimic archival plate stampings and gallery accession numbers.

## Layout & Spacing

The layout treats negative space as an intentional framing device rather than mere separation. It uses a 12-column adaptive grid that shifts dynamically between museum showcase layouts and dense workspace matrices:

- **Desktop (1200px+):** 12-column grid with `gutter-lg` (2.5rem) and `margin-lg` (5rem). Art presentation views utilize fluid horizontal margins to isolate single masterpieces or structured asymmetrical salon walls. Admin consoles snap to a fixed-width 1440px container with rigid metadata columns.
- **Tablet (768px – 1199px):** 8-column grid with `gutter` (1.5rem) and `margin-md` (3rem). Visual media scales while preserving aspect ratio, shifting curation metadata beneath the media viewport.
- **Mobile (<768px):** 4-column architecture with 1rem gutters and `margin` (1.5rem). Work displays collapse into single-column vertical scrolls with edge-to-edge asset bleed, anchoring management actions to a persistent bottom drawer.

## Elevation & Depth

Visual hierarchy does not rely on harsh drop shadows; instead, it utilizes translucent physical strata and directional lighting techniques:

- **Level 0 (Canvas Base):** Ground-level `#0a0a0c`. Completely matte, absorbent, and non-reflective.
- **Level 1 (Surface Glass):** Resting cards, side panels, and listing blocks built with `#121216` at 70% opacity, paired with a `backdrop-filter: blur(16px)` and a subtle ambient rim highlight: `border: 1px solid rgba(255, 255, 255, 0.06)`.
- **Level 2 (Active Overlays & Modals):** Floating inspection loupes, private viewing room dialogs, and inventory drawers use `#1a1a22` at 85% opacity, `backdrop-filter: blur(24px)`, and an extra-diffused warm obsidian shadow: `box-shadow: 0 24px 48px -12px rgba(0, 0, 0, 0.85), 0 0 1px 1px rgba(229, 169, 60, 0.15)`.
- **Spotlight Glow:** High-priority focus targets and selected artworks project a soft, tinted ambient penumbra behind their frames (`box-shadow: 0 0 80px -20px rgba(229, 169, 60, 0.12)`), simulating high-end gallery track lights cutting through darkness.

## Shapes

The design system enforces architectural crispness using soft, subtle radii (level `1`). Curatorial tools and fine-art interfaces demand precision; overly rounded forms soften the serious tone of investment-grade art:

- **Cards & Media Frames:** Scaled strictly with `rounded-sm` (0.25rem / 4px) to `rounded-lg` (0.5rem / 8px). Works of art maintain clean, crisp rectilinearity without aggressive clipping of painting corners.
- **Buttons & Control Elements:** 4px radius across administrative toggles, table rows, and interactive buttons, maintaining structural harmony with picture frames and provenance sheets.
- **Pill Exception:** Status indicators (e.g., "Available", "Acquired", "In Exhibition") and filter chips uniquely adopt full pill geometries to contrast sharply against geometric media boundaries.

## Components

### Buttons
- **Primary Action (Spotlight Button):** Solid amber background (`#e5a93c`) with obsidian text (`#0a0a0c`), font weight 600. Minimal hover transformation introducing an exterior glow: `box-shadow: 0 0 20px rgba(229, 169, 60, 0.35)`.
- **Secondary (Ghost Obsidian):** Transparent fill with a delicate `1px solid rgba(255, 255, 255, 0.12)` border. On hover, background transitions to `rgba(255, 255, 255, 0.05)` and border warms to `#e5a93c`.
- **Destructive/Deselect:** Subtle slate background with muted crimson text (`#f87171`), avoiding jarring neon red alerts.

### Cards & Showcase Tiles
- **Artwork Showcase Tile:** Zero visible resting outer container; artwork occupies full space with an imperceptible `1px inner stroke` to preserve edges of pure black images. On hover, a 16px frosted metadata scrim fades into the bottom third revealing title, year, medium, and availability.
- **Admin Metric Card:** Dark glass (`rgba(18, 18, 22, 0.65)`), subtle top-border accent with 10% opacity amber/violet gradient, compact numeric data in `Plus Jakarta Sans`, and tiny uppercase captions.

### Form Inputs & Selectors
- **Text Inputs:** Recessed obsidian fields (`#0a0a0c`) with `1px solid rgba(255, 255, 255, 0.08)`. Placeholder text in muted slate (`#666672`). Focus elevates border to `#e5a93c` with zero harsh outline offsets.
- **Select Menus & Dropdowns:** Translucent panels with background blur, active item highlighted with an amber left edge line (`2px solid #e5a93c`) and faint surface wash.

### Chips & Badges
- **Status Chips:** High-density, reduced padding (4px 10px), uppercase `label-caps` typography. "Available" renders with an amber border and translucent warm fill; "Private Collection" adopts secondary violet accents (`rgba(192, 132, 252, 0.1)`).

### Selection Controls (Checkboxes & Radios)
- Custom square checkboxes with 2px radius and circular radios. Resting state uses a charcoal background with a hairline border. Checked state transitions to solid `#e5a93c` with an obsidian indicator mark.

### Domain-Specific Components
- **Curatorial Lightbox:** Full-viewport modal with `#070709` deep backdrop at 95% opacity, intuitive pan-and-zoom controls, and hideable contextual sidebar detailing exhibition history, dimensions, and high-resolution provenance certificates.
- **Edition & Inventory Split-List:** Two-tiered row layout featuring batch select, thumbnail preview, physical location tracking tag, acquisition status, and instant inline price adjustments.