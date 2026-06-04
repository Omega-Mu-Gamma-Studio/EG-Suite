# EG Suite

> **An interactive 3D learning platform for Engineering Graphics.**  
> Built for the ME22201 syllabus · Live at [eg-suite.vercel.app](https://eg-suite.vercel.app)

[![Live Demo](https://img.shields.io/badge/Live%20Demo-eg--suite.vercel.app-5b8ff7?style=for-the-badge&logo=vercel&logoColor=white)](https://eg-suite.vercel.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-4fc97e?style=for-the-badge)](./LICENSE)

---

## What is this?

EG Suite is a browser-based 3D simulator that brings Engineering Graphics concepts to life. Instead of staring at static textbook diagrams trying to mentally rotate solids and imagine cutting planes, you interact with the actual geometry in real time — rotate, cut, unfold, and project, all in the browser.

Built specifically to cover **Units III, IV, and V** of the ME22201 Engineering Graphics syllabus, with WebGL rendering via Three.js. No installation, no backend, runs fully offline once loaded.

---

## What it covers

### Unit III & IV — Projection of Solids, Section & Development

- **Rotating object method** for axis inclination problems
- **Cutting plane** with live section rendering and true shape computation
- **Lateral surface development** with step-by-step unroll animation
- **First-angle orthographic projections** across four views

### Unit V — Isometric Projections & Orthographic Views

- **Isometric, orthographic, and split 4-view** layout modes
- **Angled and frustum cuts** with live geometry updates
- **Construction lines and dimension annotations**
- **PNG export** — save your view directly from the browser

---

## Tech stack

- **Vanilla JavaScript (ES6 Modules)** — no framework, no bundler
- **Three.js** — WebGL-powered 3D rendering and orbit controls
- **Custom geometry pipeline** — cutting planes, true shape rabatment, polygon triangulation for cut faces
- **Vercel** — hosting and deployment

---

## Project structure

```
EG-Suite/
├── index.html          — entry point and layout shell
├── common/             — shared utilities, camera setup, scene management
├── unit3-4/            — solid projection, section, and development modules
└── unit5/              — isometric and orthographic view modules
```

---

## Running locally

```bash
git clone https://github.com/Omega-Mu-Gamma-Studio/EG-Suite.git
cd EG-Suite
# Open index.html in your browser — or serve locally:
npx serve .
# or
python -m http.server 8080
```

---

## Background

EG Suite was built as a practical learning tool during the Engineering Graphics course (ME22201). The goal was simple — make the hard parts of the syllabus actually visual and interactive rather than abstract. The 3D cutting plane logic, true shape mathematics, and unroll animations were all implemented from scratch without relying on geometry libraries.

---

## Faculty Mentor

**Dr. M Anjan Augustine**  
Department of Mechanical Engineering  
*Faculty mentor for the Engineering Graphics course (ME22201)*

---

## License

[MIT](./LICENSE) — free to use, study, modify, and share.

---

*Built by [@albertofelix08](https://github.com/albertofelix08) & [@aaronmcgeo](https://github.com/aaronmcgeo) · CSE-A(I) · Omega Mu Gamma Studio*
