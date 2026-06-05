---
name: Organic Artisan
colors:
  surface: '#f0fdf1'
  surface-dim: '#d0ddd2'
  surface-bright: '#f0fdf1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf7eb'
  surface-container: '#e4f1e5'
  surface-container-high: '#dfece0'
  surface-container-highest: '#d9e6da'
  on-surface: '#131e17'
  on-surface-variant: '#40493d'
  inverse-surface: '#28332b'
  inverse-on-surface: '#e7f4e8'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#286b33'
  on-secondary: '#ffffff'
  secondary-container: '#abf4ac'
  on-secondary-container: '#2e7238'
  tertiary: '#415b45'
  on-tertiary: '#ffffff'
  tertiary-container: '#59745c'
  on-tertiary-container: '#daf9db'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#abf4ac'
  secondary-fixed-dim: '#90d792'
  on-secondary-fixed: '#002107'
  on-secondary-fixed-variant: '#07521d'
  tertiary-fixed: '#cceacd'
  tertiary-fixed-dim: '#b1ceb2'
  on-tertiary-fixed: '#07200e'
  on-tertiary-fixed-variant: '#334d37'
  background: '#f0fdf1'
  on-background: '#131e17'
  surface-variant: '#d9e6da'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 60px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.4'
    letterSpacing: 0.1em
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
---

## Brand & Style
The design system is centered on the concept of "Digital Craftsmanship." It merges the tactile, physical world with a refined digital interface, targeting high-end clients who value detail and intentionality. 

The visual style is **Tactile Skeuomorphism** blended with **Glassmorphism**. It avoids the heavy gloss of early 2000s design in favor of soft, matte surfaces, "squishy" interactive states, and organic depth. The UI should feel like a physical desk made of frosted glass and recycled paper, bathed in a soft, verdant light. The emotional response is one of calm, professional confidence and creative warmth.

## Colors
The palette is a monochromatic transition of organic greens. 
- **Primary (#2E7D32):** Used for high-contrast text, primary actions, and deep structural shadows.
- **Secondary (#81C784):** The core interactive color, used for "glow" states and soft highlights.
- **Tertiary (#C8E6C9):** Used for mid-tone surfaces and inner bevels.
- **Neutral (#E8F5E9):** The base canvas color, mimicking high-quality textured paper.

Depth is achieved through color-tinted shadows rather than pure greys, ensuring the "organic" feel remains consistent throughout the interface.

## Typography
The system uses a sophisticated pairing of **Libre Caslon Text** for headings and **Manrope** for functional text. 
- **Headings:** Should be treated with generous line height and tight letter-spacing for a modern-editorial look. In large displays, headings may use a subtle text-shadow (1px 1px 2px rgba(0,0,0,0.05)) to feel "pressed" into the page.
- **Body & Labels:** Manrope provides a clean, neutral balance to the decorative serif. All labels should be uppercase with slight tracking to enhance readability against textured backgrounds.

## Layout & Spacing
The layout follows a **Fluid Grid** logic within a centered container. 
- **Grid:** 12-column system for desktop, 4-column for mobile.
- **Rhythm:** An 8px base unit drives all padding and margins. 
- **Whitespace:** Elements are given significant breathing room to emphasize the "gallery" feel of a portfolio. 
- **Adaptation:** On mobile, margins reduce significantly, and skeuomorphic depth is flattened slightly (reducing shadow spreads) to maintain clarity on smaller screens.

## Elevation & Depth
Depth is the cornerstone of this design system. It is achieved through a combination of three techniques:
1.  **Convex Surfaces (Extruded):** Use dual shadows. A light highlight on the top-left (white, 40% opacity) and a soft green shadow on the bottom-right (#2E7D32, 15% opacity).
2.  **Concave Surfaces (In-set):** Use inner shadows to make elements like input fields and "active" buttons look recessed into the background.
3.  **Glassmorphism:** Navigation bars and floating modals use a backdrop-blur (12px to 20px) with a semi-transparent fill of the Neutral color (80% opacity) and a thin 1px inner-border highlight.

## Shapes
Shapes are **Rounded** to maintain the organic, approachable feel. 
- Base components use a **0.5rem (8px)** radius.
- Larger cards and containers use **1rem (16px)** to feel like smooth, tumbled stones.
- Avoid perfectly circular pills unless used for specific icon buttons, as the slightly squared-off corners feel more "architectural."

## Components
- **Buttons:** Primary buttons feature a soft "pop" effect (convex). On hover, they emit a soft green outer glow. On click, they transition to an "inset" shadow state.
- **Cards:** Project cards should use the glassmorphic style with a subtle 1px border. The border should have a linear gradient from top-left (white) to bottom-right (Primary color) at low opacity to simulate light hitting an edge.
- **Input Fields:** Recessed (inset) styling with a subtle inner shadow. When focused, the inner border glows with the Secondary color.
- **Chips/Tags:** Small, pill-shaped elements with a flat, semi-transparent green fill and high-contrast text.
- **Custom Cursor:** A soft, semi-transparent green circle that expands and blurs when hovering over interactive skeuomorphic elements, reinforcing the "glow" theme.