---
name: Radical Velocity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bdb8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ae8883'
  outline-variant: '#5d3f3c'
  surface-tint: '#ffb4ac'
  primary: '#ffb4ac'
  on-primary: '#690006'
  primary-container: '#e31b23'
  on-primary-container: '#fff9f8'
  inverse-primary: '#c00015'
  secondary: '#c8c6c5'
  on-secondary: '#303030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#727474'
  on-tertiary-container: '#fbfbfb'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  cta-text:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  section-gap: 80px
---

## Brand & Style
This design system captures the raw power and urban grit of the Venezuelan motorcycling culture, translated into a premium digital showroom. The brand personality is **robust, aspirational, and high-octane**, designed to evoke a sense of freedom and mechanical precision. 

The aesthetic leverages a **Modern-Industrial** approach with a heavy emphasis on **High-Contrast Dark Mode**. By utilizing deep blacks and graphite grays, the UI recedes to let the high-quality photography of the motorcycles become the focal point. The emotional response is one of adrenaline and reliability, positioning the dealership not just as a retail space, but as an entry point into a lifestyle of performance.

## Colors
The palette is built on a foundation of "Asphalt and Chrome." The background utilizes `#121212` for the base canvas to ensure true blacks on OLED screens, while `#1E1E1E` is used for surface containers to create structural depth.

The primary accent is **Vibrant Red (#E31B23)**, reserved strictly for call-to-action (CTA) elements, price highlights, and "Live" status indicators. This color represents energy and urgent conversion. Secondary accents include pure white for maximum legibility against dark backgrounds and various shades of "Cool Gray" to denote inactive states or secondary information without competing with the red.

## Typography
The typography system uses a hierarchical "Heavy-to-Light" strategy. **Montserrat** is the voice of the brand, used in extra-bold weights for headlines to mimic the bold badging found on motorcycle tanks. Its geometric nature provides a modern, engineered feel.

**Inter** handles the functional heavy lifting for technical specifications and descriptions, ensuring clarity even at smaller sizes. For technical data points (engine CC, torque, fuel capacity), **Geist** is introduced as a label font to provide a monospaced, "spec-sheet" aesthetic that appeals to enthusiasts.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a 12-column structure for desktop. To maintain a "premium showroom" feel, the system utilizes generous vertical spacing (`section-gap`) between content blocks, preventing the UI from feeling cluttered.

On mobile devices, the margins tighten to `16px` to maximize screen real estate for product imagery, while the 12-column grid collapses into a single column. Horizontal scrolling "shelves" are used for motorcycle categories to allow users to browse models without excessive vertical scrolling.

## Elevation & Depth
Depth is achieved through **Tonal Layering** rather than traditional drop shadows. Surfaces closer to the user are lighter in gray (e.g., `#2C2C2C`), creating a stacked effect. 

Where shadows are used, they are **Ambient and Tinted**—large blur radii with low opacity, using a slight red or dark blue tint to avoid a "muddy" look. High-end product cards utilize a subtle `1px` inner border (stroke) of `#333333` to define edges against the black background, ensuring the hardware feels "carved" out of the interface.

## Shapes
This design system uses **Soft (Level 1)** roundedness. While the brand is "robust," full sharp corners feel dated and aggressive. A `0.25rem` (4px) base radius provides a modern, machined finish—reminiscent of industrial parts and carbon fiber panels. 

Buttons and input fields follow this subtle rounding, while large imagery containers (hero sections) may remain sharp to maintain a cinematic, "edge-to-edge" impact.

## Components
- **Primary Buttons:** Solid `#E31B23` fill with white Montserrat Bold text. Use a slight "glow" (outer shadow of the same color) on hover to simulate a brake light ignition.
- **Product Cards:** Dark `#1E1E1E` background with a `1px` subtle border. The image of the motorcycle should slightly "pop" or scale up on hover. 
- **Technical Badges (Chips):** Semi-transparent white or gray backgrounds with Geist labels. Used for "In Stock," "New," or specific engine types.
- **Input Fields:** Dark gray background with a high-contrast white border on focus. Use the Red accent for error states only.
- **Lists:** Clean, border-bottom separated rows for technical specifications, using Inter for values and Geist for labels.
- **Photo Overlays:** Use a 40% black-to-transparent gradient on images to ensure headline text remains legible while maintaining the visual integrity of the photography.