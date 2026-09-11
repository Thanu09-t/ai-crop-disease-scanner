---
name: Earthy Modern
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#414844'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#116c4a'
  on-secondary: '#ffffff'
  secondary-container: '#a1f4c8'
  on-secondary-container: '#1b724f'
  tertiary: '#3a2017'
  on-tertiary: '#ffffff'
  tertiary-container: '#52352b'
  on-tertiary-container: '#c79d90'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#a1f4c8'
  secondary-fixed-dim: '#86d7ad'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdbcf'
  tertiary-fixed-dim: '#e9bdae'
  on-tertiary-fixed: '#2d150d'
  on-tertiary-fixed-variant: '#5e3f35'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin-mobile: 16px
  container-margin-desktop: 64px
  gutter: 16px
  touch-target-min: 48px
---

## Brand & Style
The design system is built for the modern agricultural landscape, bridging the gap between traditional farming wisdom and data-driven technology. The brand personality is grounded, dependable, and vital. It aims to evoke a sense of growth and reliability, ensuring users feel empowered whether they are in a sun-drenched field or a brightly lit office.

The aesthetic follows a **Modern Corporate** style infused with **Tactile** elements. It prioritizes clarity and high-contrast visuals to ensure legibility under direct sunlight. The interface utilizes generous whitespace, clear structural hierarchy, and soft elevation to create an approachable yet professional tool for agricultural management.

## Colors
The palette is rooted in the natural lifecycle of crops. **Deep Forest Green** serves as the primary brand color, used for high-level navigation and primary actions to convey stability. **Vibrant Leaf Green** is the functional accent, indicating growth, health, and success. **Warm Soil Brown** provides a grounding element for secondary information and organic data points.

The background uses a clean **Off-White** to reduce harsh glare while maintaining high contrast. For data visualization, specifically confidence scores in crop diagnostics, a five-step progressive scale is used, transitioning from a critical Red to the healthy Leaf Green.

## Typography
This design system utilizes **Inter** for its exceptional legibility and robust support for both English and Kannada scripts. The typeface’s tall x-height and neutral character make it ideal for data-heavy agricultural tables and outdoor mobile use.

Typography is structured to maintain a clear hierarchy. Larger headlines are slightly tighter in letter spacing to create a modern, "locked-in" feel, while body text maintains standard spacing for maximum readability. For Kannada script rendering, ensure line heights are increased by 10% if the default feels cramped, preserving the vertical space required for glyph matras.

## Layout & Spacing
The layout follows a **Fluid Grid** model on mobile and a **Fixed Max-Width Grid** (1280px) on desktop. A consistent 8px base unit drives all spacing decisions, ensuring a rhythmic vertical flow.

On mobile devices, a 4-column grid is used with 16px side margins. On desktop, a 12-column grid provides flexibility for complex data dashboards. To accommodate outdoor use cases where precision might be hampered by weather or gloves, the minimum touch target for any interactive element is strictly 48px.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows**. The design system avoids harsh, black shadows in favor of soft, diffused shadows tinted with a hint of the primary green (#1B4332 at 8% opacity).

- **Level 0 (Base):** Off-white background (#F8F9FA).
- **Level 1 (Cards):** Pure white surfaces with a soft 4px blur shadow. Used for primary content blocks.
- **Level 2 (Overlays/Modals):** Pure white surfaces with a 12px blur shadow, creating a clear distinction from the background layer.
- **Level 3 (Floating Actions):** High-contrast buttons with an 8px blur shadow to indicate interactivity.

## Shapes
The shape language is defined by **Rounded** geometry, specifically a 16px (1rem) corner radius for primary cards and containers. This softened geometry balances the technical nature of agricultural data with an approachable, organic feel. 

Buttons and input fields follow a consistent 8px (0.5rem) radius. High-level status indicators and tags may use a pill-shape (fully rounded) to differentiate them from interactive buttons.

## Components
### Buttons
Primary buttons use the Forest Green (#1B4332) with white text. Secondary buttons use a Leaf Green outline. All buttons must maintain a 48px height on mobile to facilitate easy tapping in the field.

### Cards
Cards are the primary container. They feature a 1px border (#E0E0E0) and a subtle Level 1 shadow. Cards used for crop health scanning should include a top-accent bar colored according to the confidence scale.

### Input Fields
Inputs use a white background with a Soil Brown (#6D4C41) border on focus. Labels remain visible above the field at all times to ensure context is never lost during data entry.

### Chips & Tags
Used for weather alerts or crop types. These are small, low-profile elements with a 4px radius. 

### Scanning Interface
A specialized component featuring a central "viewfinder" with a semi-transparent overlay. Real-time confidence scores are displayed at the bottom of the viewfinder using the progressive color scale.

### Iconography
Icons are 24px stroke-based (2px weight) with rounded terminals. They should be simplified representations of weather patterns, diagnostic tools, and botanical elements.