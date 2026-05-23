---
name: Industrial Precision
colors:
  surface: '#fdf8f8'
  surface-dim: '#ddd9d8'
  surface-bright: '#fdf8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3f2'
  surface-container: '#f1edec'
  surface-container-high: '#ebe7e6'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#444748'
  inverse-surface: '#313030'
  inverse-on-surface: '#f4f0ef'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5b5f62'
  on-secondary: '#ffffff'
  secondary-container: '#dde0e3'
  on-secondary-container: '#5f6366'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e0e3e6'
  secondary-fixed-dim: '#c3c7ca'
  on-secondary-fixed: '#181c1f'
  on-secondary-fixed-variant: '#43474a'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#fdf8f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
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
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built upon the pillars of industrial strength, architectural precision, and corporate reliability. It adopts a **Minimalist-Corporate** style that emphasizes structural integrity through a strict grid and generous whitespace. The aesthetic is "Heavy-Duty Premium"—it feels engineered rather than merely decorated. 

The UI should evoke a sense of stability and permanence, mirroring the steel industry. Visuals are kept lean to focus on technical specifications and manufacturing excellence. Expect sharp transitions, clear boundaries, and a "form follows function" philosophy that prioritizes conversion and technical clarity.

## Colors

The palette is rooted in the materials of the industry: charcoal, iron, and steel. 

- **Primary (Deep Charcoal):** Used for typography, navigation bars, and primary buttons to provide a heavy visual anchor.
- **Secondary (Steel Gray):** Used for supporting text, borders, and UI elements that require less emphasis.
- **Accent (Metallic Blue):** Reserved exclusively for high-priority calls-to-action (CTAs), active states, and small success indicators. Its rarity preserves its impact.
- **Neutral (Off-white/White):** Used to create "breathing room" and contrast against the dark primary tones, ensuring the interface feels modern rather than oppressive.

## Typography

The typography system uses **Geist** for headlines and labels to reinforce a technical, monolinear industrial aesthetic. Its geometric construction provides the "engineered" feel required for the brand. **Inter** is used for body copy to ensure maximum readability for long-form technical specifications and corporate information.

- **Headlines:** Always bold or semi-bold with tight letter-spacing to feel impactful and sturdy.
- **Labels:** Set in Geist with slight tracking and uppercase styling for a "blueprinted" look.
- **Body:** Kept clean and neutral with generous line height to balance the heavy headlines.

## Layout & Spacing

The layout follows a rigorous **12-column fixed grid** for desktop, ensuring all elements feel aligned to a structural skeleton. 

- **Grid:** Use a 24px gutter to maintain clear separation between technical modules.
- **Margins:** Large 80px vertical spacing between sections (XL) to emphasize premium positioning and prevent visual clutter.
- **Rhythm:** All spacing units must be multiples of 8px. 
- **Mobile:** Transition to a 4-column fluid grid with 16px margins. Headlines should scale down as defined in the typography tokens to maintain readability without excessive wrapping.

## Elevation & Depth

To maintain the "Industrial-Modern" feel, the system avoids heavy shadows, instead using **tonal layers and low-contrast outlines**.

- **Tiers:** Use background color shifts (White to Off-white) to define different content areas.
- **Borders:** Define elements using 1px solid borders in Steel Gray (#4A4E51) at 20-30% opacity. This mimics technical drawings.
- **Interaction Depth:** For hovering over cards, use a very subtle, tight ambient shadow (Blur: 4px, Y: 2px, Opacity: 5% Black) to suggest a slight lift without breaking the flat, industrial aesthetic.

## Shapes

The shape language is "Soft-Industrial." While the grid is sharp and rigid, UI components use a **subtle 4px to 8px corner radius** (Level 1). This softens the corporate edge just enough to feel modern and accessible while remaining professional.

- **Small elements (Inputs, Buttons):** 4px radius.
- **Large elements (Cards, Modals):** 8px radius.
- **Icons:** Use sharp or slightly rounded geometric icons that match the Geist font weight.

## Components

- **Buttons:** 
    - *Primary:* Deep Charcoal background, White text. High contrast, sharp rectangular presence.
    - *Secondary:* Transparent with a 1px Steel Gray border. 
    - *Accent:* Metallic Blue background for primary conversion points (e.g., "Request Quote").
- **Input Fields:** Flat 1px border with a background color that is slightly darker than the page surface (#EAEAEA). Focus states use the Metallic Blue for a thin 1px outline.
- **Cards:** Used for product categories or service features. No heavy shadows; use the "Steel Gray" border and a White background to stand out against the Off-white page surface.
- **Lists:** Data-heavy lists should use alternating row colors (zebra striping) in very light gray to maintain the industrial spreadsheet-like precision.
- **Chips/Badges:** Use for "In Stock" or "Grade A" indicators. High-contrast labels with the primary Deep Charcoal or subtle Metallic Blue accents.
- **Section Dividers:** Use thin horizontal lines (1px) in Steel Gray to separate content blocks, reinforcing the grid-based layout.