# K. Prajesh Kumar — Developer Portfolio

A performance-optimized, accessible, developer portfolio built with semantic HTML5, Vanilla JavaScript, and Tailwind CSS. Enhanced with custom canvas physics, command palette (⌘K), dynamic category filtering, interactive cards, and light/dark theme support.

---

## 🚀 Architecture & Tech Stack

* **Core Structure**: Semantic HTML5 with accessible landmarking (`<header>`, `<main id="main-content">`, `<section>`, `<nav>`, `<footer>`).
* **Styling & Design System**: Tailwind CSS v3 with custom design tokens, compiled at build-time with PostCSS and Autoprefixer minification.
* **Typography & Icons**: Geist Sans, JetBrains Mono, and Google Material Symbols Outlined (served via optimized, preconnected Google Fonts requests).
* **Interactive Visual Effects & Utilities**:
  * **`<DotField />`**: Interactive Canvas dot grid background with cursor bulge physics, wave displacement, reduced-motion bypass, and idle battery-saving loop throttling.
  * **`<SpotlightCard />`**: Hardware-accelerated radial spotlight effect with light/dark theme tracking.
  * **`<GlareHover />`**: Angled glare sweep reflection with `requestAnimationFrame` pointer tracking across all project cards.
  * **`<PillNav />`**: Floating glassmorphic header with animated sliding indicator.
  * **`⌘K` / `Ctrl+K` Command Palette**: Fast keyboard-navigable modal for quick section jumps, clipboard copy actions, and theme toggle.
  * **Interactive Project Category Filtering**: Smooth client-side filtering between AI/RAG systems and Full-Stack applications.

---

## ♿ Accessibility (a11y) & WCAG Compliance

1. **Skip-to-Content Link**:
   * Positioned as the first interactive element in `<body>` (`.skip-link`).
   * Appears on `:focus` to allow keyboard users to jump directly to `<main id="main-content">`.

2. **Logical Heading Hierarchy**:
   * Top-level hero heading: `<h1>`.
   * Main section labels (About, Work Experience, Skills, Education & Leadership, Projects, Contact): semantic `<h2>` elements styled with pill capsules.
   * Project titles and roles: `<h3>` and `<h4>` subheadings.

3. **Screen Reader Optimization**:
   * All decorative Material Symbols icons have `aria-hidden="true"`.
   * Action buttons and navigation links have descriptive `aria-label` attributes (`Home`, `About`, `Work Experience`, `Projects`, `Skills`, `Education`, `GitHub`, `LinkedIn`, `Contact`, `Toggle theme`).
   * Structural navigation landmarks labeled via `aria-label="Main Navigation"`.

4. **Keyboard Navigation & Visible Focus**:
   * Clear focus rings (`focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-sky-500`) on all interactive controls.
   * Universal `⌘K` / `Ctrl+K` command menu accessible from any viewport.

5. **Motion Preferences**:
   * Respects `prefers-reduced-motion: reduce` in both CSS and JavaScript. Continuous animation loops are suspended when reduced motion is requested.

---

## ⚡ Performance Optimizations

1. **Build-Time Tailwind Compilation**:
   * Precompiled production CSS (`dist/output.css`) with PostCSS & Autoprefixer, eliminating runtime parsing overhead and layout shift.

2. **Resource Preconnection & Font Merging**:
   * `<link rel="preconnect">` for `fonts.googleapis.com` and `fonts.gstatic.com`.
   * Merged font requests for Geist, JetBrains Mono, and Material Symbols into optimized stylesheet calls.

3. **Background & Idle Throttling**:
   * Canvas animations automatically sleep via idle timeouts when the cursor is still and pause via the Page Visibility API (`visibilitychange` / `document.hidden`) when tabs are backgrounded.
   * Touch-primary devices bypass desktop mouse-tracking physics.

---

## 🛠️ Getting Started & Build Commands

### Prerequisites
* Node.js (v18+) and npm

### Installation
```bash
npm install
```

### Build Production CSS
```bash
npm run build:css
# or
npm run build
```

### Watch Mode (Development)
```bash
npm run watch:css
```

### Run Local Development Server
```bash
# Using Python:
python3 -m http.server 3000

# Using Node (e.g. npx serve):
npx serve .
```
Access the application at `http://localhost:3000/`.

---

## 📁 Directory Structure

```
portfolio/
├── .vscode/
│   └── settings.json          # IDE lint configurations for Tailwind CSS
├── dist/
│   └── output.css             # Compiled, minified production CSS bundle
├── src/
│   └── input.css              # Source Tailwind & design system styles
├── index.html                 # Main portfolio entry HTML file
├── code.html                  # Legacy entry redirect to index.html
├── package.json               # Project manifest & build scripts
├── postcss.config.js          # PostCSS configuration
├── tailwind.config.js         # Tailwind configuration & custom design tokens
├── DESIGN.md                  # Design system specification
└── README.md                  # Project documentation
```
