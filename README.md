# Nebula UI — Futuristic Admin Dashboard

An ultra-modern, fully responsive admin dashboard layout built with **pure HTML & CSS** — zero JavaScript.

## 🔴 Live Demo

**✅ Verified — renders the real styled dashboard (HTML Preview service):**

> ### https://htmlpreview.github.io/?https://raw.githubusercontent.com/merabeto124-debug/Futuristic-Admin-Dashboard/1d2e58403a568bdd426290a74cc80d8930338c92/standalone.html

*(Pinned to an exact commit — this link never breaks.)*

**Always-latest version** (follows `main`):

```
https://htmlpreview.github.io/?https://raw.githubusercontent.com/merabeto124-debug/Futuristic-Admin-Dashboard/main/standalone.html
```

**Backup** (jsDelivr/githack serve HTML as plain text or with a one-click confirmation, so HTML Preview above is the recommended link).

> ℹ️ `standalone.html` is a build of the dashboard with `styles.css` inlined — it renders anywhere, even hosts that ignore relative paths. The canonical source stays `index.html` + `styles.css`.

## ✨ Features

- **CSS Grid + Flexbox** layout system (grid app shell, flex header/rows)
- **Fixed sidebar** with inline-SVG icons, active-state neon indicator, badge counts, and an upgrade card
  - Collapses to an icon rail ≤ 1100px
  - Becomes a slide-in drawer ≤ 768px (pure-CSS checkbox hack, no JS)
- **Sticky header** with search bar (⌘K hint), live status pill, notification & theme buttons, user profile
- **4 stat cards** with a full **glassmorphism hover effect** (backdrop blur, neon glow, lift, tinted sparklines)
- **Large chart placeholder** — hand-built SVG line/area chart with draw animation, dashed comparison line, pulsing dots, legend & segmented range control
- **Side panel** with a conic-gradient storage ring and animated goal bars
- **Recent activity table** — status pills, gradient initial avatars, row hover, horizontally scrollable on small screens
- **Dark Mode palette via CSS variables** — deep navy `#0b0f19`, neon accent `#6366f1`, cyan/green/amber/red tints
- **Smooth transitions everywhere** (hover lifts, glows, sheens) with a `prefers-reduced-motion` fallback
- Ambient blurred background blobs that feed the glass blur effects

## 🚀 Run

Any static server works:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

Or just open `index.html` in a browser.

## 📁 Files

| File         | Purpose                          |
| ------------ | -------------------------------- |
| `index.html` | Structure + inline SVG icons     |
| `styles.css` | All styling (tokens → responsive)|
