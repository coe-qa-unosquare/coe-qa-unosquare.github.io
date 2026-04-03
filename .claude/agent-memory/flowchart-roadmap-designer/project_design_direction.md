---
name: QE Site Design Direction
description: Established design direction for the QE Center of Excellence site — sober, minimal dark theme, restrained palette
type: project
---

The QE Site targets a premium, professional aesthetic. User explicitly rejected "cheap" rainbow gradients and multicolor badges.

**Established palette (roadmaps.html as reference):**
- Background: `#0d0d0d` / card: `#131313`
- Borders: `#242424` (default), `#3a3a3a` (hover)
- Text: `#f0f0f0` / muted: `#888888` / dim: `#555555`
- Single accent: `#3b7dd8` (blue) — used sparingly for CTAs and links only

**Banned patterns:**
- Multicolor gradient top-borders on cards (green/yellow/red, cyan/blue gradients)
- Level badges with green/yellow/red color coding
- Gradient text headlines (`-webkit-text-fill-color: transparent` + gradient)
- Radial gradient `::before` hero backgrounds
- Excessive CSS variable definitions for colors that serve no minimal role

**Preferred patterns:**
- Flat card backgrounds with a single-pixel border, subtle hover (bg shift + border lighten)
- Typography-driven hierarchy: eyebrow labels (uppercase, spaced, dim), bold heading, muted body
- Module lists with a simple 4px dash bullet, no `>` chevron in accent color
- Single-color footer with a vertical pipe separator
- `nav` instead of `div` for the navigation bar
- No `translateY` card hover lift — just color shift

**Why:** User said "the page looks cheap" — the gradient borders and rainbow badges were the primary offenders.

**How to apply:** When building or revising any page on this site, default to this palette and avoid any element that introduces a third color. If a status indicator is needed, use opacity/lightness variants of the single accent rather than a new hue.
