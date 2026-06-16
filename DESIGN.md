---
name: AgroFlow Digital
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
  on-surface-variant: '#3e4a3d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6e7b6c'
  outline-variant: '#bdcaba'
  surface-tint: '#006e2d'
  primary: '#006b2c'
  on-primary: '#ffffff'
  primary-container: '#00873a'
  on-primary-container: '#f7fff2'
  inverse-primary: '#62df7d'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#a72d51'
  on-tertiary: '#ffffff'
  tertiary-container: '#c74668'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7ffc97'
  primary-fixed-dim: '#62df7d'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005320'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2bf'
  on-tertiary-fixed: '#3f0016'
  on-tertiary-fixed-variant: '#8a143c'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  h1:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h1-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Montserrat
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
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is engineered for a high-tech B2B irrigation brand, balancing industrial reliability with digital precision. The brand personality is authoritative yet accessible, positioning itself as a partner in modernizing agricultural infrastructure.

The visual style follows a **Corporate / Modern** direction with subtle **Minimalist** influences. It prioritizes clarity and functional efficiency, using generous whitespace to signal a premium, organized experience. The aesthetic avoids "folksy" agricultural tropes in favor of a clean, engineering-led look that builds trust with large-scale commercial farm operators and technical distributors.

## Colors

The palette is rooted in the "Agriculture Green" primary color, which represents vitality and growth, paired with "Water Blue" to represent irrigation and fluid management. 

- **Primary (#16a34a):** Used for main actions, brand identifiers, and success states.
- **Secondary (#3b82f6):** Used for technical data visualizations, water-related features, and secondary call-outs.
- **Backgrounds:** A crisp white (#ffffff) is used for primary cards and content areas, while the light gray (#f9fafb) provides structural separation for the main application background.
- **Neutrals:** Grays are strictly cool-toned to maintain the high-tech, professional feel.

## Typography

This design system utilizes a dual-font strategy to distinguish between brand presence and functional utility. 

**Montserrat** is reserved for headings. Its geometric construction provides a strong, modern foundation that feels architectural and stable. **Inter** is the workhorse for all body text, data displays, and labels, chosen for its exceptional legibility in complex B2B dashboards and technical specifications.

For technical data (such as flow rates or pressure metrics), ensure Inter's tabular num features are enabled to allow for clear vertical alignment of figures.

## Layout & Spacing

The layout is built on a **12-column fluid grid** for desktop and a **4-column grid** for mobile. A 4px baseline shift ensures all components scale predictably.

- **Desktop:** 1280px max-width container with 24px gutters. Content should be grouped in cards that span 3, 4, 6, or 12 columns.
- **Mobile:** 16px side margins. Layouts should reflow to a single column for readability, especially for technical data tables which should implement horizontal scrolling with a fixed first column.
- **Rhythm:** Use "md" (16px) for internal card padding and "lg" (24px) for spacing between major sections.

## Elevation & Depth

To maintain a professional B2B aesthetic, the design system uses **Tonal Layers** supplemented by **Low-Contrast Outlines**.

- **Level 0:** Base background (#f9fafb).
- **Level 1:** Content cards (#ffffff) with a 1px solid border (#e5e7eb). No shadow.
- **Level 2 (Hover/Interaction):** Content cards with a very soft, ambient shadow (Y: 4, Blur: 12, Opacity: 0.05, Color: Neutral-900).
- **Level 3 (Modals/Overlays):** Defined by a sharp 1px border and a medium-diffused shadow to separate the element from the backdrop blur.

Avoid heavy shadows or neomorphic effects; depth should feel structural rather than decorative.

## Shapes

The design system adopts a **Soft** shape language. This provides enough rounding to feel modern and approachable without losing the precision required for a high-tech engineering brand.

- **Standard Elements:** 0.25rem (4px) corner radius for input fields, small buttons, and checkboxes.
- **Cards & Containers:** 0.5rem (8px) for `rounded-lg` to create a clear container hierarchy.
- **Visual Accents:** Icons and status indicators should maintain consistent 4px rounding to match the UI components.

## Components

### Buttons
Primary buttons use a solid Agriculture Green (#16a34a) with white text. Secondary buttons use a Water Blue (#3b82f6) outline or ghost style. All buttons have a height of 44px for high touch-target reliability in field conditions.

### Inputs & Forms
Form fields use a white background with a 1px border (#e5e7eb). On focus, the border shifts to Water Blue (#3b82f6) with a 2px outer glow (ring) of the same color at 20% opacity. Labels are always positioned above the input in Inter SemiBold.

### Chips & Status Indicators
Used for system statuses (e.g., "Active," "Leaking," "Offline"). 
- **Active:** Green tint background with Primary Green text. 
- **Warning:** Amber tint background with Dark Amber text.
- **System Info:** Blue tint background with Secondary Blue text.

### Cards
Cards are the primary container for irrigation zone data and system health. They must feature a 1px border and 8px rounded corners. Header areas within cards should use a light gray (#f9fafb) subtle top-fill to separate "Title/Controls" from "Data/Content."

### Data Visualization
Charts should prioritize clarity. Use the Primary Green for "current/actual" metrics and Secondary Blue for "target/optimal" water levels. Ensure high contrast for all data points to remain legible under sunlight on mobile devices.