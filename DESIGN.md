---
name: Tectonic Atelier
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#56423d'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#8a726c'
  outline-variant: '#ddc0ba'
  surface-tint: '#a04028'
  primary: '#9d3d26'
  on-primary: '#ffffff'
  primary-container: '#bd553b'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a2'
  secondary: '#54606c'
  on-secondary: '#ffffff'
  secondary-container: '#d4e1f0'
  on-secondary-container: '#586471'
  tertiary: '#9c3e25'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc563b'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a2'
  on-primary-fixed: '#3c0700'
  on-primary-fixed-variant: '#802913'
  secondary-fixed: '#d7e4f3'
  secondary-fixed-dim: '#bbc8d7'
  on-secondary-fixed: '#111d28'
  on-secondary-fixed-variant: '#3c4854'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#ffb4a1'
  on-tertiary-fixed: '#3c0800'
  on-tertiary-fixed-variant: '#802a12'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
  surface-canvas: '#F9F8F6'
  surface-elevated: '#FFFFFF'
  surface-stone: '#F3F1EC'
  border-caliza: '#E3DFD7'
  border-hairline: '#C9CFD3'
  ink-primary: '#14202B'
  ink-muted: '#4D5A66'
  terracotta-accent: '#C2593F'
  terracotta-deep: '#9E412A'
  blueprint-grid: rgba(194, 89, 63, 0.08)
typography:
  display-hero:
    fontFamily: Bricolage Grotesque
    fontSize: 4rem
    fontWeight: '700'
    lineHeight: 4.4rem
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.6rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 2.85rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.1rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 1.85rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.6rem
  body-lead:
    fontFamily: Work Sans
    fontSize: 1.2rem
    fontWeight: '400'
    lineHeight: 1.9rem
  body-md:
    fontFamily: Work Sans
    fontSize: 1.05rem
    fontWeight: '400'
    lineHeight: 1.68rem
  body-sm:
    fontFamily: Work Sans
    fontSize: 0.95rem
    fontWeight: '400'
    lineHeight: 1.5rem
  label-lg:
    fontFamily: Work Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.4rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Work Sans
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
  label-code:
    fontFamily: Bricolage Grotesque
    fontSize: 1.6rem
    fontWeight: '700'
    lineHeight: 1.6rem
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.35rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style
This design system defines a commercial architecture atelier focused on high-yield physical spaces: specialty coffee shops, medical and dental clinics, boutique hospitality, and retail flagships. The brand narrative rejects generic, disembodied tech aesthetics in favor of tectonic materiality, spatial discipline, and high-trust commercial pragmatism.

The visual direction operates at the intersection of **Contemporary Architectural Rationalism** and **Tactile Warmth**. It avoids clinical cold grays and weightless floating elements, grounding the interface on surfaces reminiscent of warm limestone, raw linen, drafting paper, and oxidized architectural clay. The interface communicates technical rigor, cost control, and premium spatial intelligence to commercial entrepreneurs and practice owners.

## Colors
The palette balances mineral warmth with structural precision:

- **Primary (`#C2593F`)**: Architectural terracotta/fired brick. Applied exclusively to critical calls-to-action, structural indicators, and prominent typographic anchors.
- **Secondary (`#14202B`)**: Deep drafting charcoal ink. Delivers uncompromising legibility, authoritative framing, and structural borders.
- **Tertiary (`#B85338`)**: Deeper warm clay used for focused interaction states, hover responses, and tertiary accent rules.
- **Neutral (`#F9F8F6`)**: Stone lino canvas replacing sterile whites. It serves as the primary canvas to emulate unbleached linen and porous limestone.

### Application Guidelines
1. Avoid high-gloss or pure neon hues. All colors must reflect real-world building materials: lime wash, hot-rolled steel, terracotta tile, and honest joinery.
2. Maintain high contrast: all narrative text must use `ink-primary` against `surface-canvas` or `surface-elevated` to guarantee accessibility and executive clarity.
3. Use the drafting grid (`blueprint-grid`) strictly on hero or header backing surfaces, layered beneath structural cards at no more than 8% opacity.

## Typography
Typographic rhythm mirrors the balance of an architectural blueprint: expressive structural headers matched with technical, unyielding body execution.

- **Headlines (`Bricolage Grotesque`)**: Characterful, human, and grounded. The tight tracking and steep terminal cuts evoke precision masonry and industrial design heritage.
- **Body & Controls (`Work Sans`)**: Crisp, highly legible, and neutral. Set with open line heights to comfortably present technical parameters, commercial budgets, and regulatory phases.
- **Step Counters & Quantities (`label-code`)**: Emphasized numerals derived from the headline family to structure phased execution roadmaps.

## Layout & Spacing
The layout follows a modular grid bounded within a maximum content container of `1080px`. Vertical rhythm follows deliberate, architectural modules rather than arbitrary spacing:

- **Canvas Container**: Centered horizontal wrap with strict minimum edge margins of `1.25rem` on mobile and `2rem` on desktop.
- **Structural Sections**: Padded with `3.5rem` to `4.5rem` on the vertical axis to give projects breathing room and deliberate pacing.
- **Intrinsic Alignment**: Component lists and package modules use CSS intrinsic track grids (`repeat(auto-fit, minmax(260px, 1fr))`) to preserve column rhythm without fragile layout shifts.
- **Reading Length**: Text blocks, commercial justifications, and service breakdowns must never exceed `62ch` to guarantee swift comprehension.

## Elevation & Depth
Depth in this system is strictly tectonic, planar, and non-skeuomorphic. 

- **No Diffuse Drop Shadows**: Traditional blurs and floating card drop-shadows are strictly prohibited. Depth is rendered through structural layering and physical line weights.
- **Tectonic Planar Boundaries**: Elevated surfaces use solid ivory white (`#FFFFFF`) framed by precise hairline borders (`1px solid #E3DFD7`) directly atop the stone canvas (`#F9F8F6`).
- **Hierarchy via Line Weight**:
  - `1px solid #E3DFD7` for standard container walls, structural dividing shelves, and form perimeters.
  - `2px solid #14202B` or `2px solid #C2593F` for intentional interactive focus, action containers, and structural buttons.
  - `3px solid #C2593F` applied as left architectural anchor lines on callouts, risk mitigations, and phase sequences.
- **Subsurface Blueprint Layer**: In structural header regions, a subtle `44px` orthogonal grid rendered in `var(--blueprint-grid)` forms an understated drawing plane directly behind core propositions.

## Shapes
The shape language follows a disciplined architectural standard:
- **Base Elements (`roundedness: 1` / 4px)**: Buttons, inputs, chips, and interactive toggles employ tight, softened 4px corners. This eliminates digital harshness while maintaining technical discipline.
- **Architectural Structural Containers (0px)**: Grid cards, structural image viewports (`4:3` and `3:4`), packages, and section boundaries are pinned to zero radius (`0px`). They meet each other along crisp masonry joins and continuous divider lines.

## Components

### Buttons & Interactive Triggers
- **Primary Action**: Terracotta background (`#C2593F`), stark white typography (`#FFFFFF`), `2px solid #C2593F` outer edge, `4px` border radius, padding `0.85rem 1.6rem`. On hover, surface deepens to `#9E412A`.
- **Secondary Action (Tectonic Line)**: Transparent background, deep ink border (`2px solid #14202B`), dark charcoal typography (`#14202B`), `4px` border radius. On hover, fills with `#14202B` and inverts text to `#F9F8F6`.
- **Focus States**: High-visibility outline: `3px solid #C2593F` with an `outline-offset` of `3px`.

### Cards & Service Packages
- Built on `0px` radius containers with `1px solid #E3DFD7` perimeter boundaries.
- Interior surfaces use ivory white (`#FFFFFF`) with generous internal padding (`space-lg` / `2rem`).
- Cards stack seamlessly edge-to-edge in multi-column layouts, sharing borders to evoke floor plan drawings.

### Forms & Input Fields
- Inputs, textareas, and select elements use warm stone backgrounds (`#FFFFFF`), framed by `1px solid #C9CFD3`.
- Internal padding: `0.75rem 1rem`. Typography: `Work Sans` at `0.95rem`.
- Focus shifts border to `2px solid #C2593F` with zero blur or ambient halo.

### Architectural Phasing & Lists
- Numbered sequence steps feature large-scale numeral anchors in `Bricolage Grotesque` (`1.6rem`, weight `700`) tinted in `#C2593F`.
- Step items maintain a top boundary marker: `3px solid #14202B`.

### Tags & Commercial Badges
- Compact indicators set in `Work Sans` weight `600`, uppercase, letter-spacing `0.04em`, font size `0.75rem`.
- Styled with a light terracotta wash background (`rgba(194, 89, 63, 0.08)`) and terracotta text (`#C2593F`), framed in a delicate `1px solid rgba(194, 89, 63, 0.2)`.