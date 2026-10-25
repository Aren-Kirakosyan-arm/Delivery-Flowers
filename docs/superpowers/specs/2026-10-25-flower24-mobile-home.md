# Flower24 Mobile-First Home — Design Spec

## Goal
Turn the existing Flower24 visual demo into a polished, mobile-first flower marketplace homepage that feels like a real Armenian delivery app while remaining a static GitHub Pages demo.

## Audience and outcome
Primary audience: Armenian users in Yerevan looking for flowers and gifts. The first screen should immediately communicate what Flower24 does, surface popular categories/products, and make search and cart actions obvious.

## Experience
- Armenian-first copy and typography.
- Premium but approachable white/pink/graphite visual system.
- Mobile-first layout with fixed bottom navigation on small screens.
- Desktop layout remains polished and spacious.
- Inline SVG icons; no icon package or framework dependency.
- Lightweight interactions: search filtering, favorite toggle, cart count, mobile menu state, and category/product navigation.
- Keep GitHub Pages compatibility: a self-contained `index.html` with no PHP dependency.

## Non-goals
- Real authentication, checkout, payments, seller dashboard, or database in this phase.
- No frontend framework.

## Content sections
1. Sticky app-style header.
2. Hero/search area with delivery promise.
3. Horizontal category rail.
4. Popular bouquets grid.
5. Partner shops strip.
6. 24/7 delivery feature banner.
7. Trust/payment benefits.
8. Footer and mobile bottom navigation.

## Success criteria
- Works at 390px mobile width without horizontal overflow.
- Desktop remains usable at 1440px.
- Search filters visible product cards by title/category.
- Add-to-cart increments cart badge and changes button state.
- Favorite buttons toggle state.
- All primary actions have accessible labels/focus styles.
- Page remains usable if external product images fail to load.
