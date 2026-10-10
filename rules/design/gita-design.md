---
name: gita-design
description: "Agency-grade premium visual design standard with a mandatory proof gate. Load when the user writes or says #GitaDesign, 'Gita Design', 'hashtag Gita Design', or #apex, or asks for Apple-level, viral, 3D, interactive, gorgeous design on dashboards, sites, decks, ads, or visuals. Not for copy-only or data-only tasks with no visual output."
metadata:
  author: user
  version: '1.0'
  trigger: '#GitaDesign'
---

# #GitaDesign — Agency-Grade Design Standard (also triggered by #apex, gita design)

When the user writes `#GitaDesign`, every visual deliverable in the task must meet all 8 pillars below AND pass the proof gate. Saying you applied #GitaDesign without the scorecard is a failure.

## The 8 pillars

1. **Code-native, no template ceiling.** Hand-build layout, components, and charts. Never ship a default component-library, admin-template, or stock chart look. If it could be mistaken for a template, redo it.
2. **Art direction locked before code.** Write a one-line concept, pick 3 concrete references (named brands/sites/products), and define mood, palette, type, and one signature moment. Get the user's real brand assets first; never invent logos.
3. **Real content only.** Use the user's real data, names, products, and copy. No lorem ipsum, no fake round numbers presented as real. Demo data must be labeled as demo.
4. **Signature color and light.** Build a custom palette (OKLCH), with one hero color, rich multi-stop gradients, lighting, glow, and depth. Banned: default blue/indigo SaaS, generic purple-pink AI gradient, flat gray cards.
5. **Depth and 3D.** Layered glass/material surfaces, real shadows, parallax, and where it serves the piece, real-time 3D (Three.js / React Three Fiber) or CSS 3D transforms. Everything must feel physical, not flat.
6. **Motion with physics.** Spring-based transitions, count-up numbers, staggered reveals, hover/focus micro-interactions, 60fps, and `prefers-reduced-motion` respected. Motion must explain state changes, not decorate.
7. **Editorial typography.** A premium type pairing (display + text), dramatic scale contrast, tight display tracking, tabular numerals for data, and strict 8pt spacing. No default system-font look.
8. **One viral moment.** Each piece has one scroll-stopping, screenshot-worthy element (hero visual, 3D object, data reveal) someone would share.

## Proof gate (mandatory before delivery)

1. Render the output: screenshot desktop and mobile (plus TV 1920x1080 or 3840x2160 for screens/dashboards); for decks/PDFs, every page.
2. Inspect each screenshot for clipping, overlap, contrast, template look, and banned colors.
3. Score each pillar 1-5. Any pillar below 4 means iterate and re-render. Do not ship below 4.
4. In the final reply, include a compact scorecard table (pillar, score, one-line evidence) and attach at least one screenshot.

Completion condition: every pillar scores 4 or higher on the rendered output, and the scorecard appears in the reply.
