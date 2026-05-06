---
name: The Digital Estate
colors:
  surface: '#fdf9ed'
  surface-dim: '#dedace'
  surface-bright: '#fdf9ed'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3e7'
  surface-container: '#f2eee2'
  surface-container-high: '#ece8dc'
  surface-container-highest: '#e6e2d6'
  on-surface: '#1d1c15'
  on-surface-variant: '#434843'
  inverse-surface: '#323129'
  inverse-on-surface: '#f5f1e4'
  outline: '#737973'
  outline-variant: '#c3c8c1'
  surface-tint: '#4d6453'
  primary: '#061b0e'
  on-primary: '#ffffff'
  primary-container: '#1b3022'
  on-primary-container: '#819986'
  inverse-primary: '#b4cdb8'
  secondary: '#526600'
  on-secondary: '#ffffff'
  secondary-container: '#c8f323'
  on-secondary-container: '#576c00'
  tertiary: '#271013'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f2427'
  on-tertiary-container: '#b0898c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d4'
  primary-fixed-dim: '#b4cdb8'
  on-primary-fixed: '#0b2013'
  on-primary-fixed-variant: '#364c3c'
  secondary-fixed: '#c8f323'
  secondary-fixed-dim: '#aed500'
  on-secondary-fixed: '#171e00'
  on-secondary-fixed-variant: '#3d4d00'
  tertiary-fixed: '#ffd9dc'
  tertiary-fixed-dim: '#e7bcbf'
  on-tertiary-fixed: '#2d1417'
  on-tertiary-fixed-variant: '#5d3f42'
  background: '#fdf9ed'
  on-background: '#1d1c15'
  surface-variant: '#e6e2d6'
typography:
  h1:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h2:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h3:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  data-mono:
    fontFamily: Manrope
    fontSize: 14px
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-page: 64px
  section-gap: 120px
---

## Brand & Style
This design system establishes an "Institutional but Fresh" aesthetic, bridging the gap between traditional prestige and future-facing technology. It is designed for strategic consultants who balance legacy wisdom with high-tech execution. The brand personality is authoritative, composed, and visionary.

The visual style utilizes **Minimalism** with a **Tactile** edge. It mimics the physical quality of high-end stationery—the "Digital Estate"—while incorporating hyper-modern accents that signify AI and automation. The interface should feel like an expensive physical dossier that has been flawlessly digitized.

## Colors
The palette is rooted in a warm, off-white parchment base (#FCF9F2) to reduce eye strain and evoke a sense of heritage. 

- **Deep Forest Green (#1B3022):** Used for primary typography, borders, and structural elements. It provides the "institutional" anchor, replacing standard blacks or greys with a richer, more organic tone.
- **Vibrant Lime Green (#D4FF33):** Reserved exclusively for high-tech touchpoints, progress indicators, and primary Call-to-Actions. It acts as a digital "highlighter," signaling speed, automation, and innovation.
- **Neutral Parchment Tier:** Subsurface layers use a slightly darker tint of the background (#E8E4D8) to create structural hierarchy without relying on heavy shadows.

## Typography
The typography system relies on a high-contrast pairing of a literary serif and a technical sans-serif.

- **Newsreader:** Used for all storytelling components—headlines, pull quotes, and section titles. The medium weights should be favored to maintain a "printed" feel.
- **Manrope:** Used for body copy, data visualizations, and interface labels. Its geometric precision balances the organic nature of the serif. Use tabular-nums for all technical data to ensure vertical alignment in reports and tables.

## Layout & Spacing
This design system employs a **Fixed Grid** philosophy with generous whitespace to denote luxury and clarity. 

Layouts are built on a 12-column grid. Information density is kept low; key insights are given significant vertical breathing room (Section Gaps) to allow for executive processing. Use asymmetrical layouts (e.g., spanning 8 columns for content and leaving 4 columns empty or for secondary annotations) to mimic the margins of a strategic briefing document.

## Elevation & Depth
Depth is achieved through **Low-Contrast Outlines** and **Tonal Layering** rather than aggressive shadows. 

1. **Surface Tiers:** Use subtle shifts in background color (Parchment to Neutral) to define content containers.
2. **Hairline Borders:** Use 1px Deep Forest Green borders at 15-20% opacity to define structural divisions.
3. **Intentional Shadows:** When elevation is required (e.g., for modals), use a very large, soft blur with a slight Forest Green tint (e.g., 20% opacity) to avoid the "grey" look of standard web interfaces.

## Shapes
The shape language is **Soft (Level 1)**. Elements utilize a subtle 0.25rem (4px) radius. This provides just enough softness to feel modern and accessible while maintaining the "precise" and "sharp" character expected from an institutional firm. Larger containers like cards may use a slightly increased radius (8px), but never approach pill-shapes for structural elements.

## Components
- **Buttons:** Primary buttons are Solid Vibrant Lime Green with Deep Forest Green text. Secondary buttons use a Deep Forest Green ghost style with a 1px border.
- **Input Fields:** Use a "Minimal Ledger" style—bottom border only, or a very light 4-sided stroke with an off-white fill. Focus states use a 1px solid Deep Forest Green stroke with a Lime Green accent glow.
- **Cards:** Cards should have no background (transparent) and be defined by a thin 1px border, or use a subtle #E8E4D8 fill with no border.
- **Data Visualizations:** All charts must use Deep Forest Green as the baseline, with Vibrant Lime Green used exclusively to highlight the "Target," "Insight," or "Trend."
- **Progress Indicators:** Use the Vibrant Lime Green to represent AI processing or automation status, creating a high-contrast visual "ping" against the muted background.