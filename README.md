<div align="center">

# ⚡ Tachyons 5

**Functional CSS for humans. Zero build. Pure CSS. Just works.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CSS Size](https://img.shields.io/badge/size-240kb-green)](https://github.com/gobijan/tachyons5)
[![Gzipped](https://img.shields.io/badge/gzipped-~29kb-brightgreen)](https://github.com/gobijan/tachyons5)
[![CSS Variables](https://img.shields.io/badge/CSS_Variables-✓-purple)](https://github.com/gobijan/tachyons5)
[![No Build Step](https://img.shields.io/badge/build_step-none-orange)](https://github.com/gobijan/tachyons5)

</div>

---

## 🚀 Quick Start

**CDN (Recommended)**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/gobijan/tachyons5@main/tachyons5.css">
```

**Download**
```bash
curl -O https://raw.githubusercontent.com/gobijan/tachyons5/main/tachyons5.css
```

**Then just use it:**
```html
    <div class="
        p4 bg-slate-gray-3 white br3 box-shadow-border-3 box-shadow-7 f-body flex
        items-center justify-center glow o9 active-dim
      ">
        <h1 class="f3 f4-l">@gobijan</h1>
    </div>
```

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎨 **CSS Variables** | Full theming support with custom properties |
| 🌓 **Dark Mode** | Automatic + manual light/dark theme switching |
| 📦 **Zero Build** | No npm, no webpack, no PostCSS — just drop it in |
| 📱 **Responsive** | Mobile-first with media queries AND container queries |
| 🔲 **CSS Grid** | Native grid support with `cols-*` and `g*` gap utilities |
| 🌐 **Logical Properties** | RTL-ready with `start`/`end` instead of `left`/`right` |
| 📦 **Container Queries** | Modern component-based responsive design |
| 🎛️ **Form Components** | Themed inputs, checkboxes, radios, and switches |
| 🪟 **Dialog & Dropdown** | Native `<dialog>` and Popover API components |
| ♿ **Accessibility** | Focus rings, reduced motion, selection colors |
| ⚡ **~1900+ Utilities** | Spacing, typography, colors, flexbox, grid & more |
| 🪶 **~29kb gzipped** | Lightweight and fast |
| 🔧 **Maintained** | Actively maintained and updated |

---

## 📖 Usage Examples

**Responsive Card**
```html
    <article class="mw5 w-100 center bg-white br3 p3 p4-m mb3 ba b--light f-body">
        <div class="tc">
            <img src="https://placehold.co/400x400/000000/FFF" class="br11 h4 w4 dib ba b--light p2" alt="avatar">

            <h1 class="f5 mbe2">Jane Doe</h1>

            <h2 class="f3 fw4 gray mbs0">Developer</h2>
        </div>
    </article>
```

**CSS Grid Layout**
```html
<div class="grid cols-1 cols-2-m cols-4-l g3">
  <div class="p3">Item 1</div>
  <div class="p3">Item 2</div>
  <div class="p3">Item 3</div>
  <div class="p3">Item 4</div>
</div>
```

**Container Query Responsive**
```html
<div class="container-inline">
  <div class="cols-1 cols-2-s cols-4-m">
    <!-- Responds to container size, not viewport! -->
  </div>
</div>
```

**Button Styles**
```html
<button class="f3 fw5 link dim br3 pb3 pi2 mbe2 dib white bg-blue-5 bn pointer f-body">
    Click Me
</button>
```

---

## 🎯 Class Reference (Cheat Sheet)

### Spacing (Logical Properties)
| Class | Property | Description |
|-------|----------|-------------|
| `p0` - `p9` | padding | all sides |
| `m0` - `m9` | margin | all sides |
| `pis0` - `pis9` | padding-inline-start | start edge (left in LTR) |
| `pie0` - `pie9` | padding-inline-end | end edge (right in LTR) |
| `pbs0` - `pbs9` | padding-block-start | top |
| `pbe0` - `pbe9` | padding-block-end | bottom |
| `pi0` - `pi9` | padding-inline | left & right |
| `pb0` - `pb9` | padding-block | top & bottom |
| `mis0` - `mis9` | margin-inline-start | start edge |
| `mie0` - `mie9` | margin-inline-end | end edge |
| `mbs0` - `mbs9` | margin-block-start | top |
| `mbe0` - `mbe9` | margin-block-end | bottom |
| `mi0` - `mi9` | margin-inline | left & right |
| `mb0` - `mb9` | margin-block | top & bottom |
| `g0` - `g7` | gap | grid/flex gap |

### Typography
| Class | Description |
|-------|-------------|
| `f1` - `f7` | Font sizes (3rem → 0.75rem) |
| `fw1` - `fw9` | Font weights |
| `ts`, `tc`, `te`, `tj` | Text align (start, center, end, justify) |
| `ttc`, `ttu`, `ttl` | Text transform |
| `lh-solid`, `lh-title`, `lh-copy` | Line heights |

### Colors
| Class | Example |
|-------|---------|
| `blue`, `red`, `green`, `yellow`... | Text colors |
| `bg-blue`, `bg-red`, `bg-green`... | Background colors |
| `b--blue`, `b--red`... | Border colors |

### Semantic Theme Colors
| Class | Description |
|-------|-------------|
| `brand`, `bg-brand`, `b--brand` | Primary brand color |
| `text`, `muted` | Text colors (primary, secondary) |
| `surface-0` - `surface-3` | Surface/background layers |
| `error`, `success`, `notice` | Semantic status colors |
| `hover-*`, `focus-*` | Interactive state variants |

### Positioning (Logical Properties)
| Class | Property |
|-------|----------|
| `start-0`, `start-1`, `start-2` | inset-inline-start |
| `end-0`, `end-1`, `end-2` | inset-inline-end |
| `block-start-0`, `block-start-1` | inset-block-start (top) |
| `block-end-0`, `block-end-1` | inset-block-end (bottom) |

### Borders (Logical Properties)
| Class | Property |
|-------|----------|
| `bis` | border-inline-start |
| `bie` | border-inline-end |
| `bbs` | border-block-start |
| `bbe` | border-block-end |

### Float (Logical Properties)
| Class | Property |
|-------|----------|
| `fis` | float: inline-start |
| `fie` | float: inline-end |
| `fn` | float: none |

### Flexbox & Grid
| Class | Property |
|-------|----------|
| `flex`, `inline-flex` | display: flex |
| `grid`, `inline-grid` | display: grid |
| `cols-1` - `cols-16`, `cols-24` | grid-template-columns |
| `flex-row`, `flex-column` | flex-direction |
| `justify-center`, `justify-between`... | justify-content |
| `items-center`, `items-start`... | align-items |

### Shadows (OpenProps-inspired)
| Class | Description |
|-------|-------------|
| `shadow-1` | Subtle shadow for tight UI elements |
| `shadow-2` | Light shadow for cards |
| `shadow-3` | Medium shadow for dropdowns/popovers |
| `shadow-4` | Heavy shadow for modals/dialogs |
| `inner-shadow-1` - `inner-shadow-4` | Inset shadows with highlight |

### Dropdown Menu Component

A dropdown menu component using the Popover API with CSS anchor positioning and smooth animations.

```html
<div class="dib">
    <button popovertarget="dropdown-1" 
            style="anchor-name: --anchor-1;" 
            aria-haspopup="menu">
        Actions ▾
    </button>
    <div id="dropdown-1" 
         popover 
         class="dropdown-menu p3 bg-white shadow-3 br4" 
         style="--anchor: --anchor-1;" 
         role="menu">
        <a href="#" class="db p3 hover-bg-gray-10 br3">Edit</a>
        <a href="#" class="db p3 hover-bg-gray-10 br3">Delete</a>
    </div>
</div>
```

| Class | Description |
|-------|-------------|
| `dropdown-menu` | Base dropdown with anchor positioning and animations |
| `dropdown-menu--end` | Right-align dropdown to anchor |
| `dropdown-menu--top` | Position dropdown above anchor |

### Dialog / Modal Component

A dialog component using the native `<dialog>` element with smooth animations.

```html
<dialog class="dialog">
    <h2>Modal Title</h2>
    <p>Modal content goes here.</p>
    <button onclick="this.closest('dialog').close()">Close</button>
</dialog>

<button onclick="document.querySelector('.dialog').showModal()">
    Open Modal
</button>
```

| Class | Description |
|-------|-------------|
| `dialog` | Base dialog with backdrop and animations |
| `dialog--sm` | Small dialog (max-width: 20rem) |
| `dialog--lg` | Large dialog (max-width: 48rem) |
| `dialog--full` | Full-screen dialog |

### Form Components

Themed form elements that respect light/dark mode.

```html
<input type="text" class="input" placeholder="Text input">
<input type="text" class="input input--error" placeholder="Error state">

<input type="checkbox" class="checkbox">
<input type="radio" class="radio" name="group">
<input type="checkbox" class="switch">
```

| Class | Description |
|-------|-------------|
| `input` | Styled text input |
| `input--error` | Error state for inputs |
| `input--success` | Success state for inputs |
| `checkbox` | Styled checkbox |
| `radio` | Styled radio button |
| `switch` | Toggle switch |

### Focus Ring Utilities

Accessible focus styles using `:focus-visible`.

| Class | Description |
|-------|-------------|
| `focus-ring` | Brand color focus ring with offset |
| `focus-ring-inset` | Inset focus ring |
| `focus-ring-error` | Error color focus ring |
| `focus-ring-success` | Success color focus ring |

### Scroll Utilities

| Class | Description |
|-------|-------------|
| `scroll-smooth` | Smooth scroll behavior |
| `scroll-snap-x` | Horizontal scroll snap (mandatory) |
| `scroll-snap-y` | Vertical scroll snap (mandatory) |
| `snap-start`, `snap-center`, `snap-end` | Snap alignment |
| `scroll-p1` - `scroll-p5` | Scroll padding |
| `scrollbar-hidden` | Hide scrollbar |
| `scrollbar-thin` | Thin scrollbar |

### Accent Color

For native form elements (checkboxes, radios, range, progress).

| Class | Description |
|-------|-------------|
| `accent-brand` | Brand accent color |
| `accent-error` | Error accent color |
| `accent-success` | Success accent color |
| `accent-notice` | Notice accent color |

### Skeleton / Loading States

```html
<div class="skeleton skeleton-avatar"></div>
<div class="skeleton-shimmer skeleton-text"></div>
```

| Class | Description |
|-------|-------------|
| `skeleton` | Pulsing skeleton animation |
| `skeleton-shimmer` | Shimmer effect skeleton |
| `skeleton-text` | Text line placeholder |
| `skeleton-avatar` | Avatar placeholder (3rem circle) |
| `skeleton-button` | Button placeholder |
| `skeleton-circle` | Circular skeleton |

### Text Wrap Utilities

| Class | Description |
|-------|-------------|
| `text-balance` | Balance text across lines |
| `text-pretty` | Prevent orphans/widows |
| `text-nowrap` | No wrapping |
| `hyphens-auto` | Automatic hyphenation |
| `break-word` | Break long words |

### Print Utilities

| Class | Description |
|-------|-------------|
| `print-hidden` | Hide when printing |
| `print-only` | Show only when printing |
| `print-break-before` | Page break before |
| `print-break-after` | Page break after |
| `print-plain` | Remove backgrounds/shadows for print |

### Accessibility

| Feature | Description |
|---------|-------------|
| `::selection` | Themed text selection colors |
| `@media (prefers-reduced-motion)` | Disables animations automatically |
| `motion-reduce` | Force disable animations on element |
| `motion-safe` | Override reduced motion preference |

### Container Queries
| Class | Property |
|-------|----------|
| `container-size` | container-type: size |
| `container-inline` | container-type: inline-size |
| `container-normal` | container-type: normal |
| `-s`, `-m`, `-l` suffixes | Respond to container width |

### Responsive Suffixes (Media Queries)
| Suffix | Breakpoint |
|--------|------------|
| (none) | All screens |
| `-ns` | Not small (≥30em) |
| `-m` | Medium (≥48em) |
| `-l` | Large (≥60em) |

---

## 🎨 CSS Variables & Theming

Tachyons 5 uses CSS custom properties for easy theming:

```css
:root {
  --blue: #357edd;
  --spacing-1: 0.25rem;
  --spacing-2: 0.5rem;
  /* ... and many more */
}
```

Override them to customize your design system:

```css
:root {
  --brand-light: var(--blue-5);  /* Change brand color */
  --font-family-body: 'Inter', sans-serif;
}
```

### Dark Mode

Dark mode works automatically via `prefers-color-scheme`, or manually:

```html
<!-- Automatic (follows system preference) -->
<html>

<!-- Force light mode -->
<html color-scheme="light">

<!-- Force dark mode -->
<html color-scheme="dark">
```

The semantic color tokens (`--brand`, `--text`, `--surface-*`, etc.) automatically switch between light and dark palettes.

---

## 📜 Background

Tachyons 5 was originally designed by [Adam Morse](https://github.com/mrmrs) but the v5 branch remained unreleased for 2 years. After discussing with Adam, I took on maintaining and improving this version.

**What's different from Tachyons 4:**
- ✅ Full CSS Variables support
- ✅ Semantic theming with automatic dark mode
- ✅ Container Queries for component-based responsive design
- ✅ CSS Grid utilities (`grid`, `cols-*`)
- ✅ Simplified class names (`p4` instead of `pa4`)
- ✅ CSS Logical Properties for RTL/internationalization support
- ✅ OpenProps-inspired shadow system
- ✅ Dropdown & Dialog components with Popover API
- ✅ Form components (inputs, checkboxes, switches)
- ✅ Accessibility (focus rings, reduced motion, selection)
- ✅ Scroll snap & smooth scrolling utilities
- ✅ Skeleton loading animations
- ✅ Text wrap utilities (balance, pretty)
- ✅ Print styles
- ✅ Modern CSS features (aspect-ratio, gap, accent-color, etc.)
- ✅ No build step required
- ✅ Actively maintained

---

## 📄 License

MIT License — same as the original Tachyons.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Open issues for bugs or feature requests
- Submit pull requests
- Reach out for collaboration

---

<div align="center">

**Made with ❤️ by [Bijan](https://github.com/gobijan)**

[Original Tachyons 5 branch](https://github.com/tachyons-css/tachyons/tree/v5-final-final) by Adam Morse

</div>
