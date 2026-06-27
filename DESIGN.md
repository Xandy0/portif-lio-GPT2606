---
name: Data Systems Professional
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
  on-surface-variant: '#bbc8d0'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#869399'
  outline-variant: '#3c494e'
  surface-tint: '#5ed4ff'
  primary: '#9de2ff'
  on-primary: '#003545'
  primary-container: '#00ccff'
  on-primary-container: '#005369'
  inverse-primary: '#006782'
  secondary: '#bcc7de'
  on-secondary: '#263143'
  secondary-container: '#3e495d'
  on-secondary-container: '#aeb9d0'
  tertiary: '#cad9f2'
  on-tertiary: '#233144'
  tertiary-container: '#afbdd6'
  on-tertiary-container: '#3e4c61'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bbe9ff'
  primary-fixed-dim: '#5ed4ff'
  on-primary-fixed: '#001f29'
  on-primary-fixed-variant: '#004d63'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
  surface-sidebar: '#2F3236'
  text-primary-light: '#F8FAFC'
  text-secondary-dark: '#94A3B8'
  highlight-cyan: '#00CCFF'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
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
    lineHeight: '1.5'
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
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
  container-max: 1200px
  sidebar-width: 280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for a personal brand that bridges the gap between high-level Data Science and robust Systems Analysis. It projects an image of precision, technical mastery, and modern efficiency. The target audience includes technical recruiters, engineering leads, and CTOs who value clarity and data-driven results.

The visual direction is **Corporate / Modern** with a **Developer Portfolio** edge. It utilizes a refined layout that mirrors the structure of an IDE or a technical whitepaper, emphasizing content hierarchy through clean lines and strategic whitespace. The style is professional and grounded, ensuring that the individual's expertise is the focal point while providing a "high-end" digital experience through subtle depth and purposeful color application.

## Colors

The palette is rooted in a deep, nocturnal spectrum to evoke a "terminal" or "IDE" environment suitable for a systems professional. The default mode is **dark**, using a deep navy (`#0F172A`) as the base canvas to reduce eye strain and increase the perceived value of the content.

The primary accent is a vibrant **Electric Cyan** (`#00CCFF`), derived from the source material. This color is used sparingly for interactive states, key data points, and navigation highlights. Secondary and tertiary slates provide the necessary layering for containers and borders, maintaining a monochromatic professional feel while allowing the cyan accent to provide clear visual cues for user action.

## Typography

This design system employs a tiered font strategy to signal technical authority. **Hanken Grotesk** is used for headlines; its sharp, contemporary geometry feels engineered and precise. For body content, **Inter** provides maximum readability and a neutral, professional tone. 

**JetBrains Mono** is introduced for labels, metadata, and "technical snippets." This monospaced font reinforces the developer persona, making data points such as dates, categories, or tech stacks feel like code-based objects. 

- Use **Display LG** for the primary name or hero statement.
- Use **Label MD/SM** for technical metadata, tags, and small captions.
- Ensure all body text maintains a line height of at least 1.5 for optimal legibility against dark backgrounds.

## Layout & Spacing

The layout uses a **Fluid Grid** model with a sidebar-main architecture, echoing the structure of documentation sites and technical dashboards. 

- **Desktop:** A fixed-width sidebar (280px) houses the primary navigation, while the main content area expands to a maximum of 1200px.
- **Table/Mobile:** The sidebar transitions to a hidden "drawer" or a top-bar navigation. Margins scale down from 48px on desktop to 16px on mobile to preserve screen real estate.
- **Rhythm:** An 8px base unit drives all spacing. Elements should be separated by increments of 8 (e.g., 16px for small groupings, 32px for section breaks).

The system prioritizes horizontal alignment to create a "scannable" experience, essential for reviewing technical credentials and project summaries.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** rather than heavy shadows. In the dark mode environment, surfaces closer to the user are rendered in lighter shades of slate, creating a stack of information.

- **Base Layer:** The deepest slate (`#0F172A`) for the background.
- **Surface Layer:** Secondary slate (`#1E293B`) for cards, sidebar, and containers.
- **Interaction Layer:** Subtle, low-opacity **Ambient Shadows** (0 4px 20px rgba(0,0,0,0.4)) are used on hover states to provide a tactile sense of lift.
- **Outlines:** Use 1px "ghost borders" in a low-contrast tertiary slate (`#334155`) to define sections without adding visual bulk. This keeps the interface feeling "thin" and high-tech.

## Shapes

The design system adopts a **Soft (0.25rem)** roundedness approach. This subtle rounding maintains a professional, serious architectural feel while avoiding the clinical harshness of sharp 90-degree corners. 

- **Standard Elements:** Inputs, buttons, and small cards use the base 0.25rem radius.
- **Large Containers:** Project cards or main document frames may use `rounded-lg` (0.5rem) to soften the overall layout.
- **Status Indicators:** Small dots or status pills should remain fully circular to contrast against the geometric grid.

## Components

### Buttons
Primary buttons are solid Electric Cyan with dark text. Secondary buttons utilize the "ghost" style—a 1px slate border with cyan text that fills on hover. All buttons use the `label-md` typeface for a technical, utility-first look.

### Cards
Cards are the primary container for portfolio items. They feature a 1px border (`#334155`) and a background slightly lighter than the base. On hover, the border transitions to Electric Cyan to signal interactivity.

### Chips / Tags
Used for tech stacks (e.g., "Python", "PyTorch"). These use the `label-sm` font in JetBrains Mono. They have a subtle background tint of the accent color at 10% opacity and a matching border.

### Input Fields
Inputs are dark-themed with a subtle bottom border or full outline. The focus state must be a crisp Electric Cyan ring (2px) to ensure accessibility and visual feedback.

### Lists & Timelines
Experience entries should follow a vertical timeline format, using the Electric Cyan as a "node" color. Line-work should be kept thin (1px) and in the tertiary slate color.