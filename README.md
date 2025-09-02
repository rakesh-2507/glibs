# GLIBS Beverages Experience

An interactive web experience showcasing **GLIBS beverages**, featuring smooth scroll animations, 3D bottle models, and dark mode.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [3D Model Integration](#3d-model-integration)
- [Scroll Animations & Navigation](#scroll-animations--navigation)
- [Dark Mode](#dark-mode)
- [Test Links](#test-links)
---

## Overview
GLIBS presents a curated selection of beverages through a visually rich, interactive website. Users can:
- Scroll through visually distinct sections.
- View and interact with 3D beverage bottle models.
- Toggle between light and dark themes.
- Navigate sections via fixed side dots.

---

## Features
- **Smooth scroll animations** for content sections.
- **3D GLTF beverage bottle viewer** with orbit controls.
- **Dynamic text animations** synced with scroll.
- **Dark mode toggle** for light/dark themes.
- **Navigation dots** update based on scroll position.
- **Hard refresh on exiting 3D mode**.
- **Responsive layout** for desktop and mobile.

---

## Technologies Used
- HTML5, CSS3, JavaScript (ES6)
- [Three.js](https://threejs.org/) – 3D graphics
- [GSAP](https://greensock.com/gsap/) – Animations
- [Font Awesome](https://fontawesome.com/) – Icons
- Google Fonts – Typography

---

## Project Structure
project-root/
│
├── index.html # Main HTML file
├── models/
│ └── glibs.glb # 3D beverage bottle model
├── assets/
│ └── images/ # Additional images (if any)
├── styles.css # Optional external CSS
├── scripts.js # Optional external JS
└── README.md # Project documentation


---

## Installation
1. Clone the repository:
```bash
git clone (https://github.com/rakesh-2507/glibs.git)
```
---

## Usage

- Scroll down to navigate through three sections:
  1. BEVERAGES BY GLIBS
  2. CRAFTED FOR TASTE
  3. EXPERIENCE ELEGANCE
- Navigation Dots indicate the active section.
- Click View in 3D to explore the 3D beverage bottle interactively.
- Click Exit 3D to refresh the page and return to normal view.
- Toggle Dark Mode using the moon icon in the header.

---

## 3D Model Integration

- 3D beverage bottles are loaded via `THREE.GLTFLoader`.
- OrbitControls enable rotation, zoom, and pan in 3D mode.
- Scroll animations synchronize model position and scale using GSAP.
- 3D text overlay fades in as the user scrolls to the final section.

---

## Scroll Animations & Navigation

- Scroll progress is calculated as a percentage of the page height.
- GSAP interpolates section positions and opacity smoothly.
- Navigation dots update dynamically based on scroll position.

---

## Dark Mode

- Toggle with the moon icon in the header.
- Updates background, text, buttons, and navigation dots dynamically.
- Smooth transitions applied via CSS.

---

## Test Links

- [Home Page](https://rakesh-2507.github.io/glibs/)
- [Test Page 1](https://rakesh-2507.github.io/glibs/test1.html)
- [Test Page 2](https://rakesh-2507.github.io/glibs/test2.html)  
- [Test Page 3](https://rakesh-2507.github.io/glibs/test3.html)  *** This will **refresh the page completely**, so the view returns to the standard scroll-based layout ***
- [Test Page 4](https://rakesh-2507.github.io/glibs/test4.html) 
- [Test Page 3](https://rakesh-2507.github.io/glibs/test5.html)  *** Interactive, scroll-driven 3D product showcase built with Three.js, GSAP and vanilla JS — textured model viewer, texture selectors, dark mode and audio controls ***
