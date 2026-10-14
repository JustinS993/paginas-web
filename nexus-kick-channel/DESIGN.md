---
name: Obsidian Voltage
colors:
  surface: '#111415'
  surface-dim: '#111415'
  surface-bright: '#373a3b'
  surface-container-lowest: '#0c0f10'
  surface-container-low: '#191c1d'
  surface-container: '#1d2021'
  surface-container-high: '#272a2b'
  surface-container-highest: '#323536'
  on-surface: '#e1e3e4'
  on-surface-variant: '#bbccb0'
  inverse-surface: '#e1e3e4'
  inverse-on-surface: '#2e3132'
  outline: '#86957c'
  outline-variant: '#3d4b35'
  surface-tint: '#44e400'
  primary: '#ebffdc'
  on-primary: '#0b3900'
  primary-container: '#53fc18'
  on-primary-container: '#1d7000'
  inverse-primary: '#1c6d00'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#fff7f6'
  on-tertiary: '#670020'
  tertiary-container: '#ffd1d5'
  on-tertiary-container: '#c10043'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7bff51'
  primary-fixed-dim: '#44e400'
  on-primary-fixed: '#042100'
  on-primary-fixed-variant: '#135200'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#ffb2ba'
  on-tertiary-fixed: '#400011'
  on-tertiary-fixed-variant: '#910030'
  background: '#111415'
  on-background: '#e1e3e4'
  surface-variant: '#323536'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '900'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Montserrat
    fontSize: 30px
    fontWeight: '900'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 26px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '800'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '800'
    lineHeight: 18px
    letterSpacing: 0.06em
  label-md:
    fontFamily: Montserrat
    fontSize: 11px
    fontWeight: '800'
    lineHeight: 14px
    letterSpacing: 0.08em
  label-badge:
    fontFamily: Montserrat
    fontSize: 10px
    fontWeight: '900'
    lineHeight: 12px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

The design system projects raw kinetic energy, elite gamer status, and streaming culture dynamism tailored specifically for high-engagement mobile landing environments. It targets Gen Z, competitive gamers, esports enthusiasts, and active community members who expect broadcast-grade fidelity, relentless pace, and unmistakable presence.

The aesthetic fuses **High-Contrast Brutalist Precision** with **Cybernetic Luminance**:
- Obsidian and deep charcoal foundational surfaces establish an immersive nocturnal void.
- Electric neon green puncturing accents serve as hyper-visible beacons for live status, VIP exclusivity, and immediate user conversion.
- Hard geometric precision, tight information density, and focused neon emissive lighting evoke high-performance gaming hardware displays and broadcast production overlays.

## Colors

The palette leverages pure light emitted against near-absolute void to drive immediate focus:

- **Primary (`#53FC18`)**: The signature electric neon green. Reserved strictly for primary action drivers, live broadcasts, active subscriber perks, and glowing edge micro-accents.
- **Secondary (`#00E5FF`)**: Cyan sub-accent representing digital telemetry, VIP/Moderator roles, and interactive links.
- **Tertiary (`#FF3366`)**: High-urgency magenta for alerts, offline status badges, recording indicators, and limited-time drops.
- **Neutral Core**:
  - Background Base: `#0B0E0F` (True Obsidian)
  - Surface Raised / Card Base: `#12171A` (Deep Gunmetal Charcoal)
  - Surface Border / Inset Stroke: `#1F262B` (Subtle boundary line)
  - On-Neutral Primary: `#F3F6F8` (Crisp dynamic off-white for maximum legibility)
  - On-Neutral Dim / Metadata: `#8596A4` (Muted technical slate)

## Typography

The typography pairs the aggressive, wide-stance geometry of **Montserrat** for display headers and tactical badges with the clinical, screen-optimized clarity of **Inter** for descriptions, metadata, and schedule schedules.

- All primary headlines and status badges utilize uppercase transformations to evoke esports broadcast graphics.
- High tracking is enforced on compact labels (`label-md`, `label-badge`) to maintain maximum legibility at miniature mobile sizes.
- Body text retains natural sentence case with comfortable line-heights to contrast sharply against condensed header modules.

## Layout & Spacing

A mobile-first 4-column fluid grid system geared towards compact, vertical scrolling and handheld one-thumb navigation:

- Outer canvas boundary strictly maintains a `1rem` margin on mobile to ensure zero edge clipping while preserving maximum horizontal real estate for streaming feeds and leaderboard cards.
- Internal card padding defaults to `space-md` (`0.75rem`) for compact metrics and `space-lg` (`1.25rem`) for major interactive sections like VIP Perks and Stream Embed preview zones.
- Vertical layout rhythm stacks with strict modular cadence: `space-xl` between logical landing page blocks (Hero -> Live Schedule -> VIP Community -> Social Matrix).

## Elevation & Depth

Visual hierarchy does not use diffuse skeuomorphic dropshadows. Instead, elevation is rendered through **Luminescent Tonal Stratification and Radiance Outlines**:

- **Ground Zero (Base Canvas)**: Pure matte obsidian `#0B0E0F`.
- **Level 1 (Card & Section Containers)**: `#12171A` enclosed in a razor-thin, high-definition 1px border (`#1F262B`).
- **Level 2 (Interactive Modules & Hover Targets)**: `#182024` with a 1px border shifting to `rgba(83, 252, 24, 0.35)`.
- **Neon Emissive Glare**: Reserved exclusively for critical focal points—the primary Follow/Subscribe CTA and the "LIVE NOW" badge. Achieved via dual concentrated glows: `0 0 16px rgba(83, 252, 24, 0.45), 0 0 32px rgba(83, 252, 24, 0.15)`.
- **Floating Overlays**: Bottom sticky CTA bar applies background blur (`backdrop-filter: blur(16px)`) over `rgba(11, 14, 15, 0.85)` with a 1px top divider line in `#1F262B`.

## Shapes

The design system employs a **Soft Technical Chamfer** profile (Level 1 roundedness):
- Base containers, buttons, cards, and input modules feature a compact `0.25rem` (4px) corner radius, preserving an aggressive, tactical hardware feel rather than an organic mobile app appearance.
- Outer container elements use `0.5rem` (`rounded-lg`), maintaining crisp structural cohesion.
- Status pips and online indicator badges retain hard circular shapes (9999px) strictly when functioning as indicator lights.

## Components

### Live Stream Indicator Badge
- **Structure**: Inline pill containing a pulsing signal beacon dot (`#53FC18`) and bold uppercase text "LIVE".
- **Styling**: Background `rgba(83, 252, 24, 0.12)`, border `1px solid #53FC18`, text `#53FC18`.
- **Animation**: Ambient breathing glow box-shadow cycling from `4px` to `12px` spread.

### Primary Follow & Subscribe CTAs
- **Primary CTA**: Background `#53FC18`, foreground `#0B0E0F`, `label-lg` uppercase typography. Zero-radius or micro 4px radius. Intense green glow on focus/active state.
- **Secondary Action (Sub / VIP)**: Deep charcoal background `#12171A`, high-contrast 1px border in `#53FC18`, text `#53FC18`.

### High-Contrast Stream Cards
- Charcoal slate body (`#12171A`) featuring 1px `#1F262B` borders.
- Top-anchored high-resolution stream thumbnail with overlay badges (Viewer count pill in top-left, Live duration in bottom-right).
- Internal content padded at `space-md` featuring high-contrast header and metadata tags.

### VIP Community Perks Matrix
- Grid-aligned compact tiles displaying custom emotes, badge tiers, and sub perks.
- Hover/tap reveals an active neon stroke transition and cyan secondary tag highlights.

### Stream Schedule Table
- Alternating subtle rows (`#12171A` to `#161C20`).
- Left-aligned bold day abbreviation in electric green, centered game category/title, right-aligned localized timestamp in slate monospace-aligned typography.

### Social Matrix & Channel Links
- Horizontal and grid icon blocks featuring prominent brand glyphs with sharp 1px borders, shifting to glowing green fill accents upon interaction.