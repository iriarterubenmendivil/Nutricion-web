---
name: Mediterranean Vitality
colors:
  surface: '#fdf9f0'
  surface-dim: '#dedad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c16'
  on-surface-variant: '#424841'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e7'
  outline: '#727970'
  outline-variant: '#c2c8bf'
  surface-tint: '#436747'
  primary: '#436747'
  on-primary: '#ffffff'
  primary-container: '#7ba17d'
  on-primary-container: '#14371b'
  inverse-primary: '#a9d1aa'
  secondary: '#486648'
  on-secondary: '#ffffff'
  secondary-container: '#c7e9c3'
  on-secondary-container: '#4c6a4c'
  tertiary: '#8c4e33'
  on-tertiary: '#ffffff'
  tertiary-container: '#cf8667'
  on-tertiary-container: '#53220a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c4edc5'
  primary-fixed-dim: '#a9d1aa'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#2c4e31'
  secondary-fixed: '#caecc6'
  secondary-fixed-dim: '#aecfab'
  on-secondary-fixed: '#052109'
  on-secondary-fixed-variant: '#314d31'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb597'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#6f371e'
  background: '#fdf9f0'
  on-background: '#1c1c16'
  surface-variant: '#e6e2d9'
typography:
  h1:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: '0'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  button:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is anchored in a **Modern Minimalist** aesthetic with **Tactile** influences, designed to evoke the serenity and freshness of a high-end Mediterranean wellness retreat. It targets a health-conscious Spanish demographic that values both scientific precision and culinary pleasure. 

The UI prioritizes "luminosity"—using expansive whitespace and a warm, organic palette to create a sense of breathing room. The emotional response is one of calm confidence; the interface feels like a professional advisor who is also an approachable companion. This is achieved through a balance of elegant editorial typography, soft-edged geometry, and realistic, high-fidelity imagery that celebrates the vibrant colors of natural ingredients.

## Colors

This design system utilizes a palette inspired by nature to reinforce a "healthy and premium" brand promise.

- **Brand Primary (Sage Green):** Used for key brand moments, active states, and icons related to growth and health.
- **Brand Secondary (Dark Olive):** Reserved for high-contrast elements, footers, and sophisticated accents that ground the lighter colors.
- **CTA (Soft Coral):** A strategic contrast color specifically for "Commitment" actions. It provides warmth and high visibility against the greens without being aggressive.
- **Background (Off-white):** A creamy, non-sterile base that makes the UI feel "luminous" and "warm" compared to pure white.
- **Typography (Dark Green-Grey):** A deep, near-black neutral that maintains legibility while feeling softer and more organic than true black.

## Typography

The typography strategy leverages the contrast between the traditional authority of a serif and the modern efficiency of a sans-serif.

- **Headlines:** Uses **Newsreader**, an elegant serif that conveys a professional, editorial tone. It should be used for all major section titles to inject a "premium" feel.
- **Body & UI:** Uses **Manrope**, a highly legible sans-serif with a geometric touch. It remains clear at small sizes for nutritional data and long-form advice.
- **Hierarchy:** Maintain generous vertical rhythm. Headlines should use "Optical Sizing" where possible to preserve the delicacy of the serif strokes.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop (12 columns) and a **Fluid Fluid** approach for mobile (4 columns). 

- **The 8px Rule:** All spacing and component heights are multiples of 8px to ensure a consistent visual rhythm.
- **Generous Margins:** Content containers should maintain a minimum of 24px side margins on mobile to emphasize the "clean and luminous" feel.
- **Section Breathing Room:** Use large vertical padding (80px+) between major landing page sections to prevent the "cluttered" look often found in medical services.

## Elevation & Depth

To maintain a "luminous" feel, the design system avoids heavy shadows in favor of **Ambient Tonal Layers** and **Tinted Soft Shadows**.

- **Shadow Character:** Shadows are extremely diffused (Blur: 30px+) with low opacity (8-12%) and are tinted with the Dark Olive (#3D5A3D) rather than pure black. This creates a natural, "sunny" depth.
- **Tonal Layering:** Depth is primarily communicated through subtle shifts in background color. For example, a card might sit on the Off-white background with a slightly lighter white surface and a subtle Sage Green border (1px at 10% opacity).
- **Interactions:** On hover, elements should lift slightly (2-4px) and the shadow's spread should increase to simulate physical proximity.

## Shapes

The shape language is defined by **Rounded (16px)** corners. This specific radius is large enough to feel friendly and "organic" (matching the curves of a bowl or fruit) but disciplined enough to maintain a professional app structure.

- **Containers:** All primary cards and modals use a 16px (1rem) radius.
- **Small Elements:** Buttons and input fields use a slightly smaller 12px radius to maintain visual harmony.
- **Icons:** Should be encased in "Squircle" or rounded-square containers when used as decorative accents.

## Components

- **Buttons:** 
    - *Primary:* Solid Soft Coral (#E89B7B) with white or Dark Green-Grey text. High-conversion focus.
    - *Secondary:* Ghost style with Sage Green (#7BA17D) outlines and 600 weight text.
- **Input Fields:** Off-white fill with a 1px Dark Olive border at 20% opacity. Focus state transitions the border to full Sage Green with a soft outer glow.
- **Cards:** 16px rounded corners, subtle tinted shadow, and a white background to "pop" against the Off-white page background. Used for meal plans and progress tracking.
- **Chips/Badges:** Used for nutritional tags (e.g., "Vegano," "Alta Proteína"). Soft Sage Green background with Dark Olive text.
- **Nutrition Progress Bars:** Use rounded caps and the Sage Green for completion, with a very pale neutral for the track.
- **Imagery Containers:** Images should always have the 16px radius. When featuring food, use "Realistic Macro" photography—close-ups that show texture and freshness, avoiding flat-lays that feel like generic stock.