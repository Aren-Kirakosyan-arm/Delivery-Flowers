# Flower24 Luxury Florist Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Upgrade the Flower24 homepage into a polished luxury florist experience with refined typography, richer SVG iconography, decorative botanical details, and professional micro-interactions.

**Architecture:** Keep the current static GitHub Pages architecture and existing product/filter/cart interactions. Improve the presentation through a redesigned `index.html` and an expanded external SVG sprite in `assets/icons/flower24-icons.svg`; do not introduce a framework or unnecessary dependencies.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, SVG, Google Fonts.

**Spec:** Flower24 homepage luxury florist direction selected by the user.

## Global Constraints
- Preserve Armenian-first content and mobile responsiveness.
- Keep the existing GitHub Pages deployment path.
- Use SVG icons rather than emoji or generic icon fonts for UI controls.
- Use typography appropriate for a premium flower shop.
- Keep the visual system restrained: ivory, blush, rose, burgundy and a subtle champagne accent.

## Review Focus
- External SVG symbols must render through `<use>` on GitHub Pages.
- Armenian text must remain legible at mobile sizes.
- Product cards and navigation must remain usable on narrow screens.
- Decorative elements must not cover interactive content.
- Search, favorites and cart interactions must remain functional.

### Task 1: Typography and visual system
**Files:** Modify `index.html`.
- Replace the previous typography treatment with a florist-focused serif/sans pairing.
- Introduce ivory/blush/burgundy/champagne variables and more refined spacing, borders and shadows.
- Preserve existing interactions and responsive breakpoints.

### Task 2: Expanded SVG system
**Files:** Modify `assets/icons/flower24-icons.svg`.
- Add botanical, decorative, navigation, social and service symbols using `currentColor`.
- Keep every symbol reusable with external `<use>` references.

### Task 3: Luxury composition
**Files:** Modify `index.html`.
- Add botanical line decorations, editorial hero treatment, refined category tiles, product cards, trust indicators and premium footer details.
- Add subtle hover/reveal transitions without heavy animation libraries.

### Task 4: Verification
- Validate HTML structure and all referenced SVG IDs.
- Verify JavaScript interactions remain present.
- Confirm GitHub Pages workflow deployment succeeds after the commit.
