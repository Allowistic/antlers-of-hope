# Antlers of Hope Bar & Grill — Design Document

**Project:** High-fidelity static website prototype for Antlers of Hope Bar & Grill
**Repository:** https://github.com/Allowistic/antlers-of-hope
**Status:** Prototype for team review (as of 2026)

---

## 1. Project Goals & Design Philosophy

The website must feel like an authentic extension of the physical place on Highway 190 in Porterville, California.

Core principles:
- **Down-to-earth authenticity**: No corporate polish. Warm, lived-in, community-oriented.
- **Yellowstone TV show aesthetic**: Cinematic, warm, rugged Western romance without being overly theatrical.
- **Sierra foothills character**: Connect strongly to the Mighty 190, Springville, Success Lake, and the transition from oak woodlands to giant sequoias.
- **HOPE mission forward**: The bar & grill exists to support Helping One Person Everywhere Inc. The design should make the charitable purpose feel natural and integrated, not tacked on.

The site serves two audiences:
- Locals and regulars who already know the place
- Travelers and new visitors discovering it on the 190

---

## 2. Visual System

### Color Palette

- **Deep Charcoal / Night Sky**: `#1A1F24` — Primary background
- **Weathered Barn Wood**: `#3C2F2F` — Secondary surfaces, cards
- **Saddle Leather / Amber**: `#C68E42` — Primary accent, buttons, highlights
- **Aged Gold**: `#B8860B` — Secondary accent, embroidery feel
- **Warm Cream / Parchment**: `#F4EDE3` — Text on dark, light surfaces
- **Forest / Pine**: `#2E3C2E` — Occasional nature references

These colors are designed to work with both real photography (warm lighting, wood, dollar bills) and the generated/styled merch imagery.

### Typography

- **Display / Western Headings**: Playfair Display (serif) — Large, confident, slightly condensed. Used for major section titles and the logo treatment.
- **Body & UI**: Source Sans 3 / Inter (sans) — Readable, slightly warm, good screen performance.
- Letter-spacing is deliberately tight on headings for a strong, substantial feel.

### Textures & Details
- Subtle wood grain backgrounds on cards
- Leather-like depth on some surfaces
- Warm, directional lighting in all photography
- Embroidered patch aesthetic for merch (merrow borders, thread texture, slightly distressed)

---

## 3. Photography Strategy

The site uses a deliberate mix of imagery:

- **Real venue photography** (preferred for authenticity): Interior dollar-bill walls, live music on the patio, pool tables, dancing, food close-ups, exterior on the 190. These are being integrated from the owners' own photos.
- **Styled hero & merch photography**: High-quality, cinematic shots (e.g., the cowboy hat + t-shirt + patch hero image) that feel like they belong in the space.
- **Food photography**: Dedicated, appetizing shots of specific menu items (many added in later iterations).
- **Scenic context**: Highway 190 winding through the foothills.

Photography should feel warm and inviting at golden hour or with practical interior lighting. High contrast and rich shadows are encouraged.

---

## 4. Site Structure & Sections

Current major sections (single-page + supporting pages):

1. **Hero** — Strong establishing shot + tagline emphasizing location on the Mighty 190 and community purpose.
2. **Our Story** — Mike & Rhonda Harvey, the history of the property, and the HOPE nonprofit mission.
3. **The Bar & Grill** — Interior vibe, atmosphere, what makes it special (dollar bills, pool, live music, patio).
4. **Menu** — Hearty bar food with filtering. Real food photography is heavily featured.
5. **Live Music & Events** — Karaoke, weekend bands, community gatherings.
6. **Merch Store** — Embroidered patches and apparel. This is both a revenue stream and a way for people to carry the identity of the place.
7. **The Mighty 190 & Springville** — Celebrates the location and small-town foothills context.
8. **HOPE / Giving Back** — Clear, warm explanation of the charitable purpose.
9. **Visit** — Practical information (address, hours, phone, map).

There is also a dedicated `food.html` page for a deeper menu experience.

---

## 5. Merch & Patch Design Language

The merch program is an important part of the brand.

Design principles for patches and apparel:
- Embroidered, not printed — feels premium and traditional for a bar.
- Western / biker / roadhouse heritage mixed with local pride (Highway 190, HOPE mission).
- Limited color palette (gold/cream thread on dark felt backgrounds).
- Fun but respectful tone ("Karaoke Champion", "Pool Hall Legend" alongside the main identity patches).
- The hero merch photography should feel like it was shot inside or right outside the bar.

Current patches include:
- Main Antlers of Hope oval
- Mighty 190 shield
- Karaoke Champion
- Pool Hall Legend
- HOPE Inc.
- Classic Bar & Grill

Apparel mockups (hats, jackets, t-shirts) are used to show how the patches live in the real world.

---

## 6. Interaction & Component Patterns

- **Tailwind + CDN** for zero-build deployment.
- Menu filtering with active tab states.
- Image lightbox for gallery.
- Modal patterns for donations and merch waitlist.
- "Add to Cart" is currently simulated (high-fidelity prototype behavior). Real e-commerce can be added later.
- Smooth scrolling navigation.
- Responsive first, with mobile menu.

All interactive elements should feel warm and low-pressure, matching the bar's personality.

---

## 7. Tone & Copy Guidelines

- Warm, genuine, slightly wry — never salesy or corporate.
- Use "Bar & Grill" consistently (the term "roadhouse" was retired after early feedback).
- Emphasize community and the HOPE mission without being heavy-handed.
- Practical details (hours, address, phone) should be prominent and accurate.
- Photography captions and alt text should feel natural and descriptive.

---

## 8. Technical Notes

- Pure static site (HTML + Tailwind via CDN).
- Easy to host on GitHub Pages, Netlify, Vercel, or traditional hosting.
- Images should be optimized before production (current hero and food images are already resized).
- The site is designed to be easily updated by non-technical team members (simple HTML edits + image swaps).

---

## 9. Evolution & Future Considerations

- Replace more generated imagery with real venue photography as it becomes available.
- Add real donation processing (Stripe, Square, or nonprofit-friendly processor).
- Connect the Merch Store to actual inventory/fulfillment when the team is ready.
- Consider a small CMS or simpler content update workflow for specials and events.
- Possible expansion to a small multi-page experience (already started with food.html).
- Ensure the design continues to work well when printed or used in local flyers/posters.

---

## 10. Key References

- Original research: Location on CA-190, history from Mike & Rhonda Harvey, HOPE Inc. nonprofit mission, real menu items, live music/karaoke culture, dollar-bill walls, patio stage.
- Visual references: Yellowstone TV show color grading and mood, classic American roadhouse and honky-tonk aesthetics, embroidered patch traditions from biker and Western culture.
- Location context: The "Mighty 190" drive, Springville as the "Hidden Gateway" to Sequoia National Forest.

---

*This design document should be treated as a living reference. Update it as the prototype evolves into the final site.*
