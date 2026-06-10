# DecodeLabs - Project 2: Adaptability Phase (Responsive Web Layout)

An industry-grade, fully responsive landing page built as part of the Frontend Development training at DecodeLabs. This project serves as a foundational milestone in mastering fluid web architectures, cross-device compatibility, and modern layouts without relying on any external CSS frameworks or JavaScript.

## 🚀 Live Demo
You can view the live deployment of this project here: 
👉 **[https://github.com/pkyadav-png/DecodeLabs-Internship-Project-2 / Live Link Here]**

---

## 🎯 Project Overview & Objective
The core goal of this project is to implement **The Art of Fluidity**—ensuring content behaves like water, perfectly adapting to whatever screen size or container it is placed into. 

Following the training kit guidelines, the project avoids hardcoded pixel dimensions and focuses entirely on true responsive design, delivering an optimized user experience across smartphones, tablets, and high-resolution desktop monitors.

---

## ✨ Key Features Implemented

* 📱 **Mobile-First Architecture:** Developed the core base CSS for mobile layouts first (0px - 480px) and scaled upwards using progressive enhancement.
* 🍔 **Pure CSS Navigation Toggle (No JS):** Implemented an interactive smartphone navigation drawer using the highly efficient **CSS Checkbox Hack** (`:checked` state and sibling selectors).
* 🔄 **Adaptive Hamburger Animation:** Seamless pure CSS transitions that morph the mobile 3-line hamburger icon into an elegant close (`X`) graphic upon user interaction.
* 📐 **System Breakpoints:** Strategic viewport triggers configured precisely to maintain content integrity:
    * `0px - 480px`: Mobile Core Layout initialization.
    * `768px`: Tablet Enhancement activation (Dual-column wrapping configurations).
    * `1024px+`: Desktop High-Res optimization (Multi-column spatial management).
* 🧱 **Flexbox Alignment Specialist:** Leveraged one-dimensional alignment structures (`flex-direction`, `justify-content`, `align-items`) to dynamically alter layout directions from columns on mobile to horizontal rows on desktop.
* 🚫 **Zero Overflow Errors:** Enforced strict boundaries using universal sizing resets (`box-sizing: border-box`) and robust viewport boundary rules (`overflow-x: hidden`) to prevent horizontal scroll breakages.

---

## 🛠️ Technologies & Concepts Used

* **HTML5:** Semantic architecture elements (`<header>`, `<section>`, `<nav>`, `<footer>`) ensuring rich document outline parameters.
* **CSS3 (Custom Properties):** Deep semantic theme styling utilizing global CSS Variables (`:root`) for maintainable primary accents and dark slate typography.
* **Viewport Metaphor Tag:** Embedded specialized scalable configurations (`width=device-width, initial-scale=1.0`) to handle precise device rendering scales.
* **Media Queries:** Executed layout variations entirely built around dynamic content breaking points.

---

## 📐 Folder Architecture

```text
├── index.html     # Semantic page structure & layout definitions
└── style.css      # Core CSS rules, CSS Variables, and responsive Media Queries
