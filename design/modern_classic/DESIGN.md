---
name: Modern Classic
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#3d4948'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#6c7a78'
  outline-variant: '#bcc9c8'
  surface-tint: '#006a67'
  primary: '#006a67'
  on-primary: '#ffffff'
  primary-container: '#2eb5b1'
  on-primary-container: '#00413f'
  inverse-primary: '#5dd9d4'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5e5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#a4a3a3'
  on-tertiary-container: '#393a3a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7cf6f1'
  primary-fixed-dim: '#5dd9d4'
  on-primary-fixed: '#00201f'
  on-primary-fixed-variant: '#00504e'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Noto Serif
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Noto Serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1120px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 80px
---

## Brand & Style
This design system is crafted for an author and mentor whose work bridges the gap between traditional literary excellence and contemporary professional guidance. The brand personality is intellectual, poised, and deeply dependable. It draws from a **Minimalist** philosophy to ensure the focus remains on written content and book photography, while borrowing structural discipline from **Modern Corporate** design.

The aesthetic evokes the feeling of a premium physical book: high-quality paper, thoughtful margins, and crisp, authoritative ink. It avoids fleeting trends in favor of a timeless, "editorial-first" layout that establishes a sense of legacy and quiet confidence.

## Colors
The palette is built on a foundation of "Gallery Neutrals." These shades are designed to recede, providing a sophisticated backdrop that allows colorful book covers and photography to command attention. 

- **Primary Teal (#2EB5B1):** Reserved exclusively for moments of action and significance—Primary CTAs, active navigation indicators, and key links. 
- **Deep Charcoal (#1A1A1A):** Used for primary headings and body text to ensure maximum legibility and a sense of permanence.
- **Soft White & Elegant Grey:** Used for background surfaces and subtle containment borders to define the UI without cluttering the visual field.

## Typography
Typography is the cornerstone of this design system. **Noto Serif** is utilized for headlines and long-form body text to provide an editorial rhythm that feels both academic and accessible. 

For functional UI elements like buttons, tags, and small metadata, a clean, neutral sans-serif (**Inter**) is introduced. This creates a "Modern Classic" tension—the serif handles the storytelling and wisdom, while the sans-serif handles the utility and navigation. Use ample line height for body text to ensure a comfortable, book-like reading experience.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop to mimic the structured columns of a luxury periodical. 

- **Desktop:** A 12-column grid with a narrow max-width of 1120px to prevent line lengths from becoming too long for comfortable reading.
- **Tablet:** 8-column grid with reduced margins.
- **Mobile:** 4-column grid with a focus on vertical stack-based spacing.

Generous white space (Section Gaps) is mandatory to separate different thematic areas of the site, preventing the content-heavy pages from feeling overwhelming or cluttered.

## Elevation & Depth
In keeping with the classic aesthetic, depth is achieved through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows. 

Surfaces should feel flat and physical. Use subtle 1px borders in Light Grey (#E5E5E5) to define card boundaries or content sections. If depth is required for a floating element (like a dropdown menu), use a very soft, diffused ambient shadow with 5% opacity and no color tinting. This maintains the "paper-on-table" feel rather than a "screen-in-space" feel.

## Shapes
The design system utilizes **minimal roundness (4px)** for all interactive elements and containers. This slight softening prevents the UI from feeling sharp or aggressive while maintaining the architectural rigor of a classic design. 

Large containers, such as hero image sections or content cards, should adhere to this 4px rule. Circular shapes are reserved strictly for user avatars or specific decorative icon backgrounds to provide a rare, soft counterpoint to the otherwise rectangular structure.

## Components
- **Buttons:** Primary buttons use the Teal (#2EB5B1) background with white text. Secondary buttons use a transparent background with a Charcoal border and text. All buttons use the `label-md` typography style (uppercase Inter).
- **Cards:** Cards for book listings or blog posts should have a white background, a 1px Grey border, and no shadow. The focus is on the thumbnail image and the Noto Serif headline.
- **Navigation:** Active states in the navigation bar are indicated by a 2px Teal bottom border or a Teal text color change.
- **Input Fields:** Use a Soft White background and a 1px Grey border. On focus, the border transitions to Teal.
- **Chips/Tags:** Used for categorizing content (e.g., "Leadership," "Fiction"). These should be light grey with Inter text, staying humble so they do not compete with the Primary CTA.
- **Quote Blocks:** A signature component. Large Noto Serif text, italicized, with a thick Teal vertical accent line to the left to highlight the author's voice.