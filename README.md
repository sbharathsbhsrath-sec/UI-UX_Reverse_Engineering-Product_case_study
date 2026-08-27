# 🎨 AI UI Prompt Engineering & UX Architecture Masterclass: Case Study

> **A comprehensive practical case study documenting the transformation of vague client prompts into production-grade, accessible UI components using design system tokens and usability heuristics.**

---

## 📌 Workshop Overview

* **Event Title:** UI Reverse Engineering - Break It To Build It Better
* **Format:** Hands-On Live Interactive Workshop
* **Core Objective:** Demystify generative AI UI tools (such as Google Stitch and AI frontend assistants) by demonstrating that visual output quality is directly constrained by the precision of technical design vocabulary.
* **Focus Domain:** E-Commerce & SaaS User Experience (5-Core Flow Pages: Home Landing, Collection Filter, Product Details, Checkout, and Order Confirmation).

---

## 🛠️ How the Workshop Was Conducted

The session was structured around a live **"Before vs. After" iterative auditing methodology**:

1. **The Flawed Prompt Baseline:** The presenter issued a typical "naive" or vague prompt (representing common user/client behavior) to the AI engine.
2. **Visual & Structural UX Audit:** The generated output was evaluated live against **WCAG 2.1 Accessibility Guidelines**, **Nielsen’s 10 Usability Heuristics**, and **Core Web Vitals**.
3. **Prompt Iteration & Technical Engineering:** The prompt was rewritten by injecting explicit design tokens, layout grids (8pt spacing system), color contrast rules, and behavioral states.
4. **Final Verification:** The corrected output was generated and analyzed to verify high-converting, production-ready compliance.

---

## 📂 Repository Structure

This repository serves as the complete documentation archive for the workshop artifacts:

```text
├── assets/                  # High-resolution screenshots of UI prompt iterations
│   ├── page-1-hero/         # Naive vs. Corrected Hero Section
│   ├── page-2-collection/   # Filtering & Grid Layouts
│   ├── page-3-product/      # Detail View & Variant Selectors
│   ├── page-4-checkout/     # Progressive Disclosure & Payment Forms
│   └── page-5-confirmation/ # Post-Purchase Hub & Peak-End UX
├── prompts/                 # Raw markdown prompt files for all 5 pages
│   ├── naive-prompts.md     # Baseline unconstrained inputs
│   └── engineered-prompts.md# Production-grade technical prompts
└── README.md                # Comprehensive workshop case study & documentation