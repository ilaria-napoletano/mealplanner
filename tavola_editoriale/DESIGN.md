---
name: Tavola Editoriale
colors:
  surface: '#FFFFFF'
  surface-dim: '#dfdacc'
  surface-bright: '#fff9eb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f3e5'
  surface-container: '#f3eddf'
  surface-container-high: '#ede8da'
  surface-container-highest: '#e8e2d4'
  on-surface: '#1d1c13'
  on-surface-variant: '#414845'
  inverse-surface: '#333027'
  inverse-on-surface: '#f6f0e2'
  outline: '#717974'
  outline-variant: '#c1c8c3'
  surface-tint: '#F1EAD9'
  primary: '#254b3e'
  on-primary: '#ffffff'
  primary-container: '#3d6355'
  on-primary-container: '#b4ddcc'
  inverse-primary: '#a6cfbe'
  secondary: '#834d6d'
  on-secondary: '#ffffff'
  secondary-container: '#febbe0'
  on-secondary-container: '#7b4766'
  tertiary: '#603d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#805200'
  on-tertiary-container: '#ffcc8a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c2ecda'
  primary-fixed-dim: '#a6cfbe'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#284e41'
  secondary-fixed: '#ffd8eb'
  secondary-fixed-dim: '#f5b3d7'
  on-secondary-fixed: '#350a27'
  on-secondary-fixed-variant: '#683654'
  tertiary-fixed: '#ffddb5'
  tertiary-fixed-dim: '#ffb959'
  on-tertiary-fixed: '#2a1800'
  on-tertiary-fixed-variant: '#643f00'
  background: '#fff9eb'
  on-background: '#1d1c13'
  surface-variant: '#e8e2d4'
  bg-canvas: '#FAF7F1'
  line: '#E5DCC6'
  muted: '#736C58'
  lunch-soft: '#E4EDE6'
  dinner-soft: '#F1E4EC'
  weekend-soft: '#F5E9D4'
  dark-bg-canvas: '#1C1A15'
  dark-surface: '#252219'
  dark-surface-tint: '#2E2A1F'
  dark-line: '#3C3627'
  dark-ink: '#EFE8D6'
  dark-muted: '#A99E82'
  dark-lunch: '#7FAD98'
  dark-lunch-soft: '#26332C'
  dark-dinner: '#D19BC0'
  dark-dinner-soft: '#332430'
  dark-weekend: '#E3AC55'
  dark-weekend-soft: '#332A18'
typography:
  display:
    fontFamily: Fraunces
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Fraunces
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Fraunces
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Fraunces
    fontSize: 19px
    fontWeight: '600'
    lineHeight: 25px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Fraunces
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 22px
  title-md:
    fontFamily: Work Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  body-lg:
    fontFamily: Work Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 23px
  body-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 21px
  body-sm:
    fontFamily: Work Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Work Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
  caption:
    fontFamily: Work Sans
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 13px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 0.875rem
  gutter-mobile: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system expresses a warm, editorial, and domestic identity tailored for off-campus university students and young independents organizing their weekly nutrition. It moves away from cold, sterile fitness trackers or chaotic commercial recipe portals, choosing instead the tactile calmness of an Italian culinary journal. The aesthetic reconciles the literary cadence of historic recipe prints with the utilitarian precision of iOS human interface design.

The design philosophy blends **Warm Editorial Minimalism** with functional structure. The UI evokes comfort, mindful domestic planning, and low-friction organization. Visual weight is articulated through rich typography, creamy layered surfaces, and semantic meal hues: earthy forest sage for lunch, contemplative plum for dinner, and warm roasted ochre for weekend freeform meals.

## Colors

The palette rejects sterile monochrome neutrals in favor of organic, warm cream and wheat undertones.

- **Primary (`#3D6355` - Pranzo/Lunch)**: A grounding forest sage representing daylight, energetic balance, and structured midday meal preparation.
- **Secondary (`#7A4665` - Cena/Dinner)**: A velvety plum/mora hue evoking evening decompression, shared home tables, and slow cooking.
- **Tertiary (`#B4791C` - Jolly/Weekend)**: Warm roasted ochre reserved for festive weekend slots, occasional treats, and special culinary notices.
- **Neutral (`#2A281F` - Ink)**: A deep espresso-charcoal holding warm brown pigment to preserve reading softness against light grounds.

Chromatic semantic colors (`lunch`, `dinner`, `weekend`) must always be matched with their corresponding `-soft` tinted fills for tags, badges, and contextual meal cards. In dark mode, color luminance steps down while text values switch to low-glare warm ivory (`#EFE8D6`).

## Typography

The typography implements an intentional contrast between literary tradition and pragmatic utilitarian legibility:

1. **Headlines (`Fraunces`)**: Applied strictly to section titles, day headers, recipe titles, and primary modal headers. Set with optical balance (`text-wrap: balance`) to maintain typographic dignity across viewport changes.
2. **Body (`Work Sans`)**: Dedicated to ingredients, preparation directions, shopping entries, and continuous reading. Maintains generous line height (`1.45` to `1.6`) to ensure effortless glanceability on kitchen counters.
3. **Labels & Metadata (`Work Sans` Uppercase)**: Used for cooking time metrics, equipment badges, meal types, and iOS bottom navigation elements. Styled with deliberate letter-spacing (`0.04em`–`0.08em`) and medium/semibold weight for crisp micro-legibility.

## Layout & Spacing

The layout model adheres to a mobile-first, fluid content column that expands safely up to a maximum constrained measure of `920px` on larger surfaces (such as iPad or desktop views). 

### Grid & Layout Structure
- **Mobile (<640px)**: Single column with `16px` outer margin. The weekly planner stacks horizontally or presents as a scrollable card strip. Recipe breakdowns present ingredients stacked above culinary steps.
- **Tablet / Expanded (>=640px)**: Two-column asymmetrical layout (`1fr 1.6fr`) for recipe inspection; weekly calendar displays as an auto-fitting card grid (`minmax(220px, 1fr)`).
- **iOS Safe Areas**: Top bar incorporates `env(safe-area-inset-top)` with a minimum `16px` inner clearance. Fixed bottom navigation respects `calc(8px + env(safe-area-inset-bottom))`, while tab panels maintain a trailing bottom padding of `calc(96px + env(safe-area-inset-bottom))` to prevent interaction clipping.

### Spatial Rhythm
Content components conform to a baseline 4px grid. Standard interactive rows maintain a vertical target height of at least 44px to satisfy iOS touch targets.

## Elevation & Depth

This design system avoids high-contrast drop shadows and artificial blur textures, employing instead a tactile "printed-paper" elevation model:

- **Surface Tier 0 (Canvas)**: Non-elevated creamy parchment (`#FAF7F1`), providing a soft, non-reflective background.
- **Surface Tier 1 (Cards & Modules)**: Pure white (`#FFFFFF`) cards resting on canvas with hairline structural boundaries (`1px solid var(--line)`).
- **Dual-Stop Ambient Shadows**: Elevated structural modules (`.day-card`, `.recipe`) use a warm-cast, low-opacity shadow pair:
  - Light mode: `0 1px 2px rgba(40, 35, 20, 0.06), 0 6px 16px rgba(40, 35, 20, 0.05)`
  - Dark mode: `0 1px 2px rgba(0, 0, 0, 0.30), 0 8px 20px rgba(0, 0, 0, 0.35)`
- **Pinned Chrome**: Sticky navigation elements (`.topbar`, `.tabbar`) stay opaque to preserve legible contrast without GPU-heavy real-time blurring.

## Shapes

The shape system adopts warm, rounded geometry that softens functional grids while maintaining crisp alignment with iOS native controls:

- **Micro Chips & Badges (`5px - 6px`)**: Applied to compact duration indicators (`20 min`), meal labels (`PRANZO`), and kitchen equipment tags.
- **Interactive Controls & Inputs (`8px`)**: Form elements, text field entries, and secondary action triggers.
- **Navigation Controls (`10px`)**: Segmented controls and tab item highlights.
- **Structural Cards (`12px - 14px`)**: Applied to day meal planner modules, recipe cards, and pantry warning containers.

## Components

### Buttons & Actions
- **Primary Button**: Solid fill with `--pranzo` (`#3D6355`), text in `--bg` (`#FAF7F1`), uppercase label typography (`label-sm`), height 42px, radius 8px. Pressed state darkens luminance by 8%.
- **Secondary / Ghost Button**: Transparent fill, 1px border in `--line`, text in `--muted`. On active/hover, border transitions to `--ink` and text shifts to `--ink`.
- **Destructive Glyph**: Native `×` trigger with touch bounding box of 32×32px, text color `--muted`, turning to `--cena` on hover/press.

### Chips & Semantic Badges
- **Meal Segment Chips**: Padded horizontally with `space-sm` and vertically with `space-xs`. Uppercase label styling.
  - *Pranzo*: Background `--lunch-soft`, text `--pranzo`.
  - *Cena*: Background `--dinner-soft`, text `--cena`.
  - *Weekend / Jolly*: Background `--weekend-soft`, text `--occ`.

### Segmented Tab Bar (iOS Native Feel)
- Fixed at viewport bottom with safe area clearance.
- Container surface is `--surface` with a 1px top divider (`--line`).
- Active segment renders a filled background (`--surface-tint`) with `--ink` text. Inactive segments remain transparent with `--muted` text.

### Interactive Checklist & Grocery Items
- Item container has 1px bottom divider line.
- Checkbox styled to 19×19px native box with accent-color matching `--pranzo`.
- Checked state transitions text to `--muted` with line-through treatment.

### Recipe & Day Cards
- White background (`--surface`), 1px line border, warm ambient dual-stop shadow.
- Weekend variants incorporate a 1px solid border in `--occ` accompanied by a light `--weekend-soft` tint.
- Link items within day rows feature a subtle 1px dotted underline in `--line`, turning solid `--ink` on interaction.