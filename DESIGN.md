---
name: Obsidian & Indigo
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#b9c8de'
  on-tertiary: '#233143'
  tertiary-container: '#8392a6'
  on-tertiary-container: '#1c2b3c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#d4e4fa'
  tertiary-fixed-dim: '#b9c8de'
  on-tertiary-fixed: '#0d1c2d'
  on-tertiary-fixed-variant: '#39485a'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
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
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
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
---

## Brand & Style
The brand personality is authoritative yet innovative, reflecting a high-end development boutique that prioritizes technical precision and aesthetic excellence. The target audience includes tech-forward founders and enterprise product teams looking for bespoke engineering solutions.

The design system adopts a **Modern Corporate** aesthetic with strong **Glassmorphism** and **Minimalist** influences. It utilizes a deep, nocturnal palette to establish a premium "Pro" feel, punctuated by vibrant, high-energy accents that draw the eye to calls-to-action. The emotional response should be one of absolute trust, perceived speed, and cutting-edge capability.

## Colors
The color strategy is built on a "Dark Mode First" philosophy to convey sophistication and focus. 

- **Primary (Electric Indigo):** Used for primary actions, active states, and brand-critical highlights.
- **Secondary (Cyber Cyan):** Reserved for technical callouts, success states, and subtle gradient shifts to add depth to the indigo.
- **Neutral (Slate Grays):** A hierarchy of grays starting from `#F8FAFC` for high-contrast titles down to `#94A3B8` for secondary body text.
- **Surface:** The primary canvas is `#020617` (Obsidian), with nested containers using `#0F172A` (Charcoal) to create a sense of physical layering.

## Typography
The typography system pairs the geometric, wide-stanced **Sora** for headlines with the utilitarian clarity of **Inter** for long-form content. 

To emphasize the development focus, **JetBrains Mono** is used sparingly for technical labels, metadata, and "code-inspired" decorative elements. Headlines should use tight tracking and generous line heights to maintain a "SaaS landing page" editorial feel. Ensure all body text maintains at least a 4.5:1 contrast ratio against the obsidian background for accessibility.

## Layout & Spacing
The layout follows a **Fluid Grid** model with a maximum container width of 1280px for desktop. It utilizes a 12-column structure with 24px gutters.

- **Desktop:** Section vertical spacing is aggressive (120px+) to create a "luxury" feel through whitespace.
- **Mobile:** Margins shrink to 20px, and section gaps reduce to 64px. 
- **Rhythm:** Spacing should follow a 4px/8px baseline shift. Use larger internal padding (32px-48px) within cards to maintain the airy, premium aesthetic.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Tonal Layering** rather than traditional shadows.

1.  **Level 0 (Base):** Obsidian `#020617` background.
2.  **Level 1 (Cards):** Charcoal `#0F172A` with a 1px solid border at 10% opacity white.
3.  **Level 2 (Overlays/Modals):** Semi-transparent background (80% opacity) with a 24px backdrop blur.
4.  **Accents:** Subtle radial gradients (15% opacity Indigo) are placed behind key components to create a soft "glow" effect, simulating a light source behind the UI.

## Shapes
The design system uses a **Rounded** (8px) corner radius as the standard. This strikes a balance between the precision of sharp corners and the modern friendliness of rounded UI.

- **Standard Buttons/Inputs:** 8px (`0.5rem`)
- **Main Cards:** 16px (`1rem`)
- **Avatars/Feature Icons:** Circular (Full pill)
- **Code Snippets:** 4px (`0.25rem`) to maintain a technical, structured appearance.

## Components
- **Buttons:** Primary buttons use a solid Electric Indigo fill with white text. Secondary buttons use a "ghost" style with a 1px border and a subtle hover fill.
- **Cards:** Portfolio cards should feature a subtle gradient border and a backdrop blur effect when hovering over images.
- **Input Fields:** Dark background (#0F172A), 1px slate-800 border, and Cyber Cyan focus rings.
- **Chips/Labels:** Use JetBrains Mono for the text within chips. Backgrounds should be low-opacity Indigo with high-opacity text.
- **Portraits:** Professional headshots should be styled with a slight desaturation or a cool-toned overlay to match the Obsidian theme.
- **Code Indicators:** Small "Status" dots (using Cyber Cyan) next to text to indicate "Live" or "Active" projects, nodding to developer environments.