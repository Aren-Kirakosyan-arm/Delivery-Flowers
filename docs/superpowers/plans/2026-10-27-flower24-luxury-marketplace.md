# Flower24 Luxury Marketplace Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task.

**Goal:** Turn the existing Flower24 visual prototype into a polished, conversion-focused luxury flower marketplace homepage for Yerevan.

**Architecture:** Keep the current no-framework static architecture for the prototype: one semantic HTML page with embedded CSS and vanilla JavaScript. The UI will be mobile-first and progressively enhanced; marketplace data is represented as local demo data until PHP/MySQL is connected.

**Tech Stack:** HTML5, CSS3, vanilla JavaScript, Google Fonts, responsive CSS.

**Spec:** Flower24 Luxury Marketplace homepage approved in conversation on 2026-10-27.

## Global Constraints

- Primary language: Armenian.
- Positioning: Flower24 is a marketplace connecting multiple Yerevan flower shops, not a single florist.
- Visual direction: premium, warm, editorial, modern; inspired by high-end marketplace UX rather than a generic florist template.
- Mobile-first and accessible keyboard focus states are required.
- No frontend framework.
- Subscription packages: 25,000 ֏ / 50,000 ֏ / 100,000 ֏.

## Review Focus

- Mobile hero/search must remain usable without horizontal overflow.
- Primary CTAs must remain visible and understandable at small widths.
- Product/shop cards must retain readable hierarchy when translated into Armenian.
- Interactive demo states must not depend on a backend.
- Images must have meaningful alt text and decorative imagery must not create accessibility noise.

### Task 1: Replace homepage visual system

**Files:**
- Modify: `index.html`

- [ ] Replace the existing visual hierarchy with the approved luxury marketplace layout: header, marketplace hero/search, trust strip, categories, popular products, nearby shops, subscription, how-it-works, reviews, FAQ, CTA and footer.
- [ ] Add responsive breakpoints and mobile bottom navigation.
- [ ] Add accessible labels, focus-visible states, semantic headings, and descriptive image alt text.

### Task 2: Add conversion interactions

**Files:**
- Modify: `index.html`

- [ ] Implement product add-to-cart state and cart counter.
- [ ] Implement favorite toggles.
- [ ] Implement subscription package selection feedback.
- [ ] Implement FAQ accordion.
- [ ] Implement search/filter demo behavior and clear empty-state messaging.
- [ ] Implement scroll-to-top control and mobile navigation state.

### Task 3: Verify published prototype

**Files:**
- Modify: `index.html`

- [ ] Re-fetch the committed file from GitHub and verify the new structure and critical scripts are present.
- [ ] Confirm the GitHub Pages deployment remains pointed at `main` and the public prototype URL is unchanged.
