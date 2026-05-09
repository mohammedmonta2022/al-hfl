---
name: Noor Al-Bayan
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#3f4943'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#6f7972'
  outline-variant: '#bfc9c1'
  surface-tint: '#1c6b4c'
  primary: '#00432c'
  on-primary: '#ffffff'
  primary-container: '#045d3f'
  on-primary-container: '#89d4ad'
  inverse-primary: '#8bd6b0'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#3a3a35'
  on-tertiary: '#ffffff'
  tertiary-container: '#52514b'
  on-tertiary-container: '#c6c4bc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a6f3cb'
  primary-fixed-dim: '#8bd6b0'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#474741'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Source Sans 3
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Source Sans 3
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
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
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1200px
---

## Brand & Style

The brand personality is rooted in the concepts of "Noor" (Light) and "Bayan" (Eloquence). It aims to evoke a sense of spiritual tranquility, intellectual clarity, and cultural pride. This design system bridges the gap between ancient manuscript traditions and modern instructional design, targeting students and educators who value both sacred aesthetics and academic rigor.

The visual style is a sophisticated blend of **Tactile Skeuomorphism** and **Minimalism**. It utilizes high-quality parchment textures and gold-leaf accents to reference historical Islamic manuscripts, while maintaining a clean, spacious layout that ensures the educational content remains the primary focus. The emotional response is intended to be one of "Sakinah" (inner peace) and focused curiosity.

## Colors

This design system utilizes a palette that conveys prestige and heritage. 

*   **Emerald Green (#045D3F):** The primary color, representing life, growth, and the Islamic identity. It is used for primary actions, navigational headers, and key emphasis.
*   **Deep Gold (#C5A059):** The secondary color, used for ornamental details, calligraphic flourishes, and high-level structural borders. It should be applied with restraint to maintain its premium feel.
*   **Ivory Cream (#F9F6EE):** The foundational surface color. This replaces pure white to reduce eye strain and provide a parchment-like warmth.
*   **Charcoal Onyx (#2D2926):** The neutral color for text and deep shadows, ensuring high legibility against the cream background.

Backgrounds should occasionally feature a "Subtle Parchment" texture (a low-opacity grain overlay) to add tactile depth.

## Typography

The typography strategy employs a "Sacred vs. Secular" contrast. 

For **Headlines**, we use **EB Garamond**. It mirrors the strokes of classical Arabic calligraphy (Amiri style) while maintaining exceptional legibility in Latin scripts. All major Arabic text should be rendered in **Amiri**, sized 20% larger than its English counterpart to balance optical weight.

For **Body and Instructional text**, we use **Source Sans 3**. This provides a neutral, highly readable counterpoint to the decorative headlines, ensuring that students can process information without fatigue. 

Labels and captions use uppercase Source Sans 3 with increased letter spacing to create an "engraved" look for metadata.

## Layout & Spacing

This design system follows a **Fixed Grid** philosophy to mirror the structured nature of a printed manuscript or a traditional classroom board. 

*   **Desktop:** A 12-column grid with a maximum container width of 1200px. Gutters are kept wide (24px) to allow the "ivory" space to breathe.
*   **Margins:** Large external margins (64px on desktop) are used to frame the content, creating the effect of a centered scroll or book page.
*   **Rhythm:** Vertical spacing follows an 8px base unit. Section headers always have double the bottom margin of body paragraphs to signify a clear change in lesson topic.

Arabesque patterns should be used as "Safe Area" decorations, appearing in the corners of the grid or as subtle dividers between major content sections.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Gold Accents** rather than aggressive shadows.

1.  **Base Layer:** The Ivory Cream (#F9F6EE) serves as the primary canvas.
2.  **Surface Layer:** Content cards and instructional blocks use a slightly lighter cream or pure white with a 1px solid border in Gold (#C5A059) at 30% opacity.
3.  **Elevation:** When an element requires focus (like a modal or a floating action button), use an **Ambient Shadow**. The shadow is tinted with the Primary Green (#045D3F) at a very low opacity (10%), with a high blur radius (20px) to create a soft, spiritual glow rather than a harsh physical lift.
4.  **Dividers:** Use horizontal rules featuring a center-aligned Islamic geometric motif in gold leaf.

## Shapes

The shape language is disciplined and traditional. We use **Soft (0.25rem)** roundedness to reflect the gentle curves of calligraphy while maintaining the structure of a formal document.

*   **Buttons & Inputs:** Use the base `rounded` (4px) setting.
*   **Feature Cards:** May use `rounded-lg` (8px) to soften the appearance of large instructional blocks.
*   **Decorative Frames:** Often utilize a "clipped corner" or "arched top" (Mihrab style) for specific educational highlights or quote blocks, distinguishing them from standard UI elements.

## Components

### Buttons
Primary buttons are solid Emerald Green with Deep Gold text or icons. Secondary buttons use a Deep Gold outline with Ivory background. Interactions should be subtle; a slight darkening of the green or a soft gold glow on hover.

### Cards (The "Lesson Block")
Cards are the primary container for educational content. They feature a 1px Gold border and a subtle Arabesque pattern watermark in the bottom-right corner (opacity 5%). 

### Chips & Tags
Used for categorizing subjects (e.g., "Tajweed", "Fiqh"). These are pill-shaped with a light green tint background and dark green text, keeping them distinct from the more formal rectangular cards.

### Input Fields
Inputs use a "line-only" style or a very light gold border. When focused, the bottom border thickens and transitions to Emerald Green.

### Progress Indicators
Educational progress is shown via a "Golden Thread" linear bar—a deep gold line that fills with emerald green as the student completes lesson modules.

### Animation Style
Revelations of text should use a "Fade and Slide Up" motion with a long duration (600ms) and a Cubic Bezier curve (0.22, 1, 0.36, 1) to feel "smooth and graceful." Page transitions should mimic the soft wipe of a parchment leaf turning.