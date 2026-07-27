---
name: Vibrant Workspace
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
  on-surface-variant: '#564335'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#897363'
  outline-variant: '#dcc1af'
  surface-tint: '#914c00'
  primary: '#914c00'
  on-primary: '#ffffff'
  primary-container: '#ff8f1c'
  on-primary-container: '#643300'
  inverse-primary: '#ffb77e'
  secondary: '#745c00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd03d'
  on-secondary-container: '#705900'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#adabab'
  on-tertiary-container: '#404040'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77e'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#ffe089'
  secondary-fixed-dim: '#edc22e'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
  sunny-yellow: '#FFD23F'
  deep-ink: '#333333'
  soft-gray: '#8E8E8E'
  paper-white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built for an online workbench that prioritizes joy, accessibility, and high energy. The brand personality is "The Helpful Companion"—approachable, enthusiastic, and unfussy. The target audience includes creative professionals and hobbyists who want a digital space that feels less like a corporate tool and more like a physical, tactile studio.

The design style is **Playful / Illustrative**, drawing inspiration from modern "Neo-Brutalism" but softened with "Kawaii" aesthetics. It features high-contrast thick outlines, vibrant warm gradients, and chunky UI elements that invite interaction. The emotional goal is to reduce "blank page anxiety" by providing a workspace that feels like a toy, encouraging experimentation and play.

## Colors

The palette is dominated by a "Sunrise Spectrum" of oranges and yellows. 
- **Primary Orange (#FF8F1C):** Used for primary actions, branding, and key highlights. It should feel juicy and energetic.
- **Secondary Yellow (#FFD23F):** Used for secondary call-to-outs, background accents, and celebratory UI states.
- **Deep Ink (#333333):** This is the functional foundation. It is used for all "thick outlines" (2px to 3px) and primary text to ensure high legibility and a comic-book feel.
- **Neutral (#F9F9F9):** A slightly warm off-white used for the main workbench surface to reduce eye strain compared to pure white.

Gradients should be used sparingly, primarily moving from the Primary Orange to the Secondary Yellow at a 45-degree angle for hero elements.

## Typography

The typography selection focuses on "Rounded Geometric" forms to mirror the softness of the UI components. 

**Plus Jakarta Sans** is used for headlines and labels. Its open counters and friendly curves maintain a playful tone even at large scales. Bold and Extra Bold weights should be the default for titles to stand up against the thick 3px outlines of the containers.

**Be Vietnam Pro** is used for body text. It offers slightly more technical clarity while maintaining the "warm and contemporary" vibe required for longer reading sessions on a workbench.

All text should avoid pure black; use **Deep Ink (#333333)** to maintain a softer, more organic feel.

## Layout & Spacing

This design system utilizes a **Fluid-Fixed Hybrid Grid**. 
- **Desktop:** 12-column grid with a maximum content width of 1280px. Gutters are fixed at 24px to ensure "breathing room" between the heavily outlined components.
- **Mobile:** Single column with 16px side margins. 

The spacing rhythm follows an 8px base unit. Because the design uses thick borders, padding inside cards and buttons should be slightly generous (minimum 16px) to prevent text from feeling "choked" by the outlines. "White space" in this system isn't just empty; it's a structural element that helps separate high-energy orange components from each other.

## Elevation & Depth

Depth is created through **Tactile Layering** rather than realistic shadows.
- **Outlines:** All primary interactive elements (cards, buttons, inputs) must have a 2px or 3px solid border in **Deep Ink (#333333)**.
- **Soft Shadows:** Instead of blurry ambient shadows, use "Hard-Soft" shadows. These are offsets (e.g., 4px down, 4px right) using a semi-transparent version of the primary color or a muted gray, with a very low blur radius (2-4px). This makes elements look like they are "popping" off the page like stickers.
- **Active State:** When an element is pressed, it should "depress" by removing the shadow offset and translating the element 2px down and right, simulating a physical button click.

## Shapes

The shape language is defined by **Extreme Radii**. There should be no sharp corners in the entire interface. 
- Use **Rounded (0.5rem)** for small components like checkboxes and tags.
- Use **Rounded-LG (1rem)** for standard buttons and input fields.
- Use **Rounded-XL (1.5rem)** for main content cards and modal windows.
- Buttons should frequently utilize **Pill-shaped** ends to emphasize the playful, friendly nature of the workbench.

## Components

- **Buttons:** Use a "chunky" style. Primary buttons are #FF8F1C with a 3px #333333 border and a 4px #333333 hard drop shadow. Text is bold and centered.
- **Cards:** White background with #333333 borders. Cards should feature a "Header" section with a contrasting background color (e.g., #FFD23F) to separate metadata from content.
- **Input Fields:** Large 16px padding, 2px border. On focus, the border thickness increases to 3px and the background shifts to a very light orange tint.
- **Chips/Tags:** Small pill-shaped containers with #333333 borders and bright background colors. Use these for categorizing workbench tasks.
- **Lists:** Items in a list should be separated by thick horizontal lines or placed in individual "mini-cards" to maintain the sticker-like aesthetic.
- **Progress Bars:** Thick, rounded tracks with a vibrant orange fill. The fill should have a subtle "candy stripe" pattern to add to the playful vibe.