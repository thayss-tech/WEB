<div align="center">
  <h1>Thayss Tech Hub</h1>
  <p><strong>Professional Portfolio & Centralized Architecture</strong></p>

  <p>
    <a href="https://thayss-tech.github.io/WEB/">
      <img src="https://img.shields.io/badge/Website-Live-2ea44f?style=for-the-badge" />
    </a>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  </p>
</div>

---

## 📑 Table of Contents

- [Overview](#overview)
- [Architectural Model](#architectural-model)
- [Core Engine: `assets/`](#core-engine-assets)
- [Content & Validation](#content--validation)
- [Repository Map](#repository-map)
- [Deployment](#deployment)
- [Contact](#contact)

---

## Overview

This repository contains the full source code and infrastructure of my professional website. 

It functions as a **centralized technical hub**, explicitly designed to:
- Present my analytical background in Theoretical Physics.
- Showcase applied Data Science and Machine Learning projects.
- Provide structured, transparent access for technical evaluation.

The development objective for this platform is maximum clarity, performance, and technical transparency without relying on heavy frameworks.

---

## Architectural Model

The website is built on a **Single Page Architecture (SPA-style static model)**. 

    User Request → index.html → assets/ (logic + style) → media & certificates

The structure prioritizes:
- **Performance:** Lightweight loading with zero backend dependency.
- **Maintainability:** Clear separation of concerns (HTML for structure, SASS/CSS for design, Vanilla JS for interaction).
- **Full Control:** Direct manipulation of the frontend stack.

---

## Core Engine: `assets/`

The `assets/` directory acts as the operational core of the platform, divided logically into four subsystems:

### 1. `css/` & `sass/` — Visual Engineering
Controls the entire visual identity, built using SASS for modularity.
- `main.scss` compiles into `main.css`, managing layout, typography, and responsive behavior.
- SASS implementation allows for scalable variable management and modular component design.
- Includes `noscript.css` as a fallback design for environments with disabled JavaScript.

### 2. `js/` — Interaction Layer
Manages dynamic behavior and viewport responsiveness.
- `main.js`: Core logic for smooth scrolling, animations, and interaction.
- `breakpoints.min.js`: Real-time responsive behavior controller.
- Supported by utility libraries to ensure cross-browser compatibility.

### 3. `webfonts/` — Icon Infrastructure
Locally hosted FontAwesome libraries (.woff, .woff2, .ttf, .svg) guaranteeing independent icon rendering across all browsers (Chrome, Safari, Firefox, Edge) and legacy systems.

---

## Content & Validation

Beyond the core engine, the repository is structured to hold professional assets:

- **`images/`**: Contains visual assets, including tool icons (n8n, GCP), technical stack representations, and structural layouts.
- **`certificates/`**: Hosts documentation validating technical expertise, acting as professional anchors (e.g., Google Cloud Platform and Machine Learning with Python certifications).

---

## Repository Map

    WEB/
     ┣ index.html          # Structural Core (Main Document)
     ┣ assets/             # Technical Engine
     ┃ ┣ css/              # Compiled Styles
     ┃ ┣ js/               # Interaction Logic
     ┃ ┣ sass/             # Source Styling
     ┃ ┗ webfonts/         # Typography & Icons
     ┣ images/             # Visual Assets
     ┣ certificates/       # Professional Validation
     ┣ LICENSE
     ┗ README.md           # Project Documentation

---

## Deployment

The platform is deployed via **GitHub Pages**, ensuring high availability, continuous static reliability, and fast global loading.

📍 **Live version:** [https://thayss-tech.github.io/WEB/](https://thayss-tech.github.io/WEB/)

---

## Contact

- **GitHub:** [thayss-tech](https://github.com/thayss-tech)
- **LinkedIn:** [Milton Mamani](https://www.linkedin.com/in/milton-mamani-1369a537b)

> *Designed as a structured technical gateway for data-driven environments.*
