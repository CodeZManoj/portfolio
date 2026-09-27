# Full Stack Developer Portfolio - Manoj Kumar
### ShadowFox Full Stack Developer Internship &bull; Beginner Level Task

![Portfolio Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Tech Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20CSS3%20%7C%20JavaScript-blue?style=for-the-badge)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

---

## 📌 Project Overview
This repository contains the official **Beginner Level Personal Portfolio Website** built for the **ShadowFox Full Stack Developer Internship Track**. Tailored specifically for **Manoj Kumar**, a Computer Science and Engineering undergraduate at Narula Institute of Technology and open-source contributor, this portfolio presents end-to-end full-stack capabilities, academic achievements, core skillsets, and real-world projects.

- **Developer:** Manoj Kumar
- **Role:** Full Stack Developer / Backend Developer
- **Target Internship:** Summer 2026 Full Stack / Backend Developer Intern
- **GitHub:** [github.com/CodeZManoj](https://github.com/CodeZManoj)
- **LinkedIn:** [Manoj Kumar](https://www.linkedin.com/in/manoj-kumar-677b1426a?utm_source=share_via&utm_content=profile&utm_medium=member_android)
- **Email:** [manojkumardav2004@gmail.com](mailto:manojkumardav2004@gmail.com)

---

## 🚀 Key Features

1. **Home / Hero Section:**
   - Bold, eye-catching greeting with active availability status badge (`Seeking Full Stack / Backend Internship`).
   - Dynamic typing animation highlighting multi-faceted expertise (*Full Stack Developer*, *Node.js & Express Specialist*, *RESTful API Engineer*, *Web3 Smart Contract Explorer*).
   - Interactive developer code preview card featuring syntax highlighting.
   - Quick action CTAs (*View Projects*, *Contact Me*) and direct social/GitHub links.

2. **About Section:**
   - Concise summary of engineering mindset, open-source background, and core development philosophy.
   - Highlight stats cards (8.05 CGPA, 4+ Core Projects, Hacktoberfest Contributor, 100 Days of Code).
   - Core domain pillars (Backend & REST APIs, Frontend & Responsive UI, Database Architecture, Open Source & Web3).

3. **Skills & Tools Section:**
   - **Language Competency Progress Bars:** Visualizing relative proficiency across Node.js/Express (85%), JavaScript (80%), Python (80%), MongoDB (75%), C/C++ (70%), and HTML5/CSS3 (90%).
   - **Categorized Tech Cards:** Organized into Languages & Core, Backend & APIs, Frontend & Responsive UI, and Databases & Tools.

4. **Projects Showcase with Live Filtering:**
   - Categorized filter tabs (`All`, `Backend & Full Stack`, `Frontend & APIs`, `Web3 & Smart Contracts`).
   - Real featured projects from resume:
     - **User Management System** (Node.js, Express, MongoDB, REST APIs, CRUD)
     - **Weather Monitoring Dashboard** (Live Weather APIs, JavaScript, Responsive UI)
     - **HalloApp (Web3)** (Solidity Smart Contract decentralized savings pool)
     - **KarmaGap** (Web3 contribution gap resolver)
   - Every card includes preview badges, technology chips, and links to source code / demo.

5. **Education & Certifications Timeline:**
   - Vertical timeline mapping B.Tech at Narula Institute of Technology (8.05 CGPA), Higher Secondary (SKM College), and Secondary Education (Vidya Vikash High School - 91.7%).
   - Achievement cards highlighting official **Hacktoberfest 2025 Contributor** recognition, **100 Days of Code**, **Full Stack Bootcamp**, and **Git & GitHub Essentials**.

6. **Contact Section with Comprehensive Client-Side Form Validation:**
   - Real-time and on-submit input validation for Name, Email, Subject, and Message.
   - Live character counter (0 / 500) for the message textarea.
   - Inline feedback errors, visual green/red state markers, and animated submit button with spinner state.
   - Direct contact channels (Email, Phone, Location, GitHub).

7. **Theme Switcher & Accessibility:**
   - Dark and Light mode toggle with persistent state saved in `localStorage`.
   - Respects user system preference (`prefers-color-scheme`).
   - Mobile off-canvas drawer navigation with backdrop blur and trap handling.
   - Smooth scrolling with scroll-spy highlighting active navigation links.
   - Floating back-to-top button.

---

## 🎨 ShadowFox Evaluation Answers

### 1. Design Choices & Visual Aesthetics
- **Color Palette & Theming:** Utilized a modern cyber-dark palette (`#0b0f19` and `#111827`) paired with vibrant indigo (`#6366f1`) and cyan (`#06b6d4`) gradients. This creates a high-tech developer aesthetic fitting for a full-stack engineer. A complete light theme counterpart is provided using clean slate tones (`#f8fafc`).
- **Typography:** Paired **Outfit** (for headers and brand identity) with **Inter** (for body typography). Outfit conveys modern engineering confidence, while Inter delivers optimal legibility across varying screen sizes and pixel densities.
- **Micro-Interactions:** Subtle floating badge animations, button hover lifts (`translateY`), glowing drop shadows, and progress bar fills engage users without hurting performance or accessibility.

### 2. Layout Decisions & Structure
- **Single Page Application (SPA) Flow:** Designed as a seamless single-page layout where each section flows logically from introduction &rarr; background &rarr; technical capabilities &rarr; project proof &rarr; academic validation &rarr; direct contact.
- **CSS Grid & Flexbox:**
  - CSS Grid is used for multi-dimensional layouts: hero grid, stats cards, skills grid, and project cards.
  - Flexbox is used for one-dimensional alignments: navigation bars, action buttons, filter tags, and footer items.
- **Sticky Glassmorphism Header:** The header stays fixed at the top with a subtle backdrop blur (`backdrop-filter: blur(12px)`), ensuring seamless navigation anywhere on the page without blocking screen content.

### 3. Responsiveness Approach
- **Mobile-First Responsive Design:** Built using responsive CSS units (`rem`, `%`, `clamp()`, `vh/vw`) and media queries at standard device boundaries:
  - **Desktop (>1024px):** 2-column hero, 4-column skill grids, 2-column projects grid, horizontal navigation.
  - **Tablet (768px – 1024px):** Stacked hero with centered code card, 2-column skills and project grids, adjusted padding.
  - **Mobile (<768px):** Desktop navigation converts into a sliding off-canvas mobile drawer accessible via hamburger menu, single-column forms, stacked contact panels, and touch-friendly button targets (minimum 44px).
  - **Small Mobile (<480px):** Single-column stat cards and full-width CTAs.

### 4. Overall Frontend Architecture
The codebase strictly adheres to clean separation of concerns without requiring complex bundling pipelines or heavy node modules:
```
FULL STACK/
├── index.html          # Semantic HTML5 markup, ARIA roles, structured sections
├── css/
│   └── style.css       # Modular CSS with variables, layouts, animations, and media queries
├── js/
│   └── main.js         # Interactivity, typing effect, mobile nav, theme toggle & validation
└── README.md           # Project report, rubric documentation & deployment instructions
```



## 📄 License
This project is open-source and created for educational and evaluation purposes under the [MIT License](LICENSE).
