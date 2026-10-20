---
name: Architectural Monograph
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8dae2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fc'
  surface-container: '#ecedf6'
  surface-container-high: '#e6e8f0'
  surface-container-highest: '#e1e2eb'
  on-surface: '#191c22'
  on-surface-variant: '#434654'
  inverse-surface: '#2d3037'
  inverse-on-surface: '#eff0f9'
  outline: '#737686'
  outline-variant: '#c3c5d7'
  surface-tint: '#1353d8'
  primary: '#003fb1'
  on-primary: '#ffffff'
  primary-container: '#1a56db'
  on-primary-container: '#d4dcff'
  inverse-primary: '#b5c4ff'
  secondary: '#765929'
  on-secondary: '#ffffff'
  secondary-container: '#ffd79b'
  on-secondary-container: '#795c2c'
  tertiary: '#00544c'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e65'
  on-tertiary-container: '#84f0e2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b5c4ff'
  on-primary-fixed: '#00174d'
  on-primary-fixed-variant: '#003dab'
  secondary-fixed: '#ffdeae'
  secondary-fixed-dim: '#e7c187'
  on-secondary-fixed: '#281900'
  on-secondary-fixed-variant: '#5c4214'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f9f9ff'
  on-background: '#191c22'
  surface-variant: '#e1e2eb'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-tablet: 2.5rem
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

This design system expresses the intellectual rigor of deep systems engineering unified with the quiet luxury of a Swiss architectural monograph. Designed for a high-impact engineering portfolio and research dossier, the visual tone avoids both cold developer utilitarianism and transient visual gimmicks. 

The aesthetic is grounded in:
- **Editorial Archival Authority:** Warm ivory surfaces, generous page borders, structured typographic hierarchy, and deliberate micro-annotations that present software artifacts and research papers as enduring scholarship.
- **Precision Engineering:** Clean architectural line work, proportional rhythm, and sharp technical badges rendered with monospaced data clarity.
- **Quiet Depth:** Subtle physical layering achieved via alabaster backdrops, pristine white floating cards, and diffuse warm ambient elevation rather than stark outlines.

Target audience: Principal engineers, research scientists, technical founders, and elite design engineering directors looking for depth, craftsmanship, and clarity.

## Colors

The palette establishes an intellectual, warm-light atmosphere derived from archival heavy-stock paper and high-density printing ink:

- **Canvas & Surface Base:**
  - Base Canvas: `#FBFBF9` (Warm Ivory)
  - Section Canvas / Recessed Well: `#F6F5F1` (Architectural Alabaster)
  - Elevated Card Surface: `#FFFFFF` (Pristine Archival White)
- **Ink & Typography Hierarchy:**
  - Ink Primary: `#11141A` (Deepest Onyx Ink)
  - Ink Secondary: `#1E232E` (Structured Body Ink)
  - Ink Muted / Metadata: `#5A6272` (Graphite Slate)
  - Ink Subdued: `#8F97A6` (Archival Caption Gray)
- **Dividers & Structural Rules:**
  - Border Subtle: `#E4E2DC` (Warm Alabaster Rule)
  - Border Strong: `#D8D5CD` (Structured Frame)
- **Signaling & Accents:**
  - Primary Accent: `#1A56DB` (Bespoke Warm Cobalt / Royal Blue) — reserved for active states, primary CTA anchors, interactive focal points, and live research demo anchors.
  - Secondary Accent: `#8C6D3B` (Warm Patina Bronze) — employed for editorial marks, honors, citations, and archival badges.
  - Tertiary / Metric Accent: `#0D9488` (Cyan Slate) — utilized strictly for system status, live telemetry, and computational benchmarks.

## Typography

Typography acts as the primary structural material. Three specialized typefaces work in concert:

1. **Plus Jakarta Sans (Headlines & Title Display):** Crisp, geometric sans with balanced proportions. Used at tight negative letter-spacing for headlines to create an authoritative presence reminiscent of high-end design monographs.
2. **Inter (Reading Canvas & Body):** High-legibility utilitarian body text optimized for dense engineering rationales, research write-ups, and long-form methodology breakdowns.
3. **JetBrains Mono (Technical Badging, Figures & Metadata):** Monospaced precision for commit hashes, benchmark speeds, publication dates, mathematical notation, and index categorization.

Typesetting directives:
- Body copy line lengths must never exceed 68 characters for optimal reading cadence.
- Monospaced technical tags should always be set with slight positive tracking (`0.04em` to `0.06em`) and sentence case or subtle uppercase.

## Layout & Spacing

The layout is anchored in a disciplined, asymmetrical 12-column Swiss grid that dynamically reconfigures to suit both rich media case studies and dense bibliographic indexes:

- **Grid Model:**
  - **Desktop (≥1200px):** 12 columns with `2rem` gutters and a maximum content constraint of `1320px` centered within a minimum page margin of `4rem`. Typical distributions include an asymmetrical 4-column metadata rail alongside an 8-column research narrative.
  - **Tablet (768px – 1199px):** 8 columns with `1.5rem` gutters and `2.5rem` outer margins. Side rails fold into contextual horizontal meta-headers.
  - **Mobile (<768px):** 4 columns with `1rem` gutters and `1.25rem` outer margins. Horizontal scrolling tables and diagrams sit within padded containers that gracefully allow edge-to-edge examination.

- **Vertical Rhythm:**
  - Standard component gap uses `space-md` (`1rem`) and `space-lg` (`1.5rem`).
  - Major dossier section breaks consume `space-2xl` (`4rem`) or `space-3xl` (`6rem`), allowing negative space to establish cognitive boundaries without relying on heavy horizontal lines.

## Elevation & Depth

Visual hierarchy is constructed through tonal warmth, architectural layering, and diffused ambient lighting rather than artificial high-contrast drops:

- **Canvas Tiering:**
  - Base plane (`#FBFBF9`) supports ambient reading.
  - Secondary recessed wells (`#F6F5F1`) hold technical diagrams, architecture schemas, and interactive code blocks.
  - Foreground floating cards (`#FFFFFF`) feature hairline perimeter stabilization.

- **Shadow Craft:**
  - **Resting Elevation (Cards & Modules):** `0 1px 3px rgba(17, 20, 26, 0.04), 0 8px 24px -4px rgba(17, 20, 26, 0.03)` alongside a subtle `#E4E2DC` 1px border.
  - **Interactive Hover Elevation:** `0 12px 32px -6px rgba(26, 86, 219, 0.08), 0 4px 12px -2px rgba(17, 20, 26, 0.03)` with border shifting subtly to `#D8D5CD`.
  - **Overlays & Architectural Modals:** Backdrop is tinted with `#11141A` at 30% opacity with a `12px` Gaussian blur, allowing underlying schema traces to show through while lifting the white modal via `0 24px 48px -12px rgba(17, 20, 26, 0.16)`.

## Shapes

The geometric character uses `soft` corner treatments (roundedness level `1`), reinforcing the architectural blueprint metaphor:

- Standard structural elements (cards, panels, code snippets, visual containers) use `0.375rem` (6px) or `0.5rem` (8px).
- Interactive inputs, tags, and secondary action buttons adopt a crisp `0.25rem` (4px) to maintain a tailored, non-childish silhouette.
- Badges and micro-status tags use precision pill radiuses only when indicating dynamic runtime states (e.g., active telemetry, publication status) to contrast against rectilinear card bounds.

## Components

### Buttons & Interactive Triggers
- **Primary Action:** Solid `#1A56DB` cobalt background, crisp white Inter text, 0.375rem radius, micro padding `0.625rem 1.25rem`. Hover state transitions to `#1545B3` with subtle vertical translation (-1px).
- **Secondary (Editorial Rule):** Clean white surface, 1px border `#D8D5CD`, typography `#11141A`. Hover yields `#F6F5F1` fill and `#1A56DB` text shift.
- **Text / Inline Reference:** Underlined with an offset 1px `#D8D5CD` rule that switches to `#1A56DB` on hover.

### Chips & Technical Badges
- **Architecture Taxonomy Tags:** JetBrains Mono 11px uppercase, background `#F6F5F1`, text `#5A6272`, border 1px solid `#E4E2DC`.
- **Patina Research Accents:** Reserved for paper citations, award markers, and conference presentations. Background `rgba(140, 109, 59, 0.08)`, text `#8C6D3B`, border `rgba(140, 109, 59, 0.20)`.
- **System Telemetry Chips:** Inset dot indicator in `#0D9488` with a gentle pulsing perimeter, signaling operational production deployments.

### Research Cards & Project Dossiers
- Constructed on pristine `#FFFFFF` backed by 1px `#E4E2DC` outlines.
- Internal padding is generous (`space-xl` / `2rem`), partitioned into clear sectors:
  1. Monospaced index header and chronological date.
  2. Bold Plus Jakarta Sans project headline.
  3. Inter body summary.
  4. Embedded architectural thumbnail or interactive flow trace with a `#F6F5F1` bounding box.
  5. Footer row containing technology tags and direct research links.

### Input Fields & Controls
- Form and query inputs use a `#FFFFFF` fill with 1px `#E4E2DC` borders. Focused state swaps border to `#1A56DB` accompanied by a `0 0 0 3px rgba(26, 86, 219, 0.12)` focus ring.
- Checkboxes and radio toggles feature crisp 1px borders, filling with `#1A56DB` and displaying clean white geometric ticks.

### Architecture Schematics & Code Windows
- Framed in an archival alabaster card (`#F6F5F1`) with an inset code header containing filename, language pill, and copy actions rendered in JetBrains Mono.
- Diagrams are rendered using monochrome `#11141A` stroke logic with `#1A56DB` vector callouts for primary execution paths and `#8C6D3B` for auxiliary dependencies.