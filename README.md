# 🚀 Gymini AI - Official Landing Page

This repository contains the source code for the official landing page of **Gymini AI**, the hyper-intelligent, offline-first personal training mobile application.

## 🏗️ Architecture & Tech Stack
This landing page is designed to be lightweight, blindingly fast, and heavily visual. It requires zero build steps or heavy frameworks.

* **HTML5:** Pure, semantic markup.
* **Tailwind CSS (CDN):** Utility-first styling for rapid UI development and custom dark-mode ("Ink & Ember" theme).
* **WebGL & Three.js:** Powering the dynamic background shaders and the interactive 3D floating barbell element.
* **Vanilla JavaScript:** Handling the `IntersectionObserver` scroll animations ("stagger-in" waterfall effect).

## 🚀 Deployment
This static site is optimized to be deployed instantly on any static hosting provider (Vercel, Netlify, or GitHub Pages).

1. Drop the `index.html` and `screenshot.png` into your host.
2. The site will automatically fetch Tailwind and WebGL scripts via CDN.
3. The APK download links point directly to the main Gymini application's GitHub Releases page.
