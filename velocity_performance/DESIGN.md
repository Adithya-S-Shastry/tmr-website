---
name: Velocity Performance
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#383939'
  surface-container-lowest: '#0d0e0f'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#292a2a'
  surface-container-highest: '#343535'
  on-surface: '#e3e2e2'
  on-surface-variant: '#c4c7c8'
  inverse-surface: '#e3e2e2'
  inverse-on-surface: '#303031'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c6c6c7'
  primary: '#ffffff'
  on-primary: '#2f3131'
  primary-container: '#e2e2e2'
  on-primary-container: '#636565'
  inverse-primary: '#5d5f5f'
  secondary: '#a3cddb'
  on-secondary: '#023641'
  secondary-container: '#244f5a'
  on-secondary-container: '#95bfcd'
  tertiary: '#ffffff'
  on-tertiary: '#313030'
  tertiary-container: '#e5e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#beeaf8'
  secondary-fixed-dim: '#a3cddb'
  on-secondary-fixed: '#001f27'
  on-secondary-fixed-variant: '#214c58'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e3e2e2'
  surface-variant: '#343535'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
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
    lineHeight: '1.6'
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
  stats-display:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1'
    letterSpacing: -0.03em
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
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 80px
---

## Brand & Style

The brand personality of the design system is engineered, precise, and high-velocity. It is tailored for an audience of engineering recruiters, sponsors, and automotive enthusiasts who value technical excellence and raw performance. The UI evokes the feeling of a premium racing telemetry dashboard—functional, focused, and sophisticated.

The design style is **High-Performance Minimalism**. It utilizes a "Dark Mode" default to emulate cockpit environments, focusing on high-contrast legibility and a sleek, mechanical aesthetic. Visual noise is eliminated to let the engineering achievements and photography take center stage.

## Colors

The palette for this design system is rooted in a "void" aesthetic. The primary background is a true #000000 to provide infinite depth, allowing the vehicle's form to emerge from the shadows. 

- **Primary White (#FFFFFF):** Used for all high-priority content, headlines, and essential reading to ensure maximum contrast.
- **Accent Light Blue (#ADD8E6):** Inspired by cold steel and precision lighting, this color is reserved for highlights, interactive states, and technical data points.
- **Surface Neutrals:** A series of deep greys are used sparingly for structural elements like borders and container backgrounds to differentiate layers without breaking the monochromatic flow.

## Typography

This design system employs a dual-typeface strategy to balance technical grit with readability. 

**Space Grotesk** is used for headlines and data labels. Its geometric, slightly quirky terminals give it a futuristic, scientific feel that aligns with automotive engineering. 

**Inter** is the workhorse for body copy, providing exceptional clarity at all sizes. Its neutral tone ensures that long-form content about technical specifications remains professional and easy to digest. Large numerical data points (telemetry, lap times) should use the `stats-display` style to mimic digital instrument clusters.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model within a centered container. A 12-column system provides the structure necessary for complex technical layouts. 

The spacing rhythm is strictly based on an 8px modular scale. Generous vertical "Stack" spacing (80px+) is encouraged between major sections to create a sense of premium editorial design. Content should be grouped in logical blocks that span 4, 6, or 8 columns to maintain a balanced, asymmetric look reminiscent of automotive blueprints.

## Elevation & Depth

In a pure black environment, traditional shadows are ineffective. Instead, this design system uses **Tonal Layers and Ghost Borders** to communicate depth.

- **Surface Levels:** Primary background is #000000. Secondary containers (cards/sections) use a very subtle #0A0A0A or #111111 fill.
- **Outlines:** Depth is primarily defined by 1px solid strokes. Interactive elements use a #FFFFFF opacity (10-20%) stroke, while active or highlighted elements use the accent Light Blue.
- **Backdrop Blurs:** When overlays or navigation menus appear, a high-density Gaussian blur (20px+) is applied to the background to maintain a "cockpit" feel without losing the sense of space.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding of corners bridges the gap between the aggressive, sharp angles of a roll cage and the aerodynamic curves of vehicle bodywork. 

It provides a modern, "machined" look—as if the UI components were CNC-milled from a solid block of material. Large images and hero sections may remain completely sharp (0px) to emphasize the raw, unrefined nature of Baja racing, while interactive components like buttons use the 0.25rem standard.

## Components

### Buttons
Primary buttons are styled as "Ghost" buttons: transparent backgrounds with a 1px Light Blue stroke and White text. On hover, the background fills with a 10% Light Blue tint. The "Action" button should feel like a precision instrument.

### Chips & Tags
Used for technical specs (e.g., "4WD", "VTwin"). These are small, uppercase labels with a #1A1A1A background and Light Blue text, reinforcing the data-heavy nature of the site.

### Cards
Cards do not use shadows. They are defined by a #111111 background and a subtle top-border highlight in Light Blue (2px height) to indicate focus or importance.

### Inputs
Text fields are bottom-border only, using the "Label-Caps" typography style for placeholders. This mimics technical forms found in engineering documentation.

### Telemetry Displays
A custom component for the design system: Large numerical stats paired with a small progress bar or sparkline in Light Blue to visualize performance metrics like weight, horsepower, and torque.