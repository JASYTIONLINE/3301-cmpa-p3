---
title: "Final Project Scope Statement — Project 03"
author: "John Barkle IV"
course: "CMPA 3301 — Fundamentals of Computing Applications"
date: "Sep 21, 2025"
---

# Project 03 — Final Project Scope Statement

## Project Name
This Is Your Song — **Proof of Concept** Front Page

## Project Purpose
Design a **rough, small, functional** two-page retail front for **This Is Your Song**, a service that turns a customer’s story into a custom, production-ready song. The site is a simple public door: explain the offering, **demonstrate stylistic range**, and provide a low-friction way to initiate contact by email. Goal: disciplined scope and delivery using **basic HTML/CSS only**.

## Description
A dedicated GitHub repository will host a **two-page HTML/CSS website** deployed on **GitHub Pages**, plus minimal assets.

**Page 1 — `index.html` (Home / Front Page)**
- Top banner: **“This Is Your Song.”**
- One-paragraph service explainer (custom songs from customer stories; currently free / not for sale).
- A single **clickable jingle icon** that plays a short audio “hook” (basic `<audio>` or simple link/embed).
- Bottom nav: **“Take me to the catalog”** → routes to Page 2.

**Page 2 — `catalog.html` (Portfolio Demonstrator)**
- Top banner consistent with Home.
- **Four clickable audio thumbnails** (icon + caption), each playing **the same lyrics** in **four different genres** (text captions; basic audio links/`<audio>`).
- **Contact CTA** beneath the four icons:
  - An **embedded PDF or image** of a short intake form as a **visual prompt** (what to include in the email: Name, Email, Preferred Genre(s), Story, optional examples).
  - A **mailto** button that opens the user’s email client:  
    `mailto:jasytionline@gmail.com?subject=This%20Is%20Your%20Song%20—%20New%20Request`  
    with on-page text instructing the user to **hand-type** the items shown on the embedded prompt.
- Bottom nav: **Back to Home**.

> Notes  
> • Audio uses basic HTML (`<audio>` or plain links).  
> • Any “radio buttons” referenced in earlier drafts are implemented as **standard links/buttons** (no form inputs).

## Desired Results (Measurable Deliverables)
- Two HTML pages (Home, Catalog) live on GitHub Pages.
- Home (`index.html`): banner + logo, one-paragraph explainer, **one clickable jingle** with image, nav link to Catalog.
- Catalog (`catalog.html`): banner + image, **four audio thumbnails** (same lyrics, four genres), **embedded intake PDF/image prompt**, **mailto** CTA with clear instructions, link back to Home.
- Reciprocal navigation (Home ⇄ Catalog).
- `docs/` folder contains:
  - `final-project-scope.md`
  - `project-plan.md`
  - `project-retrospective.md`
- Repository `README.md` introduces the project and summarizes the two-page prototype.

## Site Hosting
Hosted via **GitHub Pages** at:  
**https://jasytionline.github.io/this-is-your-song/**

## Standards & Sources
- **HTML/CSS limited to techniques covered in course materials and previously supplied resources.**
- **No third-party CSS/JS frameworks, libraries, or outside tutorials** beyond course-provided references.
- Styling remains **basic CSS** (no advanced/complex patterns beyond course coverage).
- Maintain separation of concerns (inline style is permitted if functionally appropriate).

## Exclusions (Out of Scope)
- No e-commerce (cart/checkout/payment).
- No user accounts, databases, or **server-side code**.
- **No web forms** (no text inputs/selects/radio/submit). The **PDF/image is a prompt only**; email is manual via `mailto:`.
- No external CSS/JS frameworks or CMS.
- No more than **two** HTML content pages.

## Priorities (Trade-off Guidance)
1. **Clarity & professionalism of content & IA** (fit for a retail front).
2. **Reliable audio demos** (one jingle on Home; four genre demos on Catalog).
3. **Deployment reliability** on GitHub Pages (fast, simple assets).
4. **Aesthetics** beyond basic CSS = lowest priority.

## Acceptance Criteria (Objective Checklist)

### Repository & Structure
- [ ] Project is in a dedicated GitHub repository with **GitHub Pages enabled**.
- [ ] `docs/` contains: `final-project-scope.md`, `project-plan.md`, `project-retrospective.md`.
- [ ] `README.md` clearly describes the **This Is Your Song** project.
- [ ] Live site is reachable at **https://jasytionline.github.io/this-is-your-song/** and renders **both pages**.
- [ ] Styling uses only course-material HTML/CSS; **no frameworks/third-party tutorial code**; pages render with **no console errors**.

### Home Page
- [ ] Top banner shows **“This Is Your Song.”**
- [ ] Include one image/logo.
- [ ] One paragraph explains the service and notes it is currently free / not for sale.
- [ ] A single **jingle icon** is clickable and plays an audio “hook.”
- [ ] Bottom navigation includes a clearly labeled link/button: **“Take me to the catalog.”**

### Catalog Page
- [ ] Top banner and page styling are consistent with Home.
- [ ] **Four** clickable **audio thumbnails** (image + caption) each playing a different **genre** rendering of the **same lyrics**.
- [ ] An **embedded PDF/image** displays the intake **prompt** (fields to include).
- [ ] A **mailto** CTA opens the user’s email client with prefilled subject **“This Is Your Song — New Request”**; on-page text instructs the user to **hand-type** the items from the embedded prompt.
- [ ] Bottom navigation includes a clearly labeled link/button back to Home.

### Global
- [ ] Pages link to each other (reciprocal navigation) and all links function.
- [ ] Audio links/players load and play in modern desktop browsers.

### Scope Control
- [ ] The delivered site matches this scope; any changes beyond this spec have documented rationale and do **not** add new pages or features beyond the acceptance criteria.

---
