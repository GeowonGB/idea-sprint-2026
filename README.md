# IEDC Idea Sprint 2026(SUB EXECOM TASK) 🚀

> Official landing page for **IEDC Idea Sprint 2026** — a 24-hour student ideathon hosted by **IEDC BOOTCAMP CEC** (College of Engineering Chengannur) in association with the Kerala Startup Mission (KSUM).

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-brightgreen?style=flat-square&logo=github)](https://geowongb.github.io/idea-sprint-2026/)
[![Performance](https://img.shields.io/badge/Lighthouse%20Performance-96%2F100-success?style=flat-square&logo=googlechrome)](https://geowongb.github.io/idea-sprint-2026/)
[![Accessibility](https://img.shields.io/badge/Lighthouse%20Accessibility-100%2F100-brightgreen?style=flat-square&logo=w3c)](https://geowongb.github.io/idea-sprint-2026/)
[![Best Practices](https://img.shields.io/badge/Lighthouse%20Best%20Practices-100%2F100-brightgreen?style=flat-square)](https://geowongb.github.io/idea-sprint-2026/)
[![SEO](https://img.shields.io/badge/Lighthouse%20SEO-100%2F100-brightgreen?style=flat-square)](https://geowongb.github.io/idea-sprint-2026/)

---

## 🌐 Live Links

- **Live Website:** [https://geowongb.github.io/idea-sprint-2026/](https://geowongb.github.io/idea-sprint-2026/)
- **GitHub Repository:** [https://github.com/GeowonGB/idea-sprint-2026](https://github.com/GeowonGB/idea-sprint-2026)

---

## ✨ Features

- **Dynamic Real-Time Countdown:** Auto-calculates remaining time until the sprint kickoff (28 Nov 2026, 10:00 IST), transitions into a "Live Sprint" countdown during the 24-hour window, and cleanly updates upon conclusion.
- **Kinetic Scroll-Driven Portal:** Smooth scroll animations scaling graphics and sliding portal panels dynamically based on scroll depth.
- **Throwable Starter Prompt Cards:** Touch-friendly, draggable card deck with support for mouse swipe, pointer gestures, and keyboard navigation (<kbd>←</kbd> / <kbd>→</kbd>).
- **Responsive 2-Day Schedule:** Formatted timetable covering Day 1 and Day 2 events, from check-in and mentor sessions to night hacking and final pitches.
- **Accessible Registration Form:** Client-side validation for team details, email format, phone numbers, and team sizing with ARIA live feedback and screen-reader support.
- **Zero Heavy Dependencies:** Built using 100% vanilla HTML5, modern CSS, and lightweight JavaScript with zero bulky frameworks, resulting in sub-second load times.
- **Reduced Motion Support:** Respects user accessibility settings via `@media (prefers-reduced-motion)` to disable jarring animations when requested.

---

## 📊 Lighthouse Mobile Audit Scores

Audited directly on the live production GitHub Pages deployment:

| Category | Score | Result |
| :--- | :---: | :---: |
| **Performance** | **96** | 🟢 Exceptional |
| **Accessibility** | **100** | 🟢 Perfect |
| **Best Practices** | **100** | 🟢 Perfect |
| **SEO** | **100** | 🟢 Perfect |

---

## 🛠️ Tech Stack

- **Markup:** Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<table>`, `<form>`, `<fieldset>`)
- **Styling:** Vanilla CSS3 (CSS Custom Properties, CSS Grid, Flexbox, `clamp()` fluid typography)
- **Typography:** [Sora](https://fonts.google.com/specimen/Sora) (Body) & [Syne](https://fonts.google.com/specimen/Syne) (Headings) via Google Fonts
- **Logic:** Vanilla ES6+ JavaScript
- **Hosting:** GitHub Pages via GitHub Actions CI/CD

---

## 💻 Local Setup & Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GeowonGB/idea-sprint-2026.git
   cd idea-sprint-2026
   ```

2. **Run locally:**
   No build steps or dependencies needed! You can open `index.html` directly in your browser or serve it using any local HTTP server:

   *Using Python:*
   ```bash
   python -m http.server 8000
   ```
   *Using Node (npx):*
   ```bash
   npx serve .
   ```
   *Or with the VS Code **Live Server** extension.*

---

## 🚀 Deployment

The site is configured for continuous deployment using **GitHub Pages**:
- **Source:** Branch `main`
- **Root Directory:** `/` (root)
- Any commit pushed to `main` triggers an automatic rebuild and deploys live in under 60 seconds.

---

## 👥 Credits & Organization

- **Organized by:** [IEDC BOOTCAMP CEC](https://github.com/GeowonGB) (College of Engineering Chengannur)
- **Affiliation:** Kerala Startup Mission (KSUM)
