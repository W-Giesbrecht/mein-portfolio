# Waldemar Giesbrecht | Frontend Developer Portfolio

This is my professional portfolio—a digital business card designed to showcase my projects, technical skills, and my journey as a Frontend Developer.

## 🚀 Live Demo
- **Custom Domain:** [waldemar-giesbrecht.de](https://waldemar-giesbrecht.de)
- **GitHub Preview:** [blitzbombong.github.io/mein-portfolio/](https://blitzbombong.github.io/mein-portfolio/)

---

## 🛠 Tech Stack
- **Core:** HTML5, CSS3, JavaScript (ES6+)
- **Libraries:** [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) – integrated locally to ensure high performance and GDPR compliance.
- **Documentation:** JSDoc (Industry standard for maintainable and readable code).

---

## ✨ Key Features
- **Multilingual Support (i18n):** Full German and English support using a dynamic JSON-based translation logic.
- **Responsive Design:** A mobile-first approach, ensuring a seamless experience from smartphones to wide-screen desktops.
- **Modular Architecture:** Controlled via JavaScript modules (Import/Export logic) for a highly maintainable codebase.
- **Interactive Contact Form:** A custom-built communication system for direct inquiries.
- **AOS Animations:** Subtle scroll animations to enhance user engagement and visual flow.

---

## 🏗 Project Architecture & Code Quality
A major focus of this project was **scalability**. Instead of a single, massive script, the portfolio is divided into logical components:

```javascript
// Example of my modular component structure
import { getNavSection, getMobileMenu } from "./html/nav.js";
import { getHeroSection } from "./html/hero.js";
import { getAboutSection } from "./html/about.js";
import { getPortfolioSection } from "./html/portfolio.js";
import { initContactForm } from "./js/form.js";