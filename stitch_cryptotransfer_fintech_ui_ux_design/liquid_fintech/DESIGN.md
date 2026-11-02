---
name: Liquid Fintech
colors:
  surface: '#faf8ff'
  surface-dim: '#d1d8ff'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f2ff'
  surface-container: '#ebedff'
  surface-container-high: '#e4e7ff'
  surface-container-highest: '#dce1ff'
  on-surface: '#0e193d'
  on-surface-variant: '#434656'
  inverse-surface: '#242e53'
  inverse-on-surface: '#eff0ff'
  outline: '#737688'
  outline-variant: '#c3c5d9'
  surface-tint: '#004fe4'
  primary: '#0046cb'
  on-primary: '#ffffff'
  primary-container: '#075bff'
  on-primary-container: '#eaecff'
  inverse-primary: '#b6c4ff'
  secondary: '#274dd7'
  on-secondary: '#ffffff'
  secondary-container: '#4768f1'
  on-secondary-container: '#fffbff'
  tertiary: '#006027'
  on-tertiary: '#ffffff'
  tertiary-container: '#007c34'
  on-tertiary-container: '#b2ffb9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#003baf'
  secondary-fixed: '#dde1ff'
  secondary-fixed-dim: '#b8c3ff'
  on-secondary-fixed: '#001356'
  on-secondary-fixed-variant: '#0035be'
  tertiary-fixed: '#7ffc97'
  tertiary-fixed-dim: '#62df7d'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005320'
  background: '#faf8ff'
  on-background: '#0e193d'
  surface-variant: '#dce1ff'
typography:
  display-hero:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Manrope
    fontSize: 34px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  balance-display:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-pill:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
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
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system embodies a modern, banking-grade financial aesthetic tailored for cross-chain and platform-to-platform digital asset transfers. The brand personality blends institutional reliability with frictionless Web3 agility: confident, pristine, secure, and approachable.

The target audience spans digital asset holders, retail crypto investors, and cross-border remitters who demand effortless execution, crystal-clear fee structures, and immediate transaction feedback without the intimidating clutter of traditional order books.

The visual style combines **Corporate Modernism** with subtle **Liquid Tonal Layering**:
- Bright, clinical background canvases with soft cerulean and periwinkle atmospheres.
- Crisp white surface cards with hairline tinted borders and gentle ambient blue glow.
- Tactile, rounded action elements with high-contrast primary accents.
- Elevated data displays featuring smooth volumetric wave accents and micro-badges for instant state recognition.

## Colors

The palette establishes an immediate sense of financial security and visual clarity through an intentional distribution of tint, surface, and semantic tones.

### Functional Palette Mapping
- **Primary (`#075BFF`)**: Drives primary conversion actions, active states, key data highlights, and brand emphasis. Used for primary CTA buttons, active tab indicators, and progress tracks.
- **Secondary (`#0037C5`)**: Provides grounding contrast for primary gradient transitions, pressed states, and high-emphasis hover states.
- **Tertiary / Success (`#16A34A`)**: Highlights positive balances, confirmed transfers, network stability metrics, and completion indicators. Paired with soft green surface tints (`#DCFCE7`).
- **Error / Danger (`#EF4444`)**: Signifies slippage warnings, network timeouts, failed validation, and asset drops. Paired with soft crimson surface tints (`#FEE2E2`).
- **Neutral Core (`#101B3F`)**: The authoritative navy anchor used for headlines, high-priority numbers, and primary interactive iconography.
- **Canvas Tones**:
  - `canvas-base`: `#F5F8FF` (light icy blue page canvas)
  - `canvas-subtle`: `#EAF2FF` (soft pill badge fills, secondary button backgrounds, input backdrops)
  - `surface-card`: `#FFFFFF` (elevated cards, floating navigation bars, modal dialogs)
  - `text-secondary`: `#5B6B8B` (supporting labels, timestamps, counterparty meta)
  - `border-subtle`: `#E2ECF9` (hairline separation on cards and list rows)

## Typography

Typography balances numeric precision with inviting editorial structure.

- **Headline Family (`Manrope`)**: Geometric curves with optimized capital letters and tight tracking give large values and value propositions a sculptural, authoritative presence.
- **Body & Label Family (`Inter`)**: Engineered for dense financial tables, balance breakdowns, and critical transaction states. Delivers flawless micro-legibility at small viewport sizes.
- **Tabular Figures**: All numeric data sets (crypto balances, dollar conversions, gas estimates, percentages) must implement `font-variant-numeric: tabular-nums` to ensure values line up across lists.
- **Hero & Headline Contrast**: Combine heavy black navy titles (`#101B3F`) with deliberate primary-colored emphasis words (`#075BFF`) to anchor user attention.

## Layout & Spacing

The layout model relies on a responsive 12-column desktop grid with a maximum content container width of 1200px, collapsing to 4 columns on mobile viewports.

### Breakpoint Strategy
- **Desktop (≥ 1024px)**: 12 columns, 24px (`gutter`) gutters, 40px (`margin`) outer margins. Multi-column cards and split hero dashboards.
- **Tablet (768px – 1023px)**: 8 columns, 20px gutters, 24px outer margins. Asset tables collapse secondary transaction details into expanders.
- **Mobile (< 768px)**: 4 columns, 16px (`gutter-mobile`) gutters, 20px (`margin-mobile`) outer padding. Single-column card stacking, sticky bottom navigation bars, and horizontal sliding carousels for partner ecosystem badges.

### Spacing Principles
- Internal card padding scales between 16px (mobile) and 24px (desktop).
- Visual rhythm strictly adheres to multiples of 4px and 8px.
- Compact micro-gaps (4px–8px) tether icons to related labels and badges.
- Roomy macro-gaps (32px–48px) clearly isolate disparate functional zones (e.g., wallet summary from activity log).

## Elevation & Depth

Visual hierarchy uses a refined layering scheme consisting of crisp white surfaces, calibrated blue-tinted ambient shadows, and atmospheric radial glow fields.

### Elevation Levels
- **Level 0 (Flat / Canvas)**: Background base `#F5F8FF` and subtle containers `#EAF2FF`. No shadow; defined strictly by border separation `#E2ECF9`.
- **Level 1 (Surface Cards & Inputs)**: `#FFFFFF` surfaces set over tinted canvases.
  - Shadow: `0 4px 16px -2px rgba(7, 91, 255, 0.05), 0 2px 6px -1px rgba(16, 27, 63, 0.03)`
  - Border: 1px solid `#E2ECF9`
- **Level 2 (Active Cards & Floating Action Shelves)**: Total portfolio containers and prominent platform selector blocks.
  - Shadow: `0 12px 28px -4px rgba(7, 91, 255, 0.08), 0 4px 10px -2px rgba(16, 27, 63, 0.04)`
  - Border: 1px solid rgba(255, 255, 255, 0.8) with ambient backdrop blur when overlaying subtle glows.
- **Level 3 (Modals, Overlays & Sticky Navbars)**: Dropdowns, confirmation sheets, and bottom app bar.
  - Shadow: `0 20px 40px -8px rgba(7, 91, 255, 0.12), 0 8px 16px -4px rgba(16, 27, 63, 0.06)`
- **Atmospheric Depth**: Ambient background gradients combine soft `#EBF3FF` blurs with radial `#075BFF10` spotlights positioned behind hero visual assets and data visualization charts.

## Shapes

The system adopts a modern, friendly geometry balancing generous radii for surfaces with tight, precise curves for compact interactive utilities.

- **Primary Cards & Containers**: 20px to 24px (`1.25rem` to `1.5rem`) corner radius, creating welcoming, non-aggressive modular compartments.
- **Input Fields & Quick-Action Buttons**: 12px to 14px (`0.75rem` to `0.875rem`) corner radius, fitting comfortably between finger tap targets and precise text cursor entries.
- **Status Badges, Filter Chips & Icon Bubbles**: 9999px (full pill form), establishing clear contrast against rectangular cards.
- **Crypto Asset Icon Squircle/Circle**: Full circular clipping (50%) for coin badges, token avatars, and user profile pictures.

## Components

### Buttons
- **Primary Button**: Solid `#075BFF` with hover to `#0037C5`. Text `#FFFFFF`, font `label-lg`, radius 12px, vertical padding 12px, horizontal padding 24px. Features subtle inner top highlight `inset 0 1px 0 rgba(255,255,255,0.2)`.
- **Secondary / Soft Button**: Background `#EAF2FF`, hover `#DCEBFF`, text `#075BFF`, font `label-lg`, radius 12px.
- **Ghost / Tertiary**: Transparent background, text `#101B3F`, hover `#F0F5FF`.
- **Quick Action Action Button (Mobile)**: Square-proportioned rounded card (`w-16 h-16` or column item), light `#EAF2FF` surface with royal blue icon, followed by an outside subtitle label.

### Form Inputs & Selectors
- **Input Field**: Height 48px, background `#FFFFFF`, border 1px solid `#E2ECF9`, radius 12px, text `#101B3F`, placeholder `#94A3B8`.
- **Focus State**: Border `#075BFF`, ring 3px `rgba(7, 91, 255, 0.15)`, smooth 150ms transition.
- **Amount / Transfer Input**: Large numeric display with affixed crypto currency ticker chip and "MAX" action link nested inside the input container.

### Status Chips & Badges
- **Success Badge**: Background `#DCFCE7`, text `#15803D`, icon micro-checkmark, padding 4px 10px, radius 9999px, font `label-pill`.
- **Primary Category Pill**: Background `#EAF2FF`, text `#075BFF`, font `label-pill`, radius 9999px.
- **Percentage Change Indicator**: Green `#DCFCE7` background with `#16A34A` text and upward chevron for gains; Red `#FEE2E2` with `#DC2626` text for drops.

### Cards & Data Panels
- **Balance Hero Card**: Gradient fill from `#075BFF` to `#0037C5`, white text, internal ambient wave vector graphic, integrated hide/show balance toggle, quick percentage change tag.
- **Interactive Asset Row**: White background, padding 14px 16px, radius 16px, border 1px solid `#F1F5F9`. Left: 40px circular crypto icon next to Asset Name and symbol. Right: balance volume in bold navy with converted fiat valuation beneath.
- **Platform Connector Card**: White surface, 16px padding, 16px radius, platform logo centered or left-aligned with subtle hover translateY(-2px) and border highlight.

### Lists & Activity Feeds
- **Transaction Item**: Left-aligned transfer direction icon inside a 36px `#EAF2FF` circular badge; centered metadata (Counterparty & date); right-aligned amount in bold tabular figures with attached status tag (`Completed`, `Pending`).
- **Dividers**: Soft `#F1F5F9` hairline dividers indented to match text baselines.

### Bottom Navigation Bar (Mobile)
- Height 68px, background `#FFFFFF` with 85% opacity and 12px blur backdrop filter. Top border `#E2ECF9`. Active tab highlighted with vibrant `#075BFF` icon and text label.