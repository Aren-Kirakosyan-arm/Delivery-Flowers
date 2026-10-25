# Flower24 Mobile-First Home Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a polished Armenian-first, mobile-first Flower24 marketplace homepage on top of the existing GitHub Pages demo.

**Architecture:** Keep the site as a single self-contained `index.html` so GitHub Pages can serve it directly. Use semantic HTML, CSS custom properties/responsive media queries, inline SVG icons, and a small vanilla JavaScript layer for search, favorites, cart state, and navigation behavior.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, inline SVG, Google Fonts, remote product photography.

**Spec:** `docs/superpowers/specs/2026-10-25-flower24-mobile-home.md`

## Global Constraints
- Armenian is the primary UI language.
- No frontend framework or icon package.
- GitHub Pages must continue serving the root `index.html`.
- Mobile width target includes 390px with no horizontal overflow.
- Keep the existing Flower24 brand direction: pink, white, graphite, premium/minimal.

## Review Focus
- 390px viewport: no horizontal overflow and bottom navigation does not cover content.
- Broken external image: layout remains intact with useful alt text/background.
- Empty search query: all products return.
- Search query with no match: clear empty state appears.
- Repeated add-to-cart clicks: badge increments predictably and button state remains readable.

---

### Task 1: Replace the visual prototype with the mobile-first Flower24 experience

**Files:**
- Modify: `index.html`

**Interfaces:**
- Produces: complete static homepage plus client-side UI interactions defined in the spec.

- [ ] **Step 1: Add semantic app shell, hero, category rail, product cards, shops, benefits, footer, and mobile navigation.**
- [ ] **Step 2: Add responsive CSS for mobile-first and desktop breakpoints.**
- [ ] **Step 3: Add inline SVG icon system and accessible labels/focus states.**
- [ ] **Step 4: Add vanilla JavaScript for search, category filtering, favorites, cart badge, and menu behavior.**
- [ ] **Step 5: Verify the generated HTML structure and JavaScript syntax locally before publishing.**
- [ ] **Step 6: Commit with `feat: build Flower24 mobile-first homepage`.**

### Task 2: Verify GitHub Pages deployment content

**Files:**
- Read: `index.html`
- Read: `.github/workflows/pages.yml`

**Interfaces:**
- Consumes: the updated root `index.html` and existing Pages workflow.
- Produces: a deployable GitHub Pages root.

- [ ] **Step 1: Fetch the committed `index.html` and confirm the new mobile UI markers exist.**
- [ ] **Step 2: Confirm the Pages workflow still points at the repository root artifact.**
- [ ] **Step 3: Report the exact GitHub Pages URL and verification result.**
