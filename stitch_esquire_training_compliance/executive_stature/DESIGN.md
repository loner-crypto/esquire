---
name: Executive Stature
colors:
  surface: '#f8f9ff'
  surface-dim: '#d8dadf'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3f9'
  surface-container: '#eceef3'
  surface-container-high: '#e7e8ed'
  surface-container-highest: '#e1e2e8'
  on-surface: '#191c20'
  on-surface-variant: '#414750'
  inverse-surface: '#2e3135'
  inverse-on-surface: '#eff0f6'
  outline: '#717781'
  outline-variant: '#c1c7d1'
  surface-tint: '#12629d'
  primary: '#004370'
  on-primary: '#ffffff'
  primary-container: '#005b96'
  on-primary-container: '#abd2ff'
  inverse-primary: '#9ccaff'
  secondary: '#006d33'
  on-secondary: '#ffffff'
  secondary-container: '#75f999'
  on-secondary-container: '#007236'
  tertiary: '#663300'
  on-tertiary: '#ffffff'
  tertiary-container: '#894600'
  on-tertiary-container: '#ffc295'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#9ccaff'
  on-primary-fixed: '#001d35'
  on-primary-fixed-variant: '#00497a'
  secondary-fixed: '#78fc9c'
  secondary-fixed-dim: '#5adf82'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005225'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb781'
  on-tertiary-fixed: '#2f1400'
  on-tertiary-fixed-variant: '#703800'
  background: '#f8f9ff'
  on-background: '#191c20'
  surface-variant: '#e1e2e8'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-padding-desktop: 80px
  section-padding-mobile: 40px
  gutter: 24px
  container-max-width: 1280px
---

## Brand & Style

The design system is engineered for **Esquire Consultants Limited**, targeting high-level corporate decision-makers and institutional stakeholders. The brand personality is **authoritative, precise, and results-driven**, leaning into a **Corporate / Modern** aesthetic that balances traditional consulting reliability with modern digital efficiency.

The visual style prioritizes high-end clarity. It utilizes expansive whitespace to denote "premium space," ensuring that complex information feels digestible and strategic. The interface should evoke a sense of calm confidence—avoiding flashy trends in favor of timeless, structural elegance. Subtle motion and refined transitions reinforce a sense of technological sophistication without compromising the professional gravitas.

## Colors

This design system utilizes a high-trust palette rooted in deep blues and growth-oriented greens.

- **Primary Blue (#005B96):** Used for navigation, primary calls to action, and structural branding. It represents the foundation of professional trust.
- **Primary Green (#00A651):** Reserved for growth indicators, success states, and secondary emphasis. It signals compliance and safety.
- **Light Background (#F5F9FC):** A slightly cooled neutral used for page-wide canvases to reduce eye strain compared to pure white.
- **Dark Text (#1F2937):** A deep charcoal for maximum legibility while appearing softer and more modern than pure black.

## Typography

The design system employs **Inter** for its systematic, utilitarian, and professional qualities. The typography is scaled to ensure a clear hierarchy that guides the user through complex consulting narratives.

- **Headlines:** Use tighter letter spacing and heavier weights to project authority. 
- **Body Text:** Set with generous line heights (1.6) to ensure effortless readability in long-form whitepapers or service descriptions.
- **Labels:** Utilize slight tracking (letter-spacing) and uppercase styling for "overline" categories or small UI metadata to differentiate from body prose.

## Layout & Spacing

This design system follows a **fixed grid** approach for desktop to maintain an executive, editorial feel, transitioning to a fluid model for mobile devices.

- **Grid:** A 12-column grid is used for desktop (1280px max-width) with 24px gutters.
- **Rhythm:** An 8px base unit governs all padding and margins. Vertical rhythm between sections should be aggressive (80px+) to maintain the "premium" feel of whitespace.
- **Adaptive Strategy:** On mobile, margins reduce to 20px, and multi-column layouts stack vertically. Complex data tables should utilize horizontal swiping with persistent header columns.

## Elevation & Depth

To maintain a clean, professional aesthetic, this design system uses **Tonal Layers** combined with **Ambient Shadows**.

- **Surface Strategy:** Backgrounds are `#F5F9FC`. Primary content sits on White (`#FFFFFF`) cards or sections to create a natural "lift."
- **Shadow Character:** Use highly diffused, low-opacity shadows. Avoid harsh edges. The shadows should have a slight blue tint (`rgba(0, 91, 150, 0.08)`) to harmonize with the primary brand color.
- **Interactive Depth:** On hover, cards should transition from a "flat" state to a slightly elevated state (increasing blur and decreasing Y-offset) to signal interactivity without breaking the professional tone.

## Shapes

The design system uses a **Soft** shape language. This provides a modern touch while remaining grounded and corporate.

- **Standard Radius:** 0.25rem (4px) for small components like inputs and checkboxes.
- **Large Radius:** 0.5rem (8px) for containers, cards, and modal windows.
- **Buttons:** Should remain slightly rounded (4px) rather than pill-shaped to maintain a more "structured" and "architectural" appearance.

## Components

### Buttons
- **Primary:** Solid `#005B96` with white text. High-contrast, 4px corner radius.
- **Secondary:** Outlined `#005B96` with 1.5px border weight. 
- **Success:** Solid `#00A651` used sparingly for "Submit" or "Approve" actions.

### Cards
- White background, 8px corner radius, and a 1px stroke of `#E5E7EB` or a very soft ambient shadow. Cards are used to encapsulate service offerings and case studies.

### Input Fields
- Subtle `#F5F9FC` fill with a bottom-only border or a light all-around border that thickens and changes to Primary Blue on focus.

### Chips & Tags
- Used for industry categories (e.g., "Finance," "Compliance"). Small text, uppercase, with a light blue tint background and darker blue text.

### Professional Accents
- **Data Visualizations:** Use the Primary Green for "positive growth" charts and Primary Blue for "stable/structural" data points.
- **Dividers:** Thin 1px lines using `#E5E7EB`, often used to separate list items in long service menus.