# Type, Color & Depth — Premium Systems

The craft layer. Read when defining the type/color/depth system (Step 2) or producing any visual or web deliverable.

## Premium type pairings

Pick a **display** face for impact and a **workhorse** for clarity. Use dramatic scale contrast (display 4–8× body). All pairings below are high-end and widely available as web fonts.

| Vibe | Display | Workhorse / Body |
|---|---|---|
| Editorial luxury | Canela, Tiempos Headline, or Playfair Display | Inter, Söhne, or Neue Haas Grotesk |
| Modern premium tech | Clash Display, General Sans | Inter, Geist |
| Bold viral / punchy | Anton, Druk, or Archivo Black | Helvetica Now, Inter |
| Refined fashion / atelier | Canela, Ogg, or Cormorant | Suisse Int'l, Inter |
| Warm humanist | Reckless, Fraunces | Mona Sans, Inter |

**Typesetting rules**
- Headlines: tighten tracking (-1% to -3%), tighten leading (0.9–1.05×).
- Body: leading 1.4–1.6×, measure 45–75 characters.
- Use real weight contrast (e.g., 800 display vs 400 body), not just size.
- One display + one workhorse. A third face is rarely justified.
- Optical kerning on big type; fix awkward letter pairs by hand.

## Color-system recipes

Commit to a point of view. A premium palette = **one dominant + one precise accent + controlled neutrals**, with tonal depth (tints/shades) of each.

Recipe template:
- **Dominant** (60%): the brand mood (e.g., deep emerald, ink navy, warm bone).
- **Accent** (10%): the pop that drives the eye — used on CTAs, one hero word, a glow.
- **Neutrals** (30%): off-whites and near-blacks, never pure #FFFFFF/#000000 for large fields — use #0A0A0B / #F7F5F0 ranges for richness.

Ready-to-use premium palettes:
- **Longevity / wellness premium** — bone `#F4F1EA`, deep emerald `#0E3A2F`, gold accent `#C9A24B`, ink `#11130F`.
- **Luxe dark editorial** — near-black `#0B0B0D`, bone text `#EDEAE3`, champagne accent `#D9B98B`.
- **Modern tech viral** — off-white `#F6F7F9`, ink `#0E1116`, electric accent `#3B5BFF`, soft violet glow `#7C5CFF`.
- **Fashion atelier** — warm bone `#EFE9DF`, espresso `#2B211B`, terracotta accent `#C66B4A`.

**Gradient & glow guidance** — use multi-stop gradients in the same hue family for depth; add a soft radial glow behind the focal element; avoid muddy complementary-color gradients.

## Depth, shadow & 3D treatment (signature)

This is what makes the work feel premium and "real," not flat or AI-generic.

- **Layered shadows, not one.** Stack 2–3 shadows: a tight contact shadow (small blur, low spread, ~20% opacity) + a soft ambient shadow (large blur, low opacity) + optional colored shadow tinted from the accent.
  - CSS example:
    ```css
    box-shadow:
      0 1px 2px rgba(10,12,16,0.18),
      0 12px 32px rgba(10,12,16,0.12),
      0 24px 64px rgba(60,91,255,0.10);
    ```
- **Ambient occlusion.** Where layers meet, darken the seam slightly — sells contact and depth.
- **Z-axis layering.** Foreground elements: larger, sharper, stronger shadow. Background: smaller, blurred, lifted lighter.
- **Subtle 3D transforms (web).** `transform: perspective(1000px) rotateX(4deg) rotateY(-6deg)` on hero cards; pair with a matching directional shadow.
- **Glassmorphism (when apt).** `backdrop-filter: blur(20px)` + 1px inner highlight border + faint top sheen — premium for overlays/nav.
- **Lighting consistency.** Pick one light direction and make every shadow and highlight obey it.
- **For generated images** — explicitly prompt: "volumetric soft studio lighting, realistic layered drop shadows, soft ambient occlusion, shallow depth of field, premium 3D-rendered feel."

## Motion (so static extends to video)

- Entrances: scale-up from 0.96 + fade + slight upward drift, with a gentle overshoot-and-settle (ease-out-back).
- Hover/scroll: parallax on layered elements; shadow grows + element lifts on hover.
- Respect `prefers-reduced-motion` in web builds.
