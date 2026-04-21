# Dream Explorer — Tactile Dreamscape

> *A magical 3D journey through creativity. Sculpt your ideas in a digital playground designed for dreamers.*


---

## Overview

**Dream Explorer** is a fully responsive, one-page portfolio/experience website built with a **Pixar-inspired "Tactile Dreamscape"** design system. It blends soft physics, glassmorphism, orbital animations, and atmospheric lighting to create an interface that users don't just browse — they *explore*.

---

## Design System — "The Tactile Dreamscape"

| Token | Value | Usage |
|---|---|---|
| `primary` | `#07006C` | Deep navy — headings, buttons, icons |
| `primary-container` | `#8083FF` | Vibrant purple — gradients, accents, CTAs |
| `secondary` | `#C0C1FF` | Soft lavender — backgrounds, chips, bubbles |
| `surface` | `#FFFFFF` | White surfaces |
| `surface-container` | `#F3F3F4` | Light grey sections |

**Typography:**
- **Headlines** → `Plus Jakarta Sans` (bold, tight tracking)
- **Body** → `Be Vietnam Pro` (clean, geometric)

**Key Rules:**
- No sharp corners — everything uses `rounded-full`, `rounded-xl`, `rounded-[2.5rem]`
- No solid borders — boundaries defined through tonal color shifts
- Spring transitions → `cubic-bezier(0.175, 0.885, 0.32, 1.275)`
- Glassmorphism on all floating elements
- Ambient diffused shadows (never pure black)

---

## Sections

| # | Section | Description |
|---|---|---|
| 1 | **Hero** | Radial gradient sky, floating 3D islands, animated orbs, CTA buttons |
| 2 | **Features Bento** | 4-card responsive grid — Sculpted Reality, Magic AI, Collaborate, Tactile Response |
| 3 | **About** | Asymmetric layout with avatar + floating info bubbles + mission bento cards |
| 4 | **Projects** | 6-card bento portfolio grid with hover animations and image overlays |
| 5 | **Skills** | Immersive orbital animation — 5 skill nodes orbiting a glowing core |
| 6 | **Contact** | Dual-column layout with glowing contact form + success feedback state |
| 7 | **Footer** | Clean footer with nav links |

---


## Project Structure

```
Dream Explorer/
├── index.html        # Complete single-page website (all sections)
└── README.md         # This file
```

> All sections are consolidated into a single `index.html` — no build tools, no dependencies, no node_modules required.

---

## Design Inspiration

The **Tactile Dreamscape** design system draws from:
- **Pixar/Disney** — soft volumes, depth, and light-emitting elements
- **Glassmorphism** — frosted glass with layered translucency
- **Editorial design** — extreme typographic scale contrast
- **Neumorphism (subtle)** — soft inset shadows on interactive wells

---

## License

MIT © 2024 Dream Explorer. Built with imagination.

---

<p align="center">
  <em>Sculpted in the Tactile Dreamscape. Every pixel hand-crafted.</em>
</p>
