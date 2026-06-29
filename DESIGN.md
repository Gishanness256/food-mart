---
name: Organic Vitality
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#40493d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#3e6a00'
  on-secondary: '#ffffff'
  secondary-container: '#b9f474'
  on-secondary-container: '#437000'
  tertiary: '#7a4b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#9b6100'
  on-tertiary-container: '#ffefe0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#b9f474'
  secondary-fixed-dim: '#9ed75b'
  on-secondary-fixed: '#0f2000'
  on-secondary-fixed-variant: '#2e4f00'
  tertiary-fixed: '#ffddb9'
  tertiary-fixed-dim: '#ffb961'
  on-tertiary-fixed: '#2b1700'
  on-tertiary-fixed-variant: '#663e00'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
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
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  section-gap: 80px
---

## Brand & Style
The design system is rooted in the "Fresh Modern Organic" aesthetic, bridging the gap between traditional Ugandan agriculture and a premium, global digital marketplace experience. It evokes the feeling of a sun-drenched farm at dawn—vibrant, clean, and full of life.

The style is a blend of **Modernism** and **Glassmorphism**. It utilizes expansive white space (the "clean" feel), high-quality natural imagery, and sophisticated translucent layers to suggest the freshness of dew on produce. The UI should feel airy and premium, avoiding the cluttered "discount" look of traditional e-commerce. Every interaction should reinforce a sense of health, abundance, and uncompromising quality.

## Colors
The palette is inspired by the lush landscapes of Uganda. 

- **Primary (Deep Green):** Represents the heart of the farm. Used for high-emphasis actions, navigation headers, and core brand elements.
- **Secondary (Fresh Lime):** Represents growth and vitality. Used for success states, badges, and subtle highlights.
- **Accent (Mango Orange):** A warm, high-contrast color used sparingly for "Add to Cart" buttons, promotions, and price highlights to drive conversion.
- **Background (Natural Cream):** Provides a warmer, more organic foundation than pure white, reducing eye strain and reinforcing the "natural" brand pillar.
- **Surface (White):** Used for cards and interactive elements to create clear separation from the cream background using elevation.

## Typography
The typography strategy pairs the confident, geometric personality of **Montserrat** for headlines with the exceptional legibility of **Inter** for commerce-heavy data.

Headlines should use tight letter-spacing to appear more editorial and premium. Body text maintains a generous line height to ensure descriptions of organic produce remain approachable and easy to scan. Use "Deep Green" for primary headlines to reinforce brand identity, and a dark charcoal (#424242) for body copy to maintain high accessibility against the cream background.

## Layout & Spacing
The layout follows a **Fluid Grid** system with a focus on generous negative space to emphasize product photography. 

- **Desktop:** 12-column grid with 24px gutters. Content is centered with a max-width of 1280px.
- **Mobile:** Single column with 16px side margins. 
- **Rhythm:** An 8px linear scale is used for all internal component spacing (padding, gaps). Large section gaps (80px+) are encouraged to separate product categories (e.g., "Vegetables" vs "Fruits") to give the UI a breathable, "Whole Foods" gallery feel.

## Elevation & Depth
This design system uses **Tonal Layering** combined with **Glassmorphism** to create a sense of freshness and transparency.

- **Level 0 (Background):** Natural Cream (#FFF8E1).
- **Level 1 (Cards):** Pure White (#FFFFFF) with a very soft, diffused "Ambient Green" shadow (Primary color at 8% opacity, 20px blur, 4px Y-offset).
- **Level 2 (Navigation/Overlays):** Semi-transparent white (80% opacity) with a 16px background blur (Backdrop Filter). This "glass" effect should be used for sticky headers and mobile menus to suggest the clarity of fresh water.
- **Level 3 (Modals/Popovers):** Standard white with a deeper, more pronounced shadow to focus attention.

## Shapes
In line with the organic theme, the shape language avoids harsh corners. Elements use **Rounded-2xl (1.5rem / 24px)** as the standard for product cards and primary containers. Smaller elements like buttons and input fields utilize **Rounded-lg (1rem / 16px)** to maintain a cohesive, soft-touch interface. This "bento-box" style of rounded containers helps organize diverse food products into a harmonious visual feast.

## Components
- **Buttons:** Primary buttons use a solid Mango Orange with white text for maximum "Add to Cart" visibility. Secondary buttons use a Deep Green outline with 2px weight. All buttons feature a subtle 200ms scale-down transition on press.
- **Product Cards:** Feature a full-bleed image at the top, followed by a 16px padded area for the title (Montserrat) and price. On hover, cards should lift slightly (-4px Y-axis) and the shadow should deepen.
- **Chips/Badges:** Used for "Organic," "Local," or "Seasonal" labels. These should have a secondary Lime Green background with Deep Green text, using a fully pill-shaped radius.
- **Input Fields:** Search bars and forms use a 1px Deep Green border at 20% opacity. Upon focus, the border becomes 100% Primary Green with a soft outer glow.
- **Progressive Disclosure:** Use smooth "spring" animations for cart drawers and category filters to mimic the fluid, natural movement of the brand.
- **Specialty Component - "Farmer Profile":** A specific card variant that uses a circular image and a "verified" badge to build trust between the consumer and the source.