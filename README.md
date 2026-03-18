# Owais Taha — Portfolio Website

A modern, interactive personal portfolio website for **Owais Taha**, a Flutter & Mobile Full-Stack Developer with 5+ years of experience. The portfolio is a self-contained single HTML file featuring 3D animations, custom cursor effects, and scroll-triggered interactions.

---

## 🚀 Live Demo

Deploy the `index.html` file to any static hosting provider to go live instantly (see [Deployment](#deployment)).

---

## ✨ Features

- **Animated Hero Section** — Custom cursor, Three.js particle canvas background, and glowing orbs
- **About** — Professional bio with key stats (50K+ active users, 5+ years of experience, MSc in AI)
- **Projects** — 4 featured projects with modal detail views and technology tags
- **Skills** — 12 proficiency-rated technical skills with animated progress bars
- **Experience** — Vertical timeline covering 4 professional roles
- **Contact** — Contact form with email, phone, and social links
- **Advanced Animations** — GSAP scroll triggers, 3D card tilt, magnetic button effects, Intersection Observer reveals

---

## 🛠️ Tech Stack

| Category | Technologies |
|---|---|
| Markup / Style / Logic | HTML5, CSS3, Vanilla JavaScript |
| 3D & Particles | [Three.js r128](https://threejs.org/) |
| Animations | [GSAP 3.12.2](https://greensock.com/gsap/) + ScrollTrigger |
| Fonts | [Google Fonts](https://fonts.google.com/) — Syne, DM Mono, Cabinet Grotesk |
| Build Tools | None — zero build step required |

---

## 📁 Project Structure

```
portfolio_owais/
├── index.html       # Main portfolio (HTML + CSS + JS, all-in-one)
└── portfolio.html   # Alternate copy of index.html
```

---

## 🖥️ Getting Started

### Prerequisites

A modern web browser with JavaScript enabled (Chrome, Firefox, Edge, Safari).

### Run Locally

```bash
# Clone the repository
git clone https://github.com/owaistaha/portfolio_owais.git
cd portfolio_owais

# Open in your browser
open index.html
```

Or serve it with any static server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js (npx)
npx serve .
```

Then open `http://localhost:8080` in your browser.

---

## 🚢 Deployment

Because the project is a single static HTML file, it can be deployed anywhere:

| Platform | Steps |
|---|---|
| **GitHub Pages** | Go to *Settings → Pages*, set source to the `main` branch root |
| **Netlify** | Drag-and-drop the repository folder onto [netlify.com/drop](https://app.netlify.com/drop) |
| **Vercel** | `npx vercel --prod` from the project directory |
| **Any web server** | Upload `index.html` to the server's public directory |

---

## 📂 Featured Projects

| Project | Year | Technologies |
|---|---|---|
| EV Charging & Smart Home Dashboard | 2024 | Flutter, BLoC, RESTful API, IoT |
| Automated CI/CD Mobile Pipeline | 2024 | GitHub Actions, Flutter, Jenkins, Docker |
| Beeducation Adventures Platform | 2023–2025 | Flutter, Firebase, BLoC, iOS/Android |
| Chefs.PK Mobile App | 2021–2022 | Flutter, Firebase, Push Notifications |

---

## 📬 Contact

Full contact details (email, phone, LinkedIn) are available in the **Contact** section of the live portfolio.

| | |
|---|---|
| **GitHub** | [github.com/owaistaha](https://github.com/owaistaha) |

---

## 📄 License

This project is open source. Feel free to use it as a template for your own portfolio — attribution appreciated but not required.
