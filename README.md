# ⚡ Arnav Verma — Developer Portfolio

[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-C6A76B?style=for-the-badge&logo=github)](https://arnav2306.github.io/arnav-portfolio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arnav%20Verma-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/arnav-verma-9b0aa0356/)
[![Email](https://img.shields.io/badge/Email-arnav03784%40gmail.com-EA4335?style=for-the-badge&logo=gmail)](mailto:arnav03784@gmail.com)

> **Live Portfolio:** [https://arnav2306.github.io/arnav-portfolio/](https://arnav2306.github.io/arnav-portfolio/)

A modern, high-performance, recruiter-ready developer portfolio engineered with **zero external framework bloat**. Designed to showcase practical software engineering skills, computer science fundamentals, multimodal AI projects, and verified credentials in an elegant **Black & Champagne Gold** aesthetic.

---

## 🌟 Highlights & Features

- **🎨 Champagne Gold & Obsidian Design System**
  - Custom design tokens for smooth dark/light transitions.
  - Subtle radial ambient background glow and modern typography ([Outfit](https://fonts.google.com/specimen/Outfit) + [Inter](https://fonts.google.com/specimen/Inter)).
- **🌓 Accessible Dark & Light Modes**
  - Seamless toggle with persistent user preference stored in `localStorage`.
  - Dynamic `meta[name="theme-color"]` update for mobile status bars.
- **⚡ Zero-Bloat & Pure Performance**
  - Built with pure semantic **HTML5**, **Vanilla CSS3**, and **Vanilla ES6+ JavaScript**.
  - No bundlers, heavy npm dependencies, or runtime overhead — instant first contentful paint (FCP) and near-perfect Lighthouse scores.
- **🔍 Interactive Project Filtering**
  - Instant client-side categorization (All, AI & Full-Stack, Algorithms, Frontend) without layout shift.
- **🖼️ Certificate Lightbox Gallery**
  - Modal lightbox viewer with keyboard navigation (`Left`, `Right`, `Escape`), touch-friendly targets, and counter indicators.
- **📋 One-Click Email Copy & Mailto Integration**
  - One-click clipboard copy utility with animated feedback and fallback support.
- **📱 Fully Responsive & Accessible**
  - Mobile slide-out navigation menu with ARIA accessibility tags.
  - Fluid typography, dynamic scroll progress indicator, and scroll-spy active link tracking.

---

## 📂 Project Structure

```text
arnav-portfolio/
│
├── assets/
│   └── certificates/
│       ├── cert-cpp-udemy.png            # Beginning C++ Programming (Udemy)
│       ├── cert-developer-catalyst.png   # Developer Catalyst Program (Silver)
│       └── cert-sih-medicaps.png         # Smart India Hackathon 2026 (Medicaps)
│
├── index.html                            # Core single-page portfolio application
└── README.md                             # Repository documentation
```

---

## 🛠️ Tech Stack & Architecture

| Layer | Technologies |
|---|---|
| **Structure** | Semantic HTML5, accessible ARIA roles & landmarks |
| **Styling** | Vanilla CSS3, CSS Custom Properties (CSS variables), Flexbox, CSS Grid |
| **Typography** | Google Fonts (`Outfit` for headings, `Inter` for body) |
| **Interactivity** | Vanilla JavaScript (ES6+), IntersectionObserver API, Clipboard API |
| **Hosting & CI/CD** | GitHub Pages |

---

## 🚀 Featured Projects Highlighted in Portfolio

1. **[Reunite — Campus Lost & Found Platform](https://github.com/Arnav2306/reunite)**
   - AI-driven campus recovery web application connecting students with lost items across campus stations.
   - Integrated **Google Gemini Vision AI** for automated item image identification, attribute extraction, deterministic matching, and OTP custody handover.
   - **Stack:** React 18, TypeScript, Tailwind CSS, Python / Django REST Framework, Vercel & Render.
   - **Demo:** [reunite-nine.vercel.app](https://reunite-nine.vercel.app/)

2. **[SehatSetu — AI Healthcare & Appointment Platform](https://github.com/Arnav2306/SehatSetu)**
   - AI-powered healthcare discovery and appointment platform that helps users explore doctors and hospitals, receive symptom-based specialty recommendations, and manage appointments through a bilingual interface.
   - Features AI-powered symptom guidance chatbot, English/Hindi language switching, hospital & doctor discovery, and booking management.
   - **Stack:** React, Vite, Tailwind CSS, Node.js, Express.js, MongoDB, AI API Integration.

3. **[DSA Sorting Visualizer](https://github.com/Arnav2306/sorting-algorithm-visualizer)**
   - Interactive algorithm animation tool demonstrating Bubble Sort, Selection Sort, and Insertion Sort.
   - Dynamic array sizing, adjustable execution speed, and live comparison/swap metrics.
   - **Stack:** Pure JavaScript (Async/Await), DOM API, HTML5, CSS3.

4. **[Personal Portfolio Website](https://github.com/Arnav2306/arnav-portfolio)**
   - High-performance, accessible, recruiter-ready developer portfolio.
   - **Stack:** Semantic HTML5, CSS Design System, Vanilla JavaScript.

---

## 💻 Local Development Setup

No node_modules or build steps required! You can run this project locally in seconds:

### Option 1: Directly Open in Browser
Simply clone the repository and double-click `index.html`:
```bash
git clone https://github.com/Arnav2306/arnav-portfolio.git
cd arnav-portfolio
# Open index.html in your default web browser
```

### Option 2: Using VS Code Live Server
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Click **"Go Live"** in the bottom status bar, or right-click `index.html` and choose **"Open with Live Server"**.

### Option 3: Using a Lightweight Local Server
Using Python:
```bash
# Python 3
python -m http.server 3000
```
Or using Node `serve` / `npx`:
```bash
npx serve .
```
Then open `http://localhost:3000` in your web browser.

---

## 🌐 Deployment to GitHub Pages

This portfolio is configured for deployment via **GitHub Pages**:

1. Push your changes to the `main` branch:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push origin main
   ```
2. In your repository on GitHub:
   - Navigate to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch: `main` and folder: `/ (root)`.
   - Click **Save**.
3. Your portfolio will be live at `https://<username>.github.io/<repository-name>/`.

---

## 📬 Contact & Connect

**Arnav Verma**  
*Developer · Problem Solver · AI Enthusiast*  
Indore, Madhya Pradesh, India (IST / UTC+5:30)

- 🌐 **Live Portfolio:** [arnav2306.github.io/arnav-portfolio](https://arnav2306.github.io/arnav-portfolio/)
- 💼 **LinkedIn:** [linkedin.com/in/arnav-verma-9b0aa0356](https://www.linkedin.com/in/arnav-verma-9b0aa0356/)
- 💻 **GitHub:** [@Arnav2306](https://github.com/Arnav2306)
- ✉️ **Email:** [arnav03784@gmail.com](mailto:arnav03784@gmail.com)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
