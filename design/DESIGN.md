---
name: Volt Energy
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c9c8ab'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#929277'
  outline-variant: '#474832'
  surface-tint: '#c7cf00'
  primary: '#ffffff'
  on-primary: '#303300'
  primary-container: '#e3ec00'
  on-primary-container: '#646900'
  inverse-primary: '#5e6300'
  secondary: '#d7ffc5'
  on-secondary: '#053900'
  secondary-container: '#2ff801'
  on-secondary-container: '#0f6d00'
  tertiary: '#ffffff'
  on-tertiary: '#00363d'
  tertiary-container: '#9cf0ff'
  on-tertiary-container: '#006f7c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e3ec00'
  primary-fixed-dim: '#c7cf00'
  on-primary-fixed: '#1c1d00'
  on-primary-fixed-variant: '#474a00'
  secondary-fixed: '#79ff5b'
  secondary-fixed-dim: '#2ae500'
  on-secondary-fixed: '#022100'
  on-secondary-fixed-variant: '#095300'
  tertiary-fixed: '#9cf0ff'
  tertiary-fixed-dim: '#00daf3'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#004f58'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-xl:
    fontFamily: anybody
    fontSize: 80px
    fontWeight: '900'
    lineHeight: '1.0'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: anybody
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: anybody
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-md:
    fontFamily: anybody
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  body-lg:
    fontFamily: montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: spaceGrotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  label-mono:
    fontFamily: spaceGrotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
This design system embodies high-octane performance and urban sophistication. It is designed for the hyper-focused: gamers in late-night sessions, athletes pushing their limits, and high-performance individuals who demand intensity. The brand personality is unapologetically loud, electric, and confident.

The visual style is a fusion of **High-Contrast / Bold** aesthetics and **Glassmorphism**. It utilizes a deep, tactical dark mode as the foundation, allowing vibrant neon "surges" of color to cut through the interface like electric currents. The aesthetic is "Premium-Aggressive"—it feels expensive but carries the raw energy of an urban lightning strike. Layouts should feel dynamic, using diagonal lines and metallic textures to imply motion even in static states.

## Colors
The palette is built on a "Current & Conduit" philosophy. The dark base represents the conduit—stable, deep, and premium—while the neons represent the raw current flowing through the system.

- **Base Layers:** Use `#0A0A0A` for global backgrounds. Use `#1A1A1A` and `#242424` for cards and containers to create subtle depth.
- **Electric Yellow (#F5FF00):** The primary action color. Use for high-priority CTAs and critical alerts. It represents the "peak" of energy.
- **Neon Green (#39FF14):** The secondary accent. Use for success states, performance metrics, and growth indicators.
- **Electric Blue (#00E5FF):** The tertiary accent. Use for technical info, cooling effects, and secondary interactive elements.
- **Overlays:** Use 20% opacity versions of the neons for glow effects and "charged" states behind components.

## Typography
The typography is designed to hit hard and be read fast. 

- **Headlines:** Use **Anybody** with ultra-heavy weights and tight tracking. It provides a variable, athletic feel that looks modern and customized. All major headlines must be uppercase to maintain a "shouted" brand voice.
- **Body:** **Montserrat** provides a geometric, urban balance that remains highly legible against dark backgrounds.
- **Technical Labels:** **Space Grotesk** is used for data points, ingredients, and specs to provide a futuristic, technical edge.
- **Styling:** Apply a subtle 5-degree italic slant to headlines in promotional contexts to imply speed and forward momentum.

## Layout & Spacing
This design system utilizes a **Fixed Grid** on desktop (12 columns, 1440px max-width) and a **Fluid Grid** on mobile (4 columns). 

- **The Diagonal Rule:** Layouts should break the horizontal plane. Use 6-degree angled section dividers and clipping masks to create "speed lines" across the screen.
- **Asymmetry:** High-energy sections should use intentional white space (or "dark space") to pull focus toward product imagery.
- **Spacing Rhythm:** Based on an 8px base unit. Gaps between related components should be tight (8px-16px) to feel dense and "packed," while section gaps should be expansive (120px+) to allow the brand energy to breathe.

## Elevation & Depth
Depth is created through light emission rather than physical shadow.

- **Glow Tiers:** Instead of traditional shadows, use "Neon Underglows." Active containers should emit a subtle outer glow (15-30px blur, 15% opacity) in the color of the current accent (Yellow, Green, or Blue).
- **Glassmorphism:** Use semi-transparent surfaces (`rgba(26, 26, 26, 0.7)`) with a high background blur (20px) for navigation bars and floating modals. This creates a high-tech "heads-up display" (HUD) effect.
- **Metallic Textures:** Use subtle linear gradients (45-degree angle) on buttons to simulate brushed aluminum or carbon fiber, enhancing the premium feel.

## Shapes
The shape language is sharp and aggressive. This design system uses **Sharp (0px)** corners for all primary containers, buttons, and input fields.

- **The Chamfer:** Where possible, use a "clipped corner" or chamfered edge rather than a curve. This mimics military hardware and high-end tech.
- **Diagonal Accents:** Elements like progress bars and decorative dividers should use a 15-degree shear or diagonal end-cap to reinforce the "Volt" lightning aesthetic.

## Components
- **Buttons:** Primary buttons are Solid Electric Yellow with Black text, sharp corners, and a 2px offset border in Yellow. On hover, the button should "pulse" with an outer glow.
- **Cards:** Graphite background (`#1A1A1A`) with a top-border accent in one of the neon colors. No border-radius.
- **Input Fields:** Ghost-style inputs with a bottom-only border (2px) in Charcoal. On focus, the border turns Electric Blue and glows slightly.
- **Chips/Badges:** Small, sharp-edged rectangles with a heavy uppercase label. Use Neon Green for "Performance" stats and Electric Blue for "Specs."
- **Progress Bars:** Segmented bars (like a battery indicator) rather than a solid line. Use the primary yellow for fill.
- **Special Element: "The Surge":** A background decorative element using a lightning bolt or diagonal speed line that tracks with the user's scroll.