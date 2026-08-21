# GenLayer Loading Spinner

An original animated spinner built from the official **GenLayer mark**.

Designed for the GenLayer Portal — loading pages, buttons, cards, and any loading state.

> Clean · Smooth · Unmistakably GenLayer

---

## Preview

Open [`index.html`](./index.html) in a browser to see all variants.

| Size | Class | Use case |
|------|-------|----------|
| 24px | `.sm` | Inline text, small buttons |
| 40px | `.md` | Cards, list items |
| 48px | (default) | General loading |
| 64px | `.lg` | Page-level loading |
| 96px | `.xl` | Full-screen / splash |

Works on both **dark** (`#070707`) and **light** (`#F5F5F5`) backgrounds.

---

## Quick Start

### CSS + SVG (recommended)

```html
<link rel="stylesheet" href="genlayer-spinner.css">

<div class="gl-spinner" aria-label="Loading">
  <svg viewBox="0 0 97.76 91.93" xmlns="http://www.w3.org/2000/svg">
    <g class="wing-left">
      <polygon fill="currentColor" points="44.26 32.35 27.72 67.12 43.29 74.9 0 91.93 44.26 0 44.26 32.35"/>
    </g>
    <g class="wing-right">
      <polygon fill="currentColor" points="53.5 32.35 70.04 67.12 54.47 74.9 97.76 91.93 53.5 0 53.5 32.35"/>
    </g>
    <g class="diamond">
      <polygon fill="currentColor" points="48.64 43.78 58.33 62.94 48.64 67.69 39.47 62.92 48.64 43.78"/>
    </g>
  </svg>
</div>


