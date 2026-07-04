---
name: Editorial Prime
colors:
  surface: '#fbf8ff'
  surface-dim: '#dbd9e1'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2fb'
  surface-container: '#efecf5'
  surface-container-high: '#eae7ef'
  surface-container-highest: '#e4e1ea'
  on-surface: '#1b1b21'
  on-surface-variant: '#454652'
  inverse-surface: '#303036'
  inverse-on-surface: '#f2eff8'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#380b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c1800'
  on-tertiary-container: '#e17c5a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#7b2e12'
  background: '#fbf8ff'
  on-background: '#1b1b21'
  surface-variant: '#e4e1ea'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Newsreader
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  meta:
    fontFamily: Work Sans
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
  base: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  container-margin: 20px
  card-gap: 24px
---

## Brand & Style

The brand identity is rooted in journalistic integrity and modern professionalism. This design system targets a sophisticated audience that values clarity, depth, and a focused reading experience. The UI evokes a sense of calm authority, moving away from the "attention-economy" clutter of typical news aggregators toward a curated, editorial feel.

The design style is **Minimalism** blended with **Corporate Modern** sensibilities. It prioritizes content hierarchy through generous negative space and a rigorous typographic grid. Visual embellishments are stripped back to ensure the reporting remains the focal point, utilizing subtle structural elements rather than heavy decorative features to guide the user's eye.

## Colors

The palette is anchored by **Professional Deep Blue (#1A237E)**, used strategically for primary actions, branding, and high-level navigation to instill trust. The background remains a pristine **White**, ensuring maximum contrast for long-form reading. 

**Slate Gray** serves as the secondary color, providing a soft hierarchy for metadata and captions without distracting from the main narrative. A tertiary accent of deep burnt orange is reserved for breaking news alerts or "Live" indicators to provide a functional contrast to the cool primary tones. Grayscale values are strictly neutral to maintain a professional, unbiased aesthetic.

## Typography

This design system employs a classic "Serif for Headlines, Sans-serif for Body" pairing. **Newsreader** is selected for headlines to provide a traditional, authoritative voice reminiscent of prestige broadsheets. Its variable weights allow for expressive display sizes and sturdy smaller headings.

**Work Sans** is used for all functional and body text. Its optimized legibility and professional character make it ideal for extended reading on mobile screens. A strict vertical rhythm is maintained, with body text utilizing a generous line-height to prevent reader fatigue. Uppercase labels are used sparingly for category badges to create a distinct visual texture compared to news titles.

## Layout & Spacing

The layout follows a **Fluid Grid** model optimized for mobile viewports, utilizing a 4-column structure with 20px outer margins. The spacing rhythm is based on a 4px baseline, but defaults to "Generous" increments (16px and 24px) to ensure the UI feels airy and unhurried.

Content is organized vertically with clear section breaks. Headlines and body copy are given significant breathing room (24px to 32px) to prevent the "wall of text" effect. Layouts should prioritize a single-column flow for articles, while the home feed uses card-based containers to separate distinct news items.

## Elevation & Depth

To maintain the editorial aesthetic, depth is conveyed through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows. The primary surface is pure white, while secondary sections or "Editors' Picks" may sit on a subtle Slate-50 background.

Cards use a very fine, 1px border in a light slate tint to define their boundaries. Shadows, when used for high-level modals or floating action buttons, are extremely diffused and low-opacity (2-4%), functioning more as a soft glow to indicate interactability rather than physical height. This keeps the interface feeling "flat" and printed, honoring its newspaper heritage.

## Shapes

The shape language is **Soft** and restrained. A base radius of 4px (0.25rem) is applied to cards and buttons to take the "edge" off the design without making it feel overly playful or "bubbly." 

Category badges use slightly more rounded corners to distinguish them as interactive chips, but stay within the professional theme. Image containers must maintain the same radius as their parent cards to preserve a cohesive, architectural structure.

## Components

- **Cards:** The primary vehicle for news items. They feature a vertical stack: Image (top), Category Badge (overlay or top-left), Headline (serif), and Meta-data (time/author). A subtle 1px border defines the container.
- **Category Badges:** Small, rectangular chips with uppercase text. Use the Primary Deep Blue for active/selected states and a light Slate Gray for neutral states.
- **Buttons:** Primary buttons are solid Deep Blue with white Work Sans text. Secondary buttons are outlined. All buttons use the base 4px radius.
- **Navigation:** A minimalist bottom tab bar using thin-stroke icons and 12px labels. The active state is indicated by the Primary Deep Blue color, while inactive states remain Slate Gray.
- **Input Fields:** Clean, underlined or lightly boxed fields with 16px padding. Focused states transition the border color to Deep Blue.
- **Progress Indicator:** A thin 2px line at the top of article pages to indicate reading progress, using the Primary Deep Blue.
- **Pull Quotes:** Stylized Serif text, larger than body copy, with a vertical Deep Blue accent bar on the left margin to break up long-form content.