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
| 📦 **Zero Build** | No npm, no webpack, no PostCSS — just drop it in |
| 📱 **Responsive** | Mobile-first with media queries AND container queries |
| 🔲 **CSS Grid** | Native grid support with `cols-*` and `g*` gap utilities |
| 📦 **Container Queries** | Modern component-based responsive design |
| ⚡ **~1900+ Utilities** | Spacing, typography, colors, flexbox, grid & more |
| 🪶 **~29kb gzipped** | Lightweight and fast |
| 🔧 **Maintained** | Actively maintained and updated |

---

## 📖 Usage Examples

**Responsive Card**
```html
<article class="mw5 center bg-white br3 p3 p4-ns mv3 ba b--light">
  <div class="tc">
    <img src="avatar.jpg" class="br-100 h4 w4 dib ba b--light p2" alt="avatar">
    <h1 class="f3 mb2">Jane Doe</h1>
    <h2 class="f5 fw4 gray mt0">Developer</h2>
  </div>
</article>
```

**CSS Grid Layout**
```html
<div class="grid cols-1 cols-2-m cols-4-l g3">
  <div class="p3 bg-light-gray">Item 1</div>
  <div class="p3 bg-light-gray">Item 2</div>
  <div class="p3 bg-light-gray">Item 3</div>
  <div class="p3 bg-light-gray">Item 4</div>
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
<button class="f6 link dim br3 ph3 pv2 mb2 dib white bg-dark-blue bn pointer">
  Click Me
</button>
```

---

## 🎯 Class Reference (Cheat Sheet)

### Spacing
| Class | Property | Scale |
|-------|----------|-------|
| `p0` - `p9` | padding: all | 0 - 256px |
| `m0` - `m9` | margin: all | 0 - 256px |
| `pt0`, `pr0`, `pb0`, `pl0` | padding: directional | top, right, bottom, left |
| `mt0`, `mr0`, `mb0`, `ml0` | margin: directional | top, right, bottom, left |
| `g0` - `g7` | gap | 0 - 256px |

### Typography
| Class | Description |
|-------|-------------|
| `f1` - `f7` | Font sizes (3rem → 0.75rem) |
| `fw1` - `fw9` | Font weights |
| `tl`, `tc`, `tr`, `tj` | Text align |
| `ttc`, `ttu`, `ttl` | Text transform |
| `lh-solid`, `lh-title`, `lh-copy` | Line heights |

### Colors
| Class | Example |
|-------|---------|
| `blue`, `red`, `green`, `yellow`... | Text colors |
| `bg-blue`, `bg-red`, `bg-green`... | Background colors |
| `b--blue`, `b--red`... | Border colors |

### Flexbox & Grid
| Class | Property |
|-------|----------|
| `flex`, `inline-flex` | display: flex |
| `grid`, `inline-grid` | display: grid |
| `cols-1` - `cols-16`, `cols-24` | grid-template-columns |
| `flex-row`, `flex-column` | flex-direction |
| `justify-center`, `justify-between`... | justify-content |
| `items-center`, `items-start`... | align-items |

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

## 🎨 CSS Variables

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
  --blue: #0066cc;
  --font-family-sans: 'Inter', sans-serif;
}
```

---

## 📜 Background

Tachyons 5 was originally designed by [Adam Morse](https://github.com/mrmrs) but the v5 branch remained unreleased for 2 years. After discussing with Adam, I took on maintaining and improving this version.

**What's different from Tachyons 4:**
- ✅ Full CSS Variables support
- ✅ Container Queries for component-based responsive design
- ✅ CSS Grid utilities (`grid`, `cols-*`)
- ✅ Simplified class names (`p4` instead of `pa4`)
- ✅ Modern CSS features (aspect-ratio, gap, etc.)
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
