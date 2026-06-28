---
name: Tactical Governance
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
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
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is built on the philosophy of **Tactical Professionalism**. It prioritizes high-stakes utility, authoritative clarity, and rapid cognitive processing for municipal incident management. The aesthetic balances the reliability of institutional governance with the cutting-edge precision of predictive analytics.

The style is **Modern-Corporate with a Tactical Edge**:
- **Clarity over Ornament:** Every visual element serves a functional purpose. Whitespace is used to isolate critical data points, not just for aesthetics.
- **High-Signal Feedback:** A disciplined use of color ensures that "Critical" and "Warning" states are immediately identifiable against a professional, neutral backdrop.
- **Controlled Depth:** Subtle elevation helps users distinguish between global navigation, incident feeds, and high-priority action modals.
- **Predictive Intelligence:** A specific "Surface-Tinted" treatment is used to denote AI-generated insights, separating human-reported data from machine-learning predictions.

## Colors

The palette is designed for high-signal-to-noise ratios. The **Deep Slate (#0F172A)** provides an authoritative anchor for headers and primary navigation, while the **Surface (#FFFFFF)** ensures maximum legibility for data-heavy dashboards.

- **Action Colors:** Officer Blue (#3B82F6) is used for primary actions and informational states. 
- **Status Indicators:** A semantic system (Critical, Warning, Success) is applied strictly to incident status and health metrics. 
- **AI Intelligence:** The Amber tint (#FFFBEB) is a reserved background color for cards or sections containing predictive governance suggestions, alerting the user that the content is machine-generated.

## Typography

This design system utilizes **Inter** for all primary communication due to its exceptional legibility at small sizes and high-pressure environments. For technical metadata, incident IDs, and coordinates, **JetBrains Mono** is introduced to provide a distinct "data" feel that separates raw facts from narrative reports.

- **Headlines:** Use tight letter spacing and semi-bold weights to command attention without occupying excessive vertical space.
- **Body:** Standardized at 14px for density on desktop dashboards, scaling to 16px for field officer mobile views to ensure touch-target legibility.
- **Monospaced Accents:** Use the labels for timestamps, case numbers, and GPS coordinates to enhance the "tactical tool" aesthetic.

## Layout & Spacing

The system employs a **12-column fluid grid** for desktop environments to maximize information density for supervisors. On mobile devices, a single-column stack is used with persistent bottom-bar navigation for field officers.

- **Density:** Dashboards should prioritize a "Compact" density model. Use 8px (stack-sm) and 16px (stack-md) for most internal component spacing.
- **Breakpoints:** 
  - Mobile: < 600px (Margins: 16px)
  - Tablet: 600px - 1024px (Margins: 24px)
  - Desktop: > 1024px (Margins: 32px, Max-width: 1600px)
- **Rhythm:** All spacing must be a multiple of the 4px base unit to maintain a rigorous, engineered alignment.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Precision Shadows**. Because the environment is high-stakes, shadows are kept tight and dark to simulate physical cards placed on a flat surface.

- **Level 0 (Base):** Surface color (#FFFFFF) or light gray background for the app canvas.
- **Level 1 (Cards):** 1px border (#E2E8F0) with a 4px blur, 2% opacity black shadow.
- **Level 2 (Modals/Popovers):** 1px border (#CBD5E1) with a 12px blur, 8% opacity black shadow.
- **Active State:** Elements being dragged or interacted with should use a subtle glow of the Primary color (#0F172A at 10% opacity) instead of a heavy shadow.

## Shapes

The shape language is **Rounded**, utilizing an 8px (0.5rem) base radius. This softens the "industrial" feel of the platform while maintaining a professional structure.

- **Small Components (Buttons, Inputs):** 8px radius.
- **Medium Components (Cards, Modals):** 16px (rounded-lg).
- **Status Indicators (Pills):** Fully rounded (pill-shaped) to distinguish them from interactive buttons.

## Components

- **Buttons:** Primary buttons use Deep Slate (#0F172A) with white text. Ghost buttons use a 1px border. All buttons have a height of 40px on desktop and 48px on mobile for field use.
- **Incident Chips:** High-signal pills. Background color is a 10% tint of the status color (e.g., Critical Red) with 100% opacity text of the same hue for maximum contrast.
- **Input Fields:** Use a 1px slate-200 border that thickens and changes to Officer Blue on focus. Labels use the JetBrains Mono font at 10px, positioned above the field.
- **Data Cards:** Containers for incidents. They must include a vertical "status strip" on the far-left edge (4px wide) that matches the status color (Red, Amber, Green).
- **Predictive Insight Panel:** Cards with a light Amber background (#FFFBEB) and a dashed border to indicate these are "suggestions" rather than "hard facts."
- **Maps:** Use a "Silver" or "Muted" map style to ensure the colored incident markers remain the primary focus of the visual field.