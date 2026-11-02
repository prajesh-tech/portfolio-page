---
name: Developer Minimalist
colors:
  surface: '#f9f9fa'
  surface-dim: '#dadadb'
  surface-bright: '#f9f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeef'
  surface-container-high: '#e8e8e9'
  surface-container-highest: '#e2e2e3'
  on-surface: '#1a1c1d'
  on-surface-variant: '#47464a'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#78767b'
  outline-variant: '#c8c5ca'
  surface-tint: '#5f5e60'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1d'
  on-primary-container: '#858386'
  inverse-primary: '#c8c6c8'
  secondary: '#5d5e66'
  on-secondary: '#ffffff'
  secondary-container: '#e3e1ec'
  on-secondary-container: '#63646c'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1f1a1a'
  on-tertiary-container: '#8a8282'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e1e4'
  primary-fixed-dim: '#c8c6c8'
  on-primary-fixed: '#1c1b1d'
  on-primary-fixed-variant: '#474649'
  secondary-fixed: '#e3e1ec'
  secondary-fixed-dim: '#c6c5cf'
  on-secondary-fixed: '#1a1b22'
  on-secondary-fixed-variant: '#46464e'
  tertiary-fixed: '#ebe0df'
  tertiary-fixed-dim: '#cec4c4'
  on-tertiary-fixed: '#1f1a1a'
  on-tertiary-fixed-variant: '#4c4545'
  background: '#f9f9fa'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e3'
  background-light: '#ffffff'
  background-dark: '#09090b'
  surface-card-light: '#ffffff'
  surface-card-dark: '#121215'
  border-subtle-light: '#e4e4e7'
  border-subtle-dark: '#27272a'
  text-primary-light: '#09090b'
  text-primary-dark: '#fafafa'
  text-muted-light: '#71717a'
  text-muted-dark: '#a1a1aa'
  dock-bg-light: rgba(255, 255, 255, 0.8)
  dock-bg-dark: rgba(18, 18, 21, 0.8)
typography:
  headline-hero:
    fontFamily: geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.04em
  headline-hero-mobile:
    fontFamily: geist
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.03em
  headline-section:
    fontFamily: geist
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.03em
  headline-section-mobile:
    fontFamily: geist
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: -0.025em
  headline-item:
    fontFamily: geist
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-sm:
    fontFamily: geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-badge:
    fontFamily: geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  label-pill-dark:
    fontFamily: geist
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.02em
  label-code:
    fontFamily: jetbrainsMono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 42rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  grid-gutter: 1rem
  dock-offset-bottom: 1.5rem
---

## Brand & Style

This design system embodies the high-craft, monochromatic aesthetic popularized by elite developer portfolios and modern engineering platforms. The visual tone is technical, disciplined, understated, and exceptionally readable. It prioritizes clarity of engineering accomplishments, code craft, and product shipping over decorative excess.

The design movement combines **Minimalism** with subtle **Neo-Brutalist micro-borders** and a touch of **Glassmorphism** for floating interactive utilities. 

Key attributes:
- **Monochromatic Purity:** High-contrast neutral hierarchy (stark blacks, zinc grays, clean whites) without distracting chromatic noise. Color is reserved exclusively for recognizable tech brand icons and external project badges.
- **Micro-Precision Borders:** Crisp 1px structural outlines (`zinc-200` in light, `zinc-800` in dark) that clearly delineate content zones, tags, and cards without visual heaviness.
- **Engineered Restraint:** Ample negative space, disciplined vertical cadence, and compact typography that mimics technical documentation and IDE interfaces.
- **Floating Utility:** Grounded by an omnipresent, floating dock bar at the bottom viewport edge, providing persistent navigation and tactile social links.

## Colors

The color palette is strictly monochromatic and grounded in the neutral zinc spectrum. The system supports full high-fidelity parity between light and dark modes.

- **Primary (`#09090b`):** The definitive foreground color in light mode (used for high-emphasis headlines, active pills, and solid action buttons). In dark mode, this flips to high-brightness pure whites and off-whites (`#fafafa`).
- **Secondary (`#71717a`):** A neutral zinc mid-tone applied to metadata, dates, secondary body copy, descriptions, and passive icon strokes.
- **Neutral (`#f4f4f5`):** Soft surface backgrounds for tag badges, secondary action pills, hover layers, and code-block backgrounds.
- **Borders & Dividers:** Built using `border-subtle-light` (`#e4e4e7`) and `border-subtle-dark` (`#27272a`). These micro-borders create clear content separation without introducing visual noise.
- **Accent Philosophy:** Chromatic color is never applied to layout framing or typography. Brand colors only appear naturally within embedded SVG technology logos (e.g., Python yellow/blue, React cyan, Next.js monochrome) and external media icons.

## Typography

The type system relies on **Geist**—a geometric, human-refined grotesque typeface engineered specifically for high readability in technical interfaces, with **JetBrains Mono** reserved for code fragments and repository stats.

Hierarchy Guidelines:
- **Tight Tracking:** Headlines employ negative letter spacing (`-0.03em` to `-0.04em`) to establish a modern, commanding presence.
- **Section Badges:** Section headings are systematically pre-faced by pill badges set in small caps or compact weights (`label-pill-dark`) centered above the title.
- **Body Rhythm:** Body copy maintains relaxed line heights (1.5x–1.6x) for reading comfort across project descriptions, while lists and timeline entries use compact line heights to preserve visual cohesion.
- **Dates & Subtitles:** Secondary timeline dates and locations are formatted in `body-sm` with a lighter gray tint (`#71717a`) to avoid competing with organizational titles.

## Layout & Spacing

The layout is built around a disciplined, centered single-column narrative container with an intentionally narrow maximum width of **42rem (672px)**. This constrained reading measure delivers an editorial, resume-grade experience optimized for scanning.

Grid & Layout Architecture:
- **Single-Column Focus:** Main narrative elements (hero introduction, about statement, work experience timeline, and education list) live inside the central 42rem container with `mx-auto` and horizontal padding of `1.25rem` on mobile and `2rem` on desktop.
- **Project Grid:** The "Projects" showcase breaks out into an intentional 2-column balanced grid (`grid-cols-1 sm:grid-cols-2`) with `1rem` gutters within the container boundary.
- **Vertical Rhythm:** Major thematic blocks (About, Experience, Education, Projects, Hackathons, Contact) are separated by rhythmic vertical gaps of `space-2xl` (48px) to `space-3xl` (72px).
- **Floating Dock Clearance:** The page content provides persistent bottom padding of at least `6rem` (96px) to guarantee that the fixed bottom dock bar never occludes text or active links.

## Elevation & Depth

This design system eschews heavy drop shadows in favor of **tactile planar surfaces and micro-borders**:

- **Card Surfaces:** Cards sit on the page with a subtle border (`1px solid var(--border-subtle)`). Shadows are either omitted or restricted to a barely visible ambient blur (`0 1px 2px 0 rgba(0, 0, 0, 0.05)`).
- **Hover Transitions:** On hover, project cards subtly lift via a micro-transition (`transform: translateY(-2px)`) accompanied by a soft border brightening (`zinc-300` in light mode, `zinc-700` in dark mode).
- **Floating Navigation Dock:** The persistent bottom dock uses an elevated glassmorphism model:
  - Background: `rgba(255, 255, 255, 0.75)` in light mode, `rgba(18, 18, 21, 0.8)` in dark mode.
  - Backdrop Filter: `blur(12px) saturate(180%)`.
  - Border: `1px solid rgba(0, 0, 0, 0.08)` / `1px solid rgba(255, 255, 255, 0.1)`.
  - Elevation Shadow: `0 10px 25px -5px rgba(0, 0, 0, 0.08), 0 8px 10px -6px rgba(0, 0, 0, 0.05)`.
- **Modals & Tooltips:** Floating popovers use crisp solid surface backgrounds with `box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1)` framed by micro-borders.

## Shapes

The design system employs a dual shape language: structured rounded rectangles for containers and pure capsules (pills) for interactive and informational tags.

- **Project & Section Cards:** `rounded-xl` (0.75rem / 12px) to `rounded-2xl` (1rem / 16px). This rounds the outer perimeter while keeping code tags and preview media neatly framed.
- **Badges, Action Buttons & Tech Pills:** Fully rounded pills (`rounded-full` / 9999px). All technology chips, link pills ("Website", "Source"), category labels ("My Projects", "Hackathons"), and avatar frames use full curvature.
- **Dock Container & Icons:** The dock shell is `rounded-full` (capsule). Internal dock icons are contained inside `rounded-full` tap targets (36px × 36px) that provide a smooth, circular highlight on hover.
- **Avatar:** Circle container (`rounded-full`) with a subtle 1px border ring.

## Components

### Section Pill Badges
- Used to label major sections (e.g., "My Projects", "Hackathons", "Contact").
- Rendered as an inline-block capsule: `px-3 py-1 text-xs font-semibold rounded-full`.
- Default: solid black background (`#09090b`) with crisp white text (`#ffffff`) in light mode; reverses in dark mode.

### Project Cards
- Enclosed containers with `border border-zinc-200 dark:border-zinc-800 rounded-xl overflow-hidden bg-white dark:bg-zinc-900/50`.
- Includes a 16:9 media slot at the top (video or screenshot) followed by a padded content stack:
  - Title row with date/period right-aligned.
  - Brief description in `body-sm` (`text-zinc-600 dark:text-zinc-400`).
  - Technology stack row with compact pill badges (`bg-zinc-100 dark:bg-zinc-800 text-[10px] font-medium px-2 py-0.5 rounded-md`).
  - Action link row containing micro-pill buttons ("Website", "Source") paired with micro-icons (Globe, GitHub).

### Timeline & Experience Items
- Clean tabular rows featuring:
  - Circular company/institution avatar (`size-10 rounded-full border border-zinc-200 dark:border-zinc-800`).
  - Organization title and role headline in semibold text.
  - Right-aligned monospaced or muted date range.
  - Expandable nested description for achievements or technologies used.

### Floating Dock Navigation
- Persistent dock fixed at `bottom-6 left-1/2 -translate-x-1/2 z-50`.
- Constructed with a blurred capsule container (`backdrop-blur-md border rounded-full px-3 py-2 flex items-center gap-1 shadow-lg`).
- Contains icon-only triggers (Home, Notebook, GitHub, LinkedIn, X, Theme Toggle) with subtle hover scale and tooltip display.
- Vertical divider line (`w-[1px] h-4 bg-zinc-200 dark:bg-zinc-800 mx-1`) separating internal navigation from external links and mode toggles.

### Tech Stack Chips
- Compact, clickable or static pills with `border border-zinc-200 dark:border-zinc-800 rounded-full px-3 py-1 flex items-center gap-1.5`.
- Incorporates official SVG tech logos at `size-3.5` alongside the tech name in `label-badge`.

### Buttons & Link Pills
- **Primary:** Capsule pill with solid dark fill (`bg-zinc-900 text-white dark:bg-zinc-50 dark:text-zinc-900 hover:opacity-90 px-3 py-1 text-xs font-medium`).
- **Ghost/Outline:** Capsule pill with `border border-zinc-200 dark:border-zinc-800 hover:bg-zinc-100 dark:hover:bg-zinc-800 text-xs px-2.5 py-1`.