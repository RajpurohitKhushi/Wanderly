---
name: Warm Editorial Journey
colors:
  surface: '#fef9ef'
  surface-dim: '#dedad0'
  surface-bright: '#fef9ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3e9'
  surface-container: '#f2ede3'
  surface-container-high: '#ece8de'
  surface-container-highest: '#e7e2d8'
  on-surface: '#1d1c16'
  on-surface-variant: '#414848'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e6'
  outline: '#717978'
  outline-variant: '#c0c8c7'
  surface-tint: '#3f6565'
  primary: '#002929'
  on-primary: '#ffffff'
  primary-container: '#173f3f'
  on-primary-container: '#83aaaa'
  inverse-primary: '#a6cecd'
  secondary: '#376666'
  on-secondary: '#ffffff'
  secondary-container: '#baeceb'
  on-secondary-container: '#3d6c6c'
  tertiary: '#4b0b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e1b06'
  on-tertiary-container: '#f88163'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1eaea'
  primary-fixed-dim: '#a6cecd'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#264d4d'
  secondary-fixed: '#baeceb'
  secondary-fixed-dim: '#9fcfcf'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#1c4e4e'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a2'
  on-tertiary-fixed: '#3c0700'
  on-tertiary-fixed-variant: '#812912'
  background: '#fef9ef'
  on-background: '#1d1c16'
  surface-variant: '#e7e2d8'
typography:
  display-lg:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Epilogue
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 3.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system embodies an editorial, contemplative, and organized approach to travel planning. It rejects the hyper-stimulated, urgent, discount-driven tropes of legacy travel aggregators in favor of a poised, serene, and tactile atmosphere reminiscent of high-end travel journals and modernist architectural retreats. 

The aesthetic is built on a foundation of Warm Minimalism infused with subtle tactile refinement:
- **Atmosphere:** Sunlit, airy, purposeful. Generous negative space frames intentional content blocks.
- **Visual Tension:** The deliberate counterpoint between rich, anchored deep teal structures and spontaneous, sun-kissed coral callouts.
- **Emotional Resonance:** Inspires calm confidence, creative discovery, and the distinct joy of unhurried curation. Every surface looks touched by natural light.

## Colors

The color architecture is built strictly upon warm daylight tones, organic minerals, and deliberate contrast:

- **Primary Deep Teal (`#173F3F`):** Used for foundational typographic hierarchy, primary interaction nodes, anchor badges, and structural brand anchors.
- **Secondary Slate/Teal (`#2A5A5A` & `#6C8282`):** Carries mid-level hierarchy, supportive icons, metadata chips, subheadings, and progressive interaction borders.
- **Accent Coral (`#E87558`):** Reserved exclusively for deliberate calls to action, high-value highlights, live itinerary pins, and active engagement tags. Never over-applied to large decorative fields.
- **Warm Neutral Canvas (`#F7F2E8`):** The default root background. It eliminates cold clinical whites, providing the optical comfort of heavy, uncoated paper stock.
- **Surface Neutrals (`#FFFFFF` & `#FAF6EE`):** Pure white is treated strictly as an elevated, focused card tier to contrast cleanly with the warm cream root canvas. `#FAF6EE` serves as an alternate recessed panel or active item background.

## Typography

Typography establishes an editorial pace:

- **Display & Headlines (Epilogue):** Chosen for its structured geometric precision with nuanced humanist touches, providing an elevated, bespoke editorial tone for titles, destinations, and trip narratives.
- **Body & Controls (Inter):** System-grade legibility for dense itinerary timetables, cost breakdowns, reviews, and interactive form fields.
- **Hierarchy Rules:** Large editorial display titles utilize tight negative tracking (`-0.02em`) to bind headline phrases together. Micro-labels and metadata tags employ uppercase styling with open letter-spacing (`0.08em`) to balance density across card interfaces.

## Layout & Spacing

The layout philosophy follows a disciplined 12-column fluid grid system paired with strict horizontal rhythm:

- **Desktop (>= 1024px):** 12 columns with `gutter-lg` (2rem) and `margin-desktop` (3.5rem). Max container constraint set at 1360px to preserve comfortable reading lengths.
- **Tablet (768px – 1023px):** 8 columns with `gutter` (1.5rem) and `margin` (2rem). Dual itinerary panels transition to single-column collapsible views.
- **Mobile (< 768px):** 4 columns with `gutter-sm` (1rem) and `margin-mobile` (1.25rem). Cards expand edge-to-edge within margins; horizontal snapping rails are used for itinerary timeline filters and destination galleries.
- **Spatial Rhythm:** Generous vertical breathing room (`space-2xl` between macro-sections) maintains the serene, uncluttered aesthetic. Internal component padding favors vertical airiness (`space-md` to `space-lg`).

## Elevation & Depth

Visual hierarchy relies on quiet, natural light physics rather than synthetic digital elevation:

- **Tonal Layers:** The baseline stage is Canvas Cream (`#F7F2E8`). Interactive modules and card surfaces rise via pure white fills (`#FFFFFF`) or subtle contrast panels (`#FAF6EE`).
- **Low-Contrast Ghost Outlines:** Cards and containers use an ultra-thin 1px border colored with deep teal at 8% opacity (`rgba(23, 63, 63, 0.08)`), imparting tangible edges without visual clutter.
- **Sunlit Ambient Shadows:** Floating elements, modals, and hover states feature diffused, tinted shadows that replicate angled natural light:
  - *Resting Card:* `0 2px 10px rgba(23, 63, 63, 0.03)` with standard 1px border.
  - *Hovered Card:* `0 12px 30px rgba(23, 63, 63, 0.07)`, 1px border shifts to `rgba(23, 63, 63, 0.16)`.
  - *Modals & Overlays:* `0 24px 48px rgba(23, 63, 63, 0.12)`.

## Shapes

The geometry is organic yet controlled:

- Standard input fields, compact chips, and secondary triggers use rounded corners (8px to 12px).
- Content cards, itinerary segment panels, and visual containers sit at a generous 16px to 20px radius (`rounded-lg` to `rounded-xl`).
- Filter badges, micro status pills, and primary circular action buttons utilize fully rounded ends to contrast against structural rectilinear card containers.

## Components

- **Buttons:**
  - *Primary:* Solid Deep Teal (`#173F3F`) fill, text in `#FFFFFF`, subtle 12px corner rounding, height of 48px. Hover state shifts to `#2A5A5A` with subtle scale-up.
  - *Accent Action:* Coral (`#E87558`) fill, text in `#FFFFFF`, reserved strictly for booking, trip checkout, or saving an itinerary.
  - *Secondary / Ghost:* Transparent background, 1px border in `rgba(23, 63, 63, 0.2)`, text in `#173F3F`. Hover introduces a warm `#FAF6EE` background fill.

- **Cards:**
  - Constructed on crisp white (`#FFFFFF`) or sand (`#FAF6EE`) with 16px to 20px radii and the 1px low-contrast teal border.
  - Generous internal padding (`space-lg`), paired with high-quality landscape imagery featuring subtle 12px inner corner rounding.

- **Chips & Filter Pills:**
  - Inactive: Background `#FFFFFF`, border 1px `rgba(23, 63, 63, 0.12)`, text `#2A5A5A`.
  - Active: Background `#173F3F`, text `#FFFFFF`, border `#173F3F`.
  - Accent / Notification: Tinted Coral (`rgba(232, 117, 88, 0.12)`), text `#E87558`.

- **Form Fields & Inputs:**
  - Date pickers, traveler selectors, and destination search fields sit on `#FFFFFF` backgrounds with an inset 1px border (`rgba(23, 63, 63, 0.14)`).
  - Focus state highlights with a 1.5px solid border in Deep Teal (`#173F3F`) and an ambient outer ring of `rgba(23, 63, 63, 0.08)`. Placeholder text sits in muted slate (`#6C8282`).

- **Itinerary Timeline & Steppers:**
  - Vertical timeline stems styled in a soft 2px continuous line (`rgba(23, 63, 63, 0.1)`). Active milestones feature deep teal circular anchors with white inner nodes; flight and transfer milestones feature delicate mono-line icons.