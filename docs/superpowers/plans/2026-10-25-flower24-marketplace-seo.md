# Flower24 Marketplace SEO Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Turn Flower24 from a visual florist landing page into a marketplace-style Yerevan flower discovery experience with strong SEO foundations.

**Architecture:** Keep the current static prototype compatible with GitHub Pages while designing the information architecture so it can later map directly to PHP/MySQL entities: shops, products, categories, districts, orders and reviews. The homepage becomes a marketplace discovery surface with intent-based filters, delivery speed, ratings, shop comparison cues and trust signals.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, SVG sprite, responsive design, GitHub Pages-compatible static assets.

**Spec:** Existing Flower24 project context and competitor research from October 25, 2026.

## Global Constraints

- Primary market: Yerevan, Armenia.
- Primary language: Armenian; preserve Russian/English SEO expansion paths for the next phase.
- No frontend framework for the prototype.
- Preserve premium luxury-florist visual direction.
- Do not create thin doorway pages or duplicate district pages.
- Marketplace claims such as real stock, delivery ETA and ratings must be clearly presented as demo data until backed by the database.

## Review Focus

- Mobile-first interaction must remain usable on small screens.
- Search/filter state must not produce misleading empty results.
- Demo delivery and availability labels must be clearly distinguishable from live data.
- SEO files must point to the real GitHub Pages canonical URL until a production domain is connected.
- Existing SVG icon sprite usage must continue working.

---

### Task 1: Marketplace homepage

**Files:**
- Modify: `index.html`

**Interfaces:**
- Consumes existing `assets/icons/flower24-icons.svg`.
- Produces marketplace-style homepage UI and interactions.

- [ ] Add intent-first hero CTA: recipient, occasion, budget and delivery timing.
- [ ] Add fast-delivery and verified-shop trust cues.
- [ ] Add product cards with rating, shop, ETA, availability and price.
- [ ] Add compare controls and an inline comparison tray.
- [ ] Add shop cards with open status and delivery capabilities.
- [ ] Add Yerevan district discovery.
- [ ] Add FAQ/SEO copy and crawlable internal links.
- [ ] Keep responsive luxury styling and mobile bottom navigation.

### Task 2: Crawl/index foundation

**Files:**
- Create: `robots.txt`
- Create: `sitemap.xml`

- [ ] Add robots rules for public pages.
- [ ] Add sitemap entries for the homepage and initial SEO landing pages.
- [ ] Use GitHub Pages URL as temporary canonical origin.

### Task 3: SEO landing pages

**Files:**
- Create: `seo/dostavka-cvetov-erevan.html`
- Create: `seo/rozy.html`
- Create: `seo/bukety.html`

- [ ] Give each page unique title, description, H1 and useful Yerevan-specific copy.
- [ ] Link each page back to the marketplace and to related categories.
- [ ] Avoid copied templates and keyword stuffing.

### Task 4: Verification

- [ ] Validate HTML structure and links.
- [ ] Confirm GitHub Pages workflow remains present.
- [ ] Confirm sitemap and robots are reachable from the repository site.
- [ ] Confirm mobile layout and JavaScript interactions in a browser-capable environment.
- [ ] Commit the complete marketplace/SEO change as one coherent feature commit.
