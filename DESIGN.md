---
name: ApexCare Visual Language
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8d9e3'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fd'
  surface-container: '#ecedf7'
  surface-container-high: '#e6e7f2'
  surface-container-highest: '#e1e2ec'
  on-surface: '#191b23'
  on-surface-variant: '#424754'
  inverse-surface: '#2e3038'
  inverse-on-surface: '#eff0fa'
  outline: '#727785'
  outline-variant: '#c2c6d6'
  surface-tint: '#005ac2'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2170e4'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#545f6f'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f3'
  on-secondary-container: '#586373'
  tertiary: '#545c70'
  on-tertiary: '#ffffff'
  tertiary-container: '#6d7489'
  on-tertiary-container: '#fefcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#d8e3f6'
  secondary-fixed-dim: '#bcc7da'
  on-secondary-fixed: '#111c2a'
  on-secondary-fixed-variant: '#3d4857'
  tertiary-fixed: '#dbe2fa'
  tertiary-fixed-dim: '#bfc6dd'
  on-tertiary-fixed: '#141b2c'
  on-tertiary-fixed-variant: '#3f4759'
  background: '#f9f9ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ec'
typography:
  display:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-sm:
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
  display-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The brand identity for this design system centers on "Precision with Empathy." It targets a high-end demographic seeking dental care that feels technically advanced yet approachable and serene. The aesthetic is **Modern Minimalist**, utilizing a "Medical-Chic" approach that avoids the sterile coldness of traditional clinics in favor of a bright, airy, and premium atmosphere.

The emotional response should be one of immediate relief and trust. By prioritizing generous whitespace and a restricted color palette, the UI communicates clarity and organizational excellence. The inclusion of soft gradients adds a layer of depth and modernity, moving the brand away from a static institutional look toward a dynamic, tech-forward healthcare experience.

## Colors

The palette is anchored by **Deep Navy Blue (#1e2937)**, used for primary typography to ensure high legibility and an authoritative tone. **Accent Blue (#3b82f6)** serves as the primary action color, providing a clear visual signal for interactivity.

The secondary character of the design comes from **Soft Purple-Blue Gradients**. These should be used sparingly for hero backgrounds, subtle card overlays, or decorative elements to soften the clinical edge of the UI. The background remains **Pure White (#ffffff)** to maximize "breathability," while an **Off-White (#f8fafc)** surface color is used to define distinct content sections without the need for heavy borders.

## Typography

This design system utilizes **Inter** across all levels to maintain a cohesive, systematic, and utilitarian feel. The hierarchy is driven by significant scale contrasts—headlines are oversized and bold to command attention and convey confidence.

- **Headlines:** Use tight letter-spacing on larger sizes to create a modern, high-fashion editorial look.
- **Body Text:** Set with generous line height (1.6) to ensure maximum readability for patients of all ages.
- **Labels:** Utilize a slightly increased letter-spacing and uppercase styling for small metadata or section eyebrows to provide clear visual anchors.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered on a 1280px container with a 12-column structure. A hallmark of this design system is "Extreme Whitespace"—section headers should be preceded by 120px of vertical padding to ensure no two primary concepts compete for attention.

- **Mobile:** Transition to a 4-column grid with 20px side margins.
- **Rhythm:** All spacing units must be multiples of 8px. 
- **Alignment:** Text heavy content should be left-aligned to maintain a clean, structured vertical axis. Use centered layouts only for hero introductions or simple call-to-action sections.

## Elevation & Depth

To maintain a minimalist profile, this design system avoids heavy shadows. Depth is communicated through **Ambient Shadows** and **Tonal Layers**:

1.  **Level 0 (Base):** Pure White (#ffffff).
2.  **Level 1 (Sub-surface):** Off-White (#f8fafc) used for large background containers to segment page areas.
3.  **Level 2 (Cards/Floating):** Use an extremely diffused shadow: `0px 10px 30px rgba(30, 41, 55, 0.04)`. The shadow should feel like a soft glow of light blocked by the element rather than a dark silhouette.
4.  **Glassmorphism:** For sticky navigation bars, use a backdrop blur (20px) with 80% opacity white background to maintain context of the content scrolling beneath.

## Shapes

The shape language is primarily **Rounded**, conveying friendliness and approachability. 
- **Standard Cards/Inputs:** Use a 0.5rem (8px) radius.
- **Primary Buttons/Chips:** Use **Pill-shaped** (full round) styling. This contrast between the structured 8px corners of cards and the fully round buttons helps interactive elements stand out as more "organic" and touchable.
- **Iconography:** Icons should feature rounded caps and corners, avoiding sharp 90-degree angles.

## Components

### Buttons
- **Primary:** Pill-shaped, Accent Blue (#3b82f6) background, white text. Bold weight.
- **Secondary:** Pill-shaped, transparent background with a 1px border of Accent Blue.
- **Ghost:** Pill-shaped, no border, Deep Navy text. Used for less prominent actions like "Cancel" or "Learn More."

### Inputs & Forms
Input fields use an 8px corner radius with a light gray border (#e2e8f0). On focus, the border transitions to Accent Blue with a subtle 4px outer glow of the same color at 10% opacity.

### Cards
Cards are the primary container for services and testimonials. They should have no visible border, utilizing the Ambient Shadow defined in the Elevation section. Padding within cards should be generous (min 32px).

### Specialist Components
- **Appointment Picker:** A clean, grid-based calendar using the Soft Purple gradient to highlight the selected date.
- **Service Chips:** Pill-shaped tags using the secondary purple-blue gradient as a very faint background (10% opacity) to categorize dental services (e.g., "Cosmetic," "Surgical").
- **Trust Bar:** A horizontal strip of logos (insurance partners) rendered in grayscale with 50% opacity, returning to full color on hover.