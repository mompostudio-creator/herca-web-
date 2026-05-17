---
name: Apex Prestige
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#d2c4b9'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#9b8f84'
  outline-variant: '#4e453d'
  surface-tint: '#e3c19f'
  primary: '#e3c19f'
  on-primary: '#412c14'
  primary-container: '#c4a484'
  on-primary-container: '#503a21'
  inverse-primary: '#735a3e'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#a9aaaa'
  on-tertiary-container: '#3d3f3f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddbb'
  primary-fixed-dim: '#e3c19f'
  on-primary-fixed: '#291803'
  on-primary-fixed-variant: '#5a4229'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 80px
---

## Brand & Style

The design system is engineered for an elite performance environment, blending the raw discipline of professional athletics with the refined elegance of a luxury club. The aesthetic is built on high-contrast tension—deep shadows meeting crisp whites, punctuated by a sophisticated tan that evokes heritage and quality.

The style leans into **High-Contrast Minimalism**. It prioritizes precision over ornamentation, utilizing expansive whitespace (or "dark space") and razor-sharp typography to create a sense of focused intensity. Every element should feel intentional, meticulously placed, and structurally sound, reflecting the high-performance outcomes expected of the framework's users.

## Colors

This design system utilizes a "High-Contrast Triad" palette. The primary brand color, **Light Brown (#C4A484)**, acts as the signature of quality and should be used for critical actions, highlights, and status indicators that denote "premium" status.

The background strategy is binary: **Deep Charcoal (#131313)** serves as the primary canvas to evoke focus and exclusivity, while **Pure White (#FFFFFF)** is used for high-impact content sections or editorial-style components to provide visual relief and clarity. Grays are kept to a minimum, used only for subtle borders and secondary text to maintain the stark, professional aesthetic.

## Typography

The typography pairing reflects the "Elite Performance" narrative. **Syne** is used for headlines to provide a distinctive, contemporary edge; its wider proportions suggest confidence and presence. Weights should be kept at Medium (500) to Bold (700) to maintain an authoritative tone without becoming bulky.

**Hanken Grotesk** serves as the workhorse for body and functional text. It is a sharp, modern sans-serif that ensures high legibility in data-dense performance tracking views. Use uppercase labels with generous letter-spacing for category headers and metadata to reinforce the organized, professional club aesthetic.

## Layout & Spacing

The layout is built on a strict **8px square grid**, ensuring mathematical precision in every component. A 12-column fixed grid is used for desktop layouts to maintain a centralized, focused reading experience, while tablet and mobile transition to a fluid layout with safe-area margins.

Large vertical spacing (Section Padding) is encouraged to separate different training modules or content blocks, allowing the "Elite" nature of the content to breathe. Use the base unit of 8px for all internal component padding to maintain a rhythmic, structured appearance.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layering** and **High-Contrast Outlines** rather than traditional shadows. On the charcoal background, surfaces are elevated by using a slightly lighter neutral (#262626) or by applying a 1px solid stroke in the primary tan color.

Where shadows are necessary for functional overlays (like modals), they should be "Ambient Shadows"—extremely diffused, large-radius, and low-opacity (#000000 at 40%) to ensure they feel like natural depth rather than a UI effect. Glassmorphism should be used sparingly, reserved only for navigation bars to maintain context of the background content.

## Shapes

The shape language is **"Architectural."** We use a Soft roundedness (Level 1) to take the edge off the high-contrast visuals without losing the feeling of structural integrity. 

- **Primary Buttons:** Subtle 4px (0.25rem) radius.
- **Cards & Containers:** 8px (0.5rem) radius for a grounded, solid feel.
- **Interactive Tags:** Pill-shaped (fully rounded) only when used as status indicators to differentiate them from actionable buttons.

## Components

### Buttons
Primary buttons use a solid fill of #C4A484 with #131313 text for maximum contrast. Secondary buttons are outlined in 1px #C4A484 or #FFFFFF. Use "Syne" in Medium weight for button labels to maintain the premium feel.

### Cards
Performance cards should have a #131313 background with a subtle 1px border (#262626). For "featured" or "active" states, the border should transition to the primary brand color (#C4A484).

### Input Fields
Inputs are minimalist: a bottom-border-only style or a very thin outlined box. The focus state must be a clear #C4A484 border transition. Placeholder text should be low-contrast to keep the UI clean.

### Lists & Data
For performance metrics, use high-contrast white text for values and the primary tan for units (e.g., **185** lbs). Ensure ample row height (minimum 56px) for list items to allow for clear tap targets and a premium, uncrowded feel.

### Progress Indicators
Progress bars should use the Charcoal (#131313) as the track and the Primary Tan (#C4A484) as the fill. The motion should be smooth and linear to reflect steady athletic progression.