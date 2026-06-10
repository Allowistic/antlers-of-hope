---
version: alpha
name: Antlers of Hope
description: Visual identity and design system for Antlers of Hope Bar & Grill on the Mighty 190 in Porterville, California. A down-to-earth, cinematic roadhouse aesthetic blending Yellowstone-inspired warmth with authentic small-town Sierra foothills character. Supports the HOPE Inc. mission of neighbors helping neighbors.
colors:
  charcoal: "#1A1F24"
  barn-wood: "#3C2F2F"
  leather: "#6B4E31"
  amber: "#C68E42"
  gold: "#B8860B"
  cream: "#F4EDE3"
  forest: "#2E3C2E"
typography:
  display:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "72px"
    fontWeight: 700
    lineHeight: 0.88
    letterSpacing: "-0.02em"
  heading:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "48px"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Source Sans 3, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Source Sans 3, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.1em"
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
  full: "9999px"
spacing:
  base: "16px"
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "32px"
  xl: "64px"
  gutter: "24px"
components:
  button:
    primary:
      background: "{colors.amber}"
      color: "{colors.charcoal}"
      borderRadius: "{rounded.md}"
  card:
    background: "{colors.barn-wood}"
    border: "1px solid rgba(255,255,255,0.1)"
    borderRadius: "{rounded.md}"
  patch:
    border: "merrow edge"
    background: "dark felt"
    thread: "{colors.gold}, {colors.cream}"
---

# Antlers of Hope

## Overview

Antlers of Hope is a classic, laid-back Bar & Grill located at 30990 Highway 190 in Porterville, California, right on the scenic "Mighty 190" route through the Sierra foothills toward Springville and the giant sequoias.

The visual identity must feel like an authentic extension of the physical place: dollar-bill-covered wooden walls, pool tables, warm Edison lighting, live music on the patio, friendly locals, and a strong sense of community. The design blends the cinematic, warm, rugged romance of the TV show *Yellowstone* with genuine small-town roadhouse character.

**Brand personality:** Down-to-earth, warm, cinematic, unpretentious, community-first, with a touch of Western heritage. It should feel like a place where neighbors gather — hearty food, cold drinks, live music, and real support for the HOPE Inc. nonprofit (Helping One Person Everywhere), which uses proceeds from the bar to help families facing serious medical challenges.

The system applies to the website (single-page experience + dedicated food page), merchandise (embroidered patches and apparel), and any future print or digital collateral.

Target emotional response: Inviting, grounded, slightly nostalgic, confident, and hopeful. Not corporate, not overly polished, not generic stock photography.

## Colors

The palette is rooted in the real materials and lighting of the bar: weathered wood, leather, warm amber practical lighting, cream parchment, and the deep forest tones of the surrounding Sierra foothills.

- **Charcoal (#1A1F24):** Deep night-sky background. Primary surface for the site. Evokes evening at the bar with practical lighting.
- **Barn Wood (#3C2F2F):** Secondary card and container color. Matches the actual wooden walls and bar.
- **Leather (#6B4E31):** Subtle depth for accents and textures.
- **Amber (#C68E42):** Primary action and highlight color. The warm glow of the bar at golden hour and the main call-to-action color.
- **Gold (#B8860B):** Secondary accent, especially for embroidered elements and fine details. Feels like thread on a patch.
- **Cream (#F4EDE3):** Warm off-white for text on dark backgrounds and light surfaces. Avoids harsh pure white.
- **Forest (#2E3C2E):** Occasional nature reference for the Mighty 190 and sequoia context.

All colors are chosen for high readability in low-light bar conditions and to work beautifully with real photography of the space.

### Design Tokens

```yaml
colors:
  charcoal: "#1A1F24"
  barn-wood: "#3C2F2F"
  leather: "#6B4E31"
  amber: "#C68E42"
  gold: "#B8860B"
  cream: "#F4EDE3"
  forest: "#2E3C2E"
```

## Typography

Two type families create the Western yet approachable voice.

- **Display / Western Headings:** Playfair Display (serif). Large, confident, slightly condensed with tight tracking. Used for the logo treatment ("ANTLERS OF HOPE") and major section titles. Evokes classic signage and a sense of place.
- **Body & UI:** Source Sans 3 (or Inter). Readable, slightly warm, excellent screen performance. Used for all body text, menus, and interface elements.

Headlines feel substantial and grounded. Body text prioritizes long-form readability for the story and menu sections.

### Design Tokens

```yaml
typography:
  display:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "72px"
    fontWeight: 700
    lineHeight: 0.88
    letterSpacing: "-0.02em"
  heading:
    fontFamily: "Playfair Display, Georgia, serif"
    fontSize: "48px"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Source Sans 3, system-ui, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Source Sans 3, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.1em"
```

## Layout

The layout follows a generous, human-scale rhythm inspired by a real bar interior and the winding drive of the Mighty 190.

Use a fluid, single-column experience on mobile that expands into comfortable multi-column grids on larger screens. Maximum content width around 1400–1600px for the main experience.

A consistent 8px base spacing scale (with 4px micro-steps) creates visual rhythm. Cards and sections use generous internal padding (24–32px) to feel like solid wooden tables and booths rather than tight digital boxes.

Navigation is sticky and minimal — logo + links on desktop, hamburger on mobile. Strong use of full-bleed or near-full-bleed hero and gallery imagery to immerse the visitor in the place.

## Elevation & Depth

Depth is achieved primarily through tonal layers, warm shadows, and material texture rather than heavy drop shadows.

- Dark charcoal backgrounds with slightly lighter barn-wood cards create natural separation.
- Subtle wood-grain textures and leather-like gradients on surfaces.
- Photography with strong directional lighting and rich shadows provides the cinematic depth.
- For interactive elements (buttons, cards), use a combination of the amber accent and a gentle lift on hover (small transform + shadow).

Avoid flat, paper-like interfaces. The goal is to feel like a well-lit wooden bar with real objects on it.

## Shapes

The shape language is warm and hand-crafted with subtle architectural references.

- Cards and containers use soft but not overly rounded corners (8–12px) — reminiscent of well-worn furniture.
- Buttons are rectangular with moderate rounding to feel solid and approachable.
- Embroidered patches use traditional oval, shield, and circular forms with merrow (fabric) borders. These shapes are a key brand motif and should feel tactile.
- Antler motifs and Highway 190 shield elements appear in logos, patches, and subtle decorative details.

## Components

**Buttons:** Primary buttons use the amber background with charcoal text. Secondary are outline or cream-on-dark. All have clear hover states that feel like reaching for a cold drink.

**Cards & Sections:** Use barn-wood or charcoal with subtle borders. Generous padding. Often paired with strong photography.

**Navigation:** Clean, high-contrast links. Logo treatment uses the Playfair "ANTLERS OF HOPE" lockup with a small antler SVG.

**Gallery & Lightbox:** Full-bleed or grid photography with warm overlays. Clicking opens a clean lightbox focused on the image.

**Menu:** Tab-filtered cards with food photography. Left accent bar in amber for visual interest.

**Merch / Patches:** Patches are shown both as isolated embroidered objects and applied to real apparel (hats, jackets, t-shirts). The design system treats the embroidered aesthetic (gold/cream thread on dark felt, slight distress) as a core component style.

**Modals:** Used for donations to HOPE and merch waitlist. Dark overlays with warm content cards.

**Forms:** Simple, high-contrast inputs that match the bar's practical feel.

## Do's and Don'ts

**Do:**
- Use real venue photography whenever possible (dollar bills on walls, live music, pool tables, food on wooden surfaces, exterior on the 190).
- Lean into warm, directional lighting and rich shadows.
- Treat embroidered patches and the antler/190 motifs as signature brand elements.
- Keep copy warm, genuine, and slightly wry — "Pull up a stool," "Where the highway meets heart."
- Make the HOPE mission feel integrated and natural.
- Maintain generous breathing room and solid, furniture-like containers.

**Don't:**
- Use generic stock photography or overly polished corporate imagery.
- Go too dark or moody without the compensating warmth of amber and cream.
- Use pure white or cold blue tones.
- Make buttons or cards feel digital and flat.
- Overuse heavy modern gradients or glassmorphism.
- Treat the charitable aspect as an afterthought or separate "non-profit" section only.
- Use thin, delicate typography for headlines — the voice should feel substantial.

---

*This DESIGN.md serves as the single source of truth for the visual identity. It can be used by humans and future AI tools to maintain consistency across the website, merchandise, photography direction, and any new touchpoints.*