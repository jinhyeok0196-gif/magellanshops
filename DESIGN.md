---
name: Aether Fluid
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c8c6ca'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#919095'
  outline-variant: '#47464a'
  surface-tint: '#c8c6c8'
  primary: '#c8c6c8'
  on-primary: '#303032'
  primary-container: '#121214'
  on-primary-container: '#7e7d7f'
  inverse-primary: '#5f5e60'
  secondary: '#ddb7ff'
  on-secondary: '#490080'
  secondary-container: '#6f00be'
  on-secondary-container: '#d6a9ff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00151a'
  on-tertiary-container: '#008aa1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e1e4'
  primary-fixed-dim: '#c8c6c8'
  on-primary-fixed: '#1b1b1d'
  on-primary-fixed-variant: '#474649'
  secondary-fixed: '#f0dbff'
  secondary-fixed-dim: '#ddb7ff'
  on-secondary-fixed: '#2c0051'
  on-secondary-fixed-variant: '#6900b3'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is engineered to evoke a sense of hyper-personalized intelligence and premium technical sophistication. It targets a discerning audience looking for data-driven wellness and lifestyle optimization. 

The aesthetic is a hybrid of **Modern Minimalism** and **Glassmorphism**. It utilizes deep, immersive backgrounds to provide a canvas for vibrant, glowing accents that represent AI "spark" or activity. The interface must feel ethereal yet grounded, using high-quality typography and intentional negative space to ensure the user feels they are interacting with a high-end, reliable digital concierge.

## Colors

The palette is anchored in a **Dark Mode** environment to emphasize depth and premium quality.

- **Deep Charcoal (#121214):** The primary canvas color. It is not pure black, allowing for subtle shadow work and depth perception.
- **Electric Purple (#A855F7):** Used for primary actions, success states, and the "intelligence" layer of the brand.
- **Vibrant Cyan (#06B6D4):** Used for secondary highlights, data visualizations, and active progress indicators.
- **Neutral Slate (#94A3B8):** Applied to secondary text and inactive UI elements to maintain a clear visual hierarchy.

Gradients should transition from Purple to Cyan at a 135-degree angle to represent fluid movement and transformation.

## Typography

This design system utilizes **Inter** for all primary communication due to its exceptional legibility and neutral, modern character. For technical data and UI labels, **Geist** is introduced to provide a monospaced-adjacent, developer-focused aesthetic that reinforces the AI-driven narrative.

Headlines use tight letter-spacing and bold weights to command attention. Body text maintains generous line-heights to ensure readability against dark, translucent backgrounds. Labels are often set in uppercase with slight tracking to differentiate them from prose.

## Layout & Spacing

The layout follows a **Fluid Grid** system based on an 8px base unit. 

- **Desktop:** 12-column grid with 24px gutters. Content is centered with a max-width of 1200px.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px gutters and 16px side margins.

Spacing between functional groups should be generous (48px - 64px) to allow the glassmorphic elements "room to breathe" and prevent the interface from feeling cluttered or overwhelming.

## Elevation & Depth

Depth is established through **Glassmorphism** and layering rather than traditional shadows.

1.  **Base Layer:** Solid Deep Charcoal background.
2.  **Mid Layer:** Semi-transparent surfaces (Background Blur: 20px, Opacity: 40%) with a 1px white border at 10% opacity to define the edge.
3.  **Top Layer:** Active elements or modals with higher opacity (60%) and a subtle outer glow using the primary accent color (Purple) to signify focus.

Ambient "blobs" of blurred color (Purple and Cyan) are placed behind glass layers to create a sense of dynamic energy moving through the liquid recommendation engine.

## Shapes

The shape language is consistently **Rounded**, reflecting the "fluid" nature of the product. 

Standard components use a 0.5rem (8px) radius. Larger cards and sections use 1rem (16px) or 1.5rem (24px) to create a soft, inviting feel. Interactive elements like buttons and chips may utilize pill-shaping (full rounding) to contrast against the more structured container shapes.

## Components

- **Buttons:** Primary buttons use a linear gradient (Purple to Cyan) with white text. Secondary buttons are "ghost" style with a glass background and a thin border.
- **Cards:** Use glassmorphism properties: 12% white fill, 20px backdrop blur, and 1px border-top/border-left for a "light hit" effect.
- **Inputs:** Darker than the base background with a subtle inner glow. On focus, the border transitions to a Cyan-to-Purple gradient.
- **Chips/Badges:** High-contrast, small-scale elements with Geist typography. Used for liquid properties (e.g., "Hydrating," "High-Caffeine").
- **Lists:** Separated by low-opacity hairline dividers. Each item features a subtle hover state that increases the glass opacity.
- **Progress Indicators:** Use glowing Cyan paths to represent fluid levels or recommendation loading states.