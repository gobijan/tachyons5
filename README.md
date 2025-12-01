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
| 🌐 **Logical Properties** | RTL-ready with `start`/`end` instead of `left`/`right` |
| 📦 **Container Queries** | Modern component-based responsive design |
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
- ✅ CSS Logical Properties for RTL/internationalization support
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
