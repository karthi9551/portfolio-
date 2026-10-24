# Karthikeyan V — Personal Portfolio Website

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Site-EAAA00?style=for-the-badge&logo=google-chrome&logoColor=3A0F34)](https://your-username.github.io/portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-DDE3E8?style=for-the-badge)](LICENSE)
[![Built With: Vanilla Web Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20Tailwind%20%7C%20GSAP-3A0F34?style=for-the-badge)](https://developer.mozilla.org/)

An award-style, editorial personal portfolio website engineered for **Karthikeyan V**, Python Developer & AI Systems Engineer. Built with vanilla web standards, smooth momentum scrolling, dynamic physics-based cursor interactions, and a strict bespoke color system.

---

## 🎨 Color System & Visual Identity

The design adheres strictly to a high-contrast editorial palette ensuring WCAG AA compliance across both Aubergine (default dark) and Ice Silver (light) modes:

* **Deep Aubergine (`#3A0F34`):** Primary canvas, rich background depth, and frosted card overlays.
* **Ice Silver (`#DDE3E8`):** Editorial typography, high-legibility surfaces, and fine border line-work.
* **Marigold (`#EAAA00`):** Accent reserved exclusively for CTAs, active indicators, timeline nodes, and key metrics.

---

## ✨ Signature Features & Interactions

* **Architectural Hero Portrait:** Custom arch-framed headshot with offset Marigold line geometry, 3D mouse perspective parallax, and an animated rotating status badge (*"• OPEN TO WORK • FULL STACK & AI •"*).
* **Kinetic Typography & Marquee:** Scroll velocity-aware infinite marquees highlighting core technical domains.
* **Case Study Panels:** In-depth technical breakdowns for primary projects featuring metrics, stack tags, and simulated live terminal/telemetry logs.
* **Vertical Circuit Timeline:** Interactive internship timeline with dynamic marker glowing as you scroll.
* **Custom Magnetic Cursor:** Trailing lerp follower that scales and tracks interactive elements (auto-disabled on touch devices).
* **Smooth Inertia Scrolling:** Integrated [Lenis](https://github.com/darkroomengineering/lenis) engine paired with GSAP ScrollTrigger animations.
* **Micro-Interactions:** 1-click clipboard copy with animated toast notifications, client-validated contact console, and a keyboard Easter egg (`[K]`).

---

## 🛠️ Tech Stack

* **Markup & Structure:** HTML5 (Semantic, SEO meta tags, JSON-LD Person schema)
* **Styling:** [Tailwind CSS Play CDN](https://tailwindcss.com/) + Custom CSS variables
* **Animation Engine:** [GSAP 3.12](https://greensock.com/gsap/) & [ScrollTrigger](https://greensock.com/scrolltrigger/)
* **Smooth Scrolling:** [Lenis](https://github.com/darkroomengineering/lenis)
* **Typography:** Syne (Headings), Plus Jakarta Sans (Body), JetBrains Mono (Code/Telemetry)

---

## 📂 Project Structure

```text
karthikeyan-portfolio/
│
├── index.html                               # Core portfolio source code
├── resume.pdf                               # Downloadable resume document
├── watermarked_img_8961928524761646952.png  # Executive suit headshot
└── README.md                                # Repository documentations
