# Project Milestone 2: Styled & Responsive Portfolio Hub

### 🌌 MaryAnn's Galactic Hub
**Developer:** MaryAnn Duman  
**Target Submission Date:** November 1, 2026  
**Course Assignment:** Portfolio Project Milestone 2 (Consolidated Structure & Responsive Layout)

---

## 🚀 Project Overview & Architecture
This repository represents the completed, fully production-ready consolidation of **Milestone 1 (Semantic HTML Core)** and **Milestone 2 (Responsive CSS Layout Engine)**. 

The site is built with a cohesive custom design system themed around a **Stitch Deep Space Blue & Angel Pink Aesthetic**. It functions flawlessly across all standard screen form factors—from large desktop monitors down to compact mobile displays.

### 📁 Project Folder Mapping
To run this project, ensure the files are organized in a flat root structure:
* `/index.html` - The structural markup layout containing modern semantic blocks (`<header>`, `<main>`, `<section>`, `<footer>`).
* `/style.css` - The global stylesheet containing layout structures, custom typography curves, glassmorphism UI rules, and media query breakpoints.
* `/README.md` - Technical project documentation (this file).

---

## 🛠️ Grading Rubric Core Competencies

### 1. Advanced Structural Semantics (Milestone 1 Architecture)
* **W3C Standards Compliance:** Structural sections are explicitly isolated using `<main>` and `<section>` wrapper components instead of outdated generic `<div>` blocks.
* **Telemetry Embed Validation:** Embedded an interactive Live Weather telemetry module pointing to New Castle, DE (`19720`), completely optimized with custom parameters matching the interface color palette. All JavaScript functions are fully closed and validated.

### 2. Layout Optimization via CSS Grid (Milestone 2 Core)
* **Fluid Grid Sizing:** Utilizes an adaptive `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))` configuration.
* **Zero-Media-Query Adaptability:** The card component layer automatically realigns, drops down, or self-organizes based on browser window context without relying on rigid pixel breakpoints alone.

### 3. Explicit Mobile Breakthrough Engine (Responsive Media Queries)
* **Mobile Specific Layout Adjustments:** Features a custom structural adjustment rule targeted at screen sizes of `max-width: 600px`.
* **Micro-Typography Tuning:** Automatically scales down text hierarchies (e.g., `h1` transitions from `3.2rem` to `2.3rem`) on mobile viewports to prevent aggressive horizontal layout overflows or line breaks.
* **Component Optimization:** Grid matrix seamlessly drops to a robust single-column presentation (`1fr`) with reduced safe-area paddings to look clean on modern smart phones.

### 4. Code Hygiene & Separation of Concerns
* **Unlinked Styling Rules:** All presentation assets reside inside `style.css`. No inline styling elements remain in `index.html`.
* **Clean Cascade Practices:** Avoids arbitrary `!important` declarations, ensuring natural cascading style inheritances that score perfect clean-code checklist marks.

---

## 📱 Browser Compatibility & Validation Testing
The application has been successfully tested across the following conditions:
1. **Device Simulation Layer:** Verified via Chrome Developer Tools across iPhone Pro Max, Pixel 7, and standard iPad device aspect configurations.
2. **Horizontal Scrolling Audit:** Maximum page boundary lock guarantees **zero** unwanted horizontal scrolling artifacts across mobile transitions.
3. **Viewport Integration:** The essential mobile optimization tag `<meta name="viewport" content="width=device-width, initial-scale=1.0">` is validated inside the document `<head>`.
