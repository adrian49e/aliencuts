---
name: Cosmic Urban Noir
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c2caad'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8c9479'
  outline-variant: '#434933'
  surface-tint: '#a0d800'
  primary: '#ffffff'
  on-primary: '#253600'
  primary-container: '#b7f700'
  on-primary-container: '#506e00'
  inverse-primary: '#4b6700'
  secondary: '#e3b5ff'
  on-secondary: '#4d007a'
  secondary-container: '#9400e4'
  on-secondary-container: '#f0d2ff'
  tertiary: '#ffffff'
  on-tertiary: '#00363a'
  tertiary-container: '#7df4ff'
  on-tertiary-container: '#006f77'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b7f700'
  primary-fixed-dim: '#a0d800'
  on-primary-fixed: '#141f00'
  on-primary-fixed-variant: '#374e00'
  secondary-fixed: '#f3daff'
  secondary-fixed-dim: '#e3b5ff'
  on-secondary-fixed: '#2f004c'
  on-secondary-fixed-variant: '#6e00ab'
  tertiary-fixed: '#7df4ff'
  tertiary-fixed-dim: '#00dbe9'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.15em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 32px
  xl: 64px
  gutter: 24px
  margin: 24px
---

## Brand & Style

This design system is built to evoke the high-energy, nocturnal atmosphere of an intergalactic terminal located in the heart of Cabo San Lucas. The brand personality is aggressive, avant-garde, and unapologetically futuristic, catering to a clientele that views grooming as a form of "bio-modification" or "tech-upgrade."

The aesthetic combines **Glassmorphism** with **High-Contrast** elements. It utilizes deep transparency to create depth, mimicking the vastness of space, while grounding the interface with sharp, neon-lit structural components that feel like the dashboard of a high-end spacecraft. The emotional response is one of excitement, exclusivity, and precision.

## Colors

The palette is anchored in a "Void Black" base to ensure maximum contrast for the radioactive accents. 
- **Primary (Neon Green):** Used for primary actions, success states, and "active" energy signals. It represents the "Alien" life force.
- **Secondary (Cyber Purple):** Used for navigational elements, secondary buttons, and depth-defining glows.
- **Accents (White/Cyan):** Used for critical data readouts and fine mechanical details.

Backgrounds should utilize subtle radial gradients of purple and black to simulate cosmic dust, ensuring the "deep black" never feels flat.

## Typography

The design system exclusively utilizes **Space Grotesk** to maintain a technical, engineering-heavy aesthetic. 
- **Display Type:** Should be set with tight tracking to feel dense and powerful.
- **Labels:** Use all-caps with wide letter-spacing for "system-readout" styles, perfect for prices or technical barbering services (e.g., "HAIR RECONSTRUCTION").
- **Contrast:** Always pair large, bold headlines with much smaller, high-tracking labels to create a hierarchy that feels like a HUD (Heads-Up Display).

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to maintain a "contained console" feel, transitioning to a fluid model for mobile devices. 
- **Grid:** A 12-column structure with generous gutters to allow the background stardust patterns to breathe between UI panels.
- **Rhythm:** An 8px linear scale is used for most components, but 4px increments are permitted for micro-adjustments in technical icons or borders.
- **Padding:** Internal card padding should be generous (32px+) to emphasize the "glass" edges and the glow they emit.

## Elevation & Depth

In this design system, depth is conveyed through **Glassmorphism** and **Luminescence** rather than traditional shadows.
- **Layer 0 (Background):** Deep black with a subtle, non-moving "stardust" texture and faint purple radial blurs.
- **Layer 1 (Panels):** Translucent dark cards (Background: `rgba(20, 20, 20, 0.7)`) with a 1px solid border in low-opacity white or purple. Apply a `backdrop-filter: blur(20px)`.
- **Layer 2 (Floating/Active):** Elements that are interactive should emit a "Neon Glow." This is achieved using `box-shadow` with 0px offset and a spread that matches the element's accent color (Green or Purple).
- **Z-Axis:** Higher elevation is represented by increased border brightness and stronger backdrop blurs.

## Shapes

The shape language is "Aggressive-Precision." While the base roundedness is set to **Soft (Level 1)**, the system thrives on the juxtaposition of sharp corners and subtle curves.
- **Buttons:** Sharp 90-degree corners on one side and a 0.5rem curve on the opposite side are encouraged for a "custom-molded" look.
- **Cards:** Standard 0.25rem (4px) corner radius to keep them looking technical and sleek.
- **Decorative Elements:** Use 45-degree clipped corners (chamfers) for containers to reinforce the sci-fi/military-tech aesthetic.

## Components

- **Buttons:** Primary buttons feature a solid Neon Green background with black text. Hover states must trigger an outer glow effect. Secondary buttons are transparent with a 2px Neon Purple border.
- **Glass Cards:** Used for service menus and booking details. They must have a subtle "shine" gradient (linear, 45 degrees, transparent white to fully transparent) to simulate light hitting glass.
- **Inputs:** Underline-style inputs with a focus state that "charges" the line, turning it from dim purple to bright neon green.
- **Chips/Status:** Small, all-caps pills with high-saturation backgrounds. Used for "Availability" or "Barber Skill Level."
- **Scrollbars:** Custom-styled to be ultra-thin, neon green, and floating without a track.
- **Specialty Component (The HUD Overlay):** A persistent corner element showing "Real-time Cabo Status" (Temperature/Time) styled like a flight computer readout.