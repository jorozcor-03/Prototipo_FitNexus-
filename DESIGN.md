---
name: Performance Elite
colors:
  surface: '#0e1511'
  surface-dim: '#0e1511'
  surface-bright: '#343b36'
  surface-container-lowest: '#09100c'
  surface-container-low: '#161d19'
  surface-container: '#1a211d'
  surface-container-high: '#242c27'
  surface-container-highest: '#2f3632'
  on-surface: '#dde4dd'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dde4dd'
  inverse-on-surface: '#2b322d'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#ffb690'
  on-secondary: '#552100'
  secondary-container: '#ec6a06'
  on-secondary-container: '#4a1c00'
  tertiary: '#ffb3af'
  on-tertiary: '#650911'
  tertiary-container: '#fc7c78'
  on-tertiary-container: '#711419'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3af'
  on-tertiary-fixed: '#410005'
  on-tertiary-fixed-variant: '#842225'
  background: '#0e1511'
  on-background: '#dde4dd'
  surface-variant: '#2f3632'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
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
  margin-desktop: 48px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is built upon the concept of "Performance Luxury." It targets high-achieving individuals and health professionals who demand precision data wrapped in a premium, frictionless interface. The aesthetic is rooted in **Corporate Modernism** with a **High-Contrast** edge, utilizing a deep, dark canvas to allow biometric data and performance metrics to vibrate with clarity.

The emotional response should be one of "Focused Energy"—the calm before a workout, the precision of a calculated diet, and the satisfaction of a closed data loop. We achieve this through expansive negative space, razor-sharp typography, and tactical use of high-energy neon accents against a sophisticated slate-dark backdrop.

## Colors

The palette is optimized for low-light environments and high-intensity focus. 

- **Primary (Neon Emerald):** This is the color of "Action." It is used for primary conversion points, success states, and active tracking indicators. It symbolizes growth and vitality.
- **Secondary (Sports Orange):** This is the color of "Attention." It is reserved for high-priority calls to action, urgent notifications, and specialized badges (e.g., "Pro" or "Live").
- **Neutral Ramp:** The background (#090D16) provides a deep, ink-like foundation. The Surface (#121826) creates subtle depth for cards and containers. Text utilizes a "Cloud White" for primary readability and "Slate" for secondary metadata to ensure a clear hierarchy without eye strain.

## Typography

This design system utilizes **Inter** exclusively to maintain a systematic, utilitarian feel that mirrors high-end performance hardware. 

- **Headlines:** Use Extra-bold (800) for large displays to create a sense of strength and authority. Negative letter-spacing is applied to larger sizes to keep the "Fit" between letters tight and energetic.
- **Body:** Standardized on a 16px base for optimal legibility against dark backgrounds. 
- **Labels:** Small caps and increased letter spacing are used for data labels and categories to differentiate them from prose, aiding in quick scanning of health metrics.

## Layout & Spacing

The design system employs a **12-column fluid grid** for desktop and a **4-column grid** for mobile. We use an 8px rhythmic scale to ensure consistent vertical flow.

- **Desktop:** A fixed-width container of 1280px is centered for main content areas to prevent line lengths from becoming unreadable on ultra-wide monitors.
- **Gutters:** A generous 24px gutter ensures that dense data tables and charts have sufficient "breathing room."
- **Padding:** Internal card padding should always be at least 24px (3 units) to maintain the premium, spacious feel.

## Elevation & Depth

In this dark-themed design system, depth is communicated through **Tonal Layering** rather than heavy shadows. 

1. **Level 0 (Background):** #090D16 - The foundational "floor."
2. **Level 1 (Surface):** #121826 - For main content cards and navigation bars.
3. **Level 2 (Overlay):** #1E293B - For hover states, dropdowns, and modals.

To enhance the "SaaS" feel, use **Inner Glows** on primary buttons (1px, 20% white) to make them appear slightly inset or high-definition. Avoid drop shadows on cards; instead, use a subtle 1px border (#1E293B) to define edges against the background.

## Shapes

The design system uses a **Rounded (Level 2)** shape language. This balances the aggressive, high-performance nature of the typography with a modern, approachable SaaS feel.

- **Buttons & Inputs:** 0.5rem (8px) corner radius.
- **Cards & Modals:** 1rem (16px) corner radius.
- **Data Chips:** Full pill-shaped (999px) to contrast against the structured grid of cards.

## Components

- **Buttons:** Primary buttons use the Neon Emerald (#10B981) with black text for maximum contrast. Secondary buttons use a ghost style with a slate border.
- **CTAs:** Special conversion points (like "Upgrade to Pro") utilize the Sports Orange (#F97316) to disrupt the cool color palette.
- **Data Cards:** Surfaces (#121826) featuring a subtle top-border in Neon Emerald for active tracking categories.
- **Inputs:** Darker than the surface (#0F172A) with a 1px border. On focus, the border transitions to Neon Emerald with a soft 4px outer glow.
- **Progress Bars:** Use a thick 8px track. The unfilled portion is #1E293B, while the progress is a gradient from Neon Emerald to a slightly lighter green to indicate motion and energy.
- **Badges:** Small, all-caps labels with a subtle background tint of the accent color (10% opacity) and 100% opacity text for the label itself.