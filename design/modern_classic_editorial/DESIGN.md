---
name: Modern Classic Editorial
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#f0eeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#3d4948'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ec'
  outline: '#6c7a78'
  outline-variant: '#bcc9c8'
  surface-tint: '#006a67'
  primary: '#006a67'
  on-primary: '#ffffff'
  primary-container: '#2eb5b1'
  on-primary-container: '#00413f'
  inverse-primary: '#5dd9d4'
  secondary: '#366664'
  on-secondary: '#ffffff'
  secondary-container: '#b9ece9'
  on-secondary-container: '#3c6c6a'
  tertiary: '#964735'
  on-tertiary: '#ffffff'
  tertiary-container: '#eb8973'
  on-tertiary-container: '#672315'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7cf6f1'
  primary-fixed-dim: '#5dd9d4'
  on-primary-fixed: '#00201f'
  on-primary-fixed-variant: '#00504e'
  secondary-fixed: '#b9ece9'
  secondary-fixed-dim: '#9ed0cd'
  on-secondary-fixed: '#00201f'
  on-secondary-fixed-variant: '#1b4e4c'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#ffb4a4'
  on-tertiary-fixed: '#3d0600'
  on-tertiary-fixed-variant: '#783020'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  caption:
    fontFamily: Work Sans
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
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is built on a "Modern Classic" editorial foundation, blending the intellectual rigor of traditional publishing with the sleek functionalism of modern digital interfaces. It targets an audience that values depth, clarity, and a premium reading experience.

The aesthetic follows a **Minimalist-Editorial** movement. It prioritizes generous whitespace (reminiscent of wide book margins), high-quality serif typography, and a restrained but vibrant color palette. The goal is to evoke a sense of "quiet authority"—a professional environment that feels warm and inviting rather than cold and corporate.

## Colors
The palette is anchored by a warm, paper-like primary surface color (#F5F3EF) which reduces eye strain and provides a sophisticated backdrop. The signature teal (#2EB5B1) serves as the primary action color, providing a modern, energetic counterpoint to the traditional surface.

- **Primary Surface:** #F5F3EF (Light Beige) used for main backgrounds.
- **Action/Accent:** #2EB5B1 (Vibrant Teal) used for primary buttons, active states, and highlights.
- **Deep Accent:** #1A4D4B (Forest Teal) used for hover states on teal elements or high-contrast text accents.
- **Typography:** #1A1A1A for primary headlines; #59544E for secondary body text to maintain softness against the beige background.
- **Semantic Warmth:** A muted terracotta (#D97B66) is used sparingly for secondary accents or notifications to maintain the "warm" editorial feel.

## Typography
The typographic system utilizes a classic "Serif for display, Sans for utility" pairing. 

**Noto Serif** provides the refined, authoritative voice required for storytelling and information hierarchy. It should be used for all headlines and featured pull-quotes. 

**Work Sans** is used for body copy and interface elements. Its neutral, slightly grounded character ensures high legibility and a professional tone. For labels and small metadata, use Work Sans in semi-bold with increased letter spacing and uppercase styling to create a clear visual distinction from narrative text.

## Layout & Spacing
This design system employs a **Fixed Grid** philosophy on desktop to mimic the structured layout of a premium magazine, while transitioning to a fluid model on mobile.

- **Desktop (1440px+):** 12-column grid, 1120px max-width container, 24px gutters. Use large "XL" spacing (80px) between major sections to emphasize the editorial feel.
- **Tablet (768px - 1024px):** 8-column grid with 32px side margins.
- **Mobile (<768px):** 4-column fluid grid with 20px side margins.

Horizontal rhythm should prioritize generous padding within containers to ensure the content never feels crowded. Vertical spacing should follow a strict 8px baseline grid to maintain alignment across disparate columns of text.

## Elevation & Depth
To maintain a "literary" and flat editorial feel, this design system avoids heavy drop shadows. Depth is communicated through **Tonal Layering** and **Fine Outlines**.

- **Surface Levels:** The primary surface is the light beige (#F5F3EF). Elevated elements like cards or modals use a pure white (#FFFFFF) background to subtly pop against the beige.
- **Outlines:** Use 1px solid borders in a slightly darker version of the beige (#E6E2D9) for structural separation.
- **Interaction Depth:** Only "active" floating elements (like dropdowns or primary modals) should use a shadow. These shadows must be "Ambient": very high blur (20px+), low opacity (5-8%), and tinted with the deep teal secondary color to avoid a "dirty" grey look.

## Shapes
The shape language is **Soft (0.25rem)**. This subtle rounding takes the "edge" off the professional interface, making it feel more approachable and inviting without leaning into the playfulness of fully rounded or pill-shaped systems.

- **Standard Buttons & Inputs:** 4px (0.25rem) corner radius.
- **Cards & Large Containers:** 8px (0.5rem) corner radius.
- **Selection Indicators:** Use sharp vertical bars or underlines for the most "editorial" look, specifically for tab states or navigation highlights.

## Components
- **Buttons:** Primary buttons use the signature teal (#2EB5B1) with white text. Secondary buttons should be "Ghost" style: a teal outline with teal text, or a subtle beige-dark fill.
- **Cards:** Cards should have a white background, a 1px #E6E2D9 border, and no shadow. Use generous internal padding (min 24px).
- **Input Fields:** Use a subtle "inset" look with a 1px border. On focus, the border should transition to the signature teal with a 2px weight.
- **Chips/Tags:** Use a slightly darker beige background with Work Sans semi-bold uppercase text. No borders.
- **Lists:** Editorial lists should use Noto Serif for titles and include 1px horizontal dividers between items to reinforce the grid.
- **Pull-quotes:** A specific component for this system—large Noto Serif text, center-aligned or with a thick teal left-border, used to break up long-form body text.