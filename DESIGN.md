---
name: Epicurean Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#d0ceca'
  on-tertiary: '#30312e'
  tertiary-container: '#b4b3af'
  on-tertiary-container: '#454542'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e4e2dd'
  tertiary-fixed-dim: '#c8c6c2'
  on-tertiary-fixed: '#1b1c19'
  on-tertiary-fixed-variant: '#474744'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style
The design system is engineered for the high-end culinary sector, focusing on exclusivity, precision, and sensory appeal. The target audience includes discerning diners, gourmands, and luxury hospitality stakeholders who value craft over convenience.

The style is **Modern Luxury**, characterized by:
- **Atmospheric Depth:** Utilizing deep charcoal backgrounds to allow high-fidelity food photography to emerge with vibrant clarity.
- **Understated Elegance:** Merging the timeless authority of editorial serif typography with the functional precision of modern tech aesthetics.
- **Tactile Sophistication:** Incorporating subtle glassmorphism and soft-light elevation to create a sense of physical layers, reminiscent of fine glassware and polished surfaces.
- **Spaciousness:** Generous use of white space (or "dark space") to ensure the UI feels unhurried and premium.

## Colors
The palette is rooted in a "Noir" aesthetic to evoke the atmosphere of a dimly lit, high-end dining room.

- **Primary (Gold):** `#D4AF37` is used sparingly for accents, interactive states, and brand iconography to signify value and heritage.
- **Secondary (Charcoal):** `#1A1A1A` serves as the primary surface color, providing a deep, non-distracting canvas.
- **Tertiary (Off-White):** `#F9F7F2` is used for high-contrast typography and essential readability, avoiding the harshness of pure white.
- **Neutral/Surface:** `#262626` defines container levels and UI structural elements, creating a subtle distinction from the background.

## Typography
The typography strategy creates an editorial rhythm. 

**Playfair Display** is the "voice" of the brand—used for titles, dish names, and storytelling. It should be typeset with tight letter spacing in large formats to emphasize its elegant serifs.

**Inter** provides the functional "skeleton." It is used for descriptions, nutritional data, and interface labels. For labels and navigation, use increased letter spacing and uppercase styling to maintain a structured, professional appearance.

Ensure body text maintains a line height of at least 1.6 to allow for a comfortable reading experience against dark backgrounds.

## Layout & Spacing
The layout follows a **Fixed Grid** system on desktop to maintain curated, magazine-like compositions.

- **Desktop (1280px+):** 12-column grid with 24px gutters. Content is centered with wide 64px margins to create an "airy" feel.
- **Tablet:** 8-column grid with 24px gutters and 40px margins.
- **Mobile:** 4-column grid with 16px gutters and 20px margins.

Use a consistent 8px scale for internal component spacing. Section gaps should be aggressive (up to 120px) to delineate different courses of information, preventing the "clutter" common in standard food apps.

## Elevation & Depth
Depth is achieved through **Tonal Stacking** and **Subtle Translucency**.

- **Level 0 (Background):** Secondary color (`#1A1A1A`).
- **Level 1 (Cards/Containers):** Neutral color (`#262626`) with a 1px stroke of white at 5% opacity.
- **Glassmorphism:** For overlays like navigation bars or floating action buttons, use a background blur (16px - 20px) combined with a 40% opaque dark fill.
- **Shadows:** Use large, ultra-soft "ambient" shadows. Avoid black shadows; instead, use a deep charcoal with 30-40% opacity and a 30px-50px blur radius to create a "glow" rather than a hard drop.

## Shapes
The shape language is refined and consistent. We use a **Rounded** (0.5rem base) approach to balance modern tech with organic softness.

- **Base Radius:** 8px for small components like inputs and chips.
- **Large Radius (rounded-lg):** 16px for primary cards and modal containers to soften the high-contrast edges.
- **Interactive Elements:** Buttons can utilize the Large Radius or remain pill-shaped depending on their hierarchy within the page.

## Components
- **Buttons:** Primary buttons use the Gold accent with dark text. Secondary buttons use a "ghost" style with a subtle 1px border and a hover transition that fills the background with a soft gold tint.
- **Premium Cards:** Featured menu items should use cards with a fixed aspect ratio (e.g., 4:5), high-quality imagery, and typography overlaid on a subtle bottom-to-top dark gradient.
- **Form Fields:** Inputs should be "minimalist"—a bottom border only or a very dark background fill. Focus states are indicated by a change in border color to Gold.
- **Chips:** Used for dietary tags (e.g., Vegan, Gluten-Free). These should be small, outlined in gold, using `label-sm` typography.
- **Lists:** Reservation or order lists should feature generous vertical padding (24px+) with thin dividers in 10% opacity white.
- **Photography:** All imagery must be professional, macro-focused, and color-graded to feel warm and inviting, contrasting with the cool, dark UI.