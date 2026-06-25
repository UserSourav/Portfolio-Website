
# Sourav Singh — Portfolio Website

> Personal portfolio of **Sourav Singh**, CS Engineering student at SRM IST specialising in Cloud Computing, graduating 2027.

**Live Site:** [souravsingh-portfolio.vercel.app](https://souravsingh-portfolio.vercel.app)

---

## Overview

A fully responsive, single-page portfolio built with pure **HTML, CSS, and vanilla JavaScript** — no frameworks, no build tools. It features a custom animated cursor, a typewriter terminal widget, an orbiting tech-stack visualiser, scroll-reveal animations, and a seamless skills marquee.

---

## Features

- **Custom cursor** — dual-layer cursor with lerp-smoothed ring that scales on hover
- **Animated terminal** — typewriter effect simulating a real dev session (`whoami`, `cat skills.json`, `git log`, etc.)
- **Orbiting tech stack** — two concentric rings of tech icons that counter-rotate around a centre card
- **Skills marquee** — infinite-loop horizontal ticker of technology icons
- **Scroll-reveal animations** — `IntersectionObserver`-powered fade-and-slide entrances
- **Project cards** — spinning gradient border on hover, linking to live demos
- **Certifications section** — cards for NPTEL NLP (IIT Kharagpur) and Fortinet Cybersecurity
- **Fully responsive** — fluid layout that works across desktop and mobile

---

## Tech Stack

| Layer      | Technology                          |
|------------|-------------------------------------|
| Markup     | HTML5                               |
| Styling    | CSS3 (custom properties, Grid, Flexbox) |
| Scripting  | Vanilla JavaScript (ES6+)           |
| Fonts      | Google Fonts — Instrument Serif, DM Sans, Space Mono |
| Icons      | Boxicons, Devicons (CDN)            |
| Hosting    | Vercel                              |

---

## Projects Showcased

| # | Project | Description | Stack |
|---|---------|-------------|-------|
| 01 | [DevTrace](https://devtrace-web-two.vercel.app/) | Auto-formats commits, syncs Jira tickets, and provides a unified terminal interface | Full Stack |
| 02 | [V-Image](https://img-classifieer.vercel.app/) | CNN-based image classifier running entirely in the browser via WebGL | ML · Browser-Side |
| 03 | [Automata Password](https://automata-passkey.vercel.app/) | DFA password strength checker with animated state transitions and entropy scoring | Theory of Computation · UI |

---

## File Structure

```
Portfolio-Website/
├── index.html      # Single-page app — all sections (Hero, About, Skills, Work, Certs, Contact)
├── style.css       # All styling — layout, animations, dark theme, responsive breakpoints
└── README.md
```

---

## Getting Started

No dependencies or build steps required.

```bash
# Clone the repository
git clone https://github.com/UserSourav/Portfolio-Website.git

# Open in browser
cd Portfolio-Website
open index.html
```

Or simply drag `index.html` into any modern browser.

---

## Sections

| Section | Description |
|---------|-------------|
| **Hero** | Name, tagline, CTA buttons, and the animated terminal widget |
| **Skills** | Infinite marquee of tech icons |
| **About** | Brief bio, tech description, and the orbiting tech-stack widget |
| **Work** | Three featured projects with live links |
| **Certifications** | NPTEL NLP and Fortinet Cybersecurity credentials |
| **Contact** | LinkedIn, GitHub, email, and resume download links |

---

## Contact

| Platform | Link |
|----------|------|
| LinkedIn | [linkedin.com/in/usersourav](https://www.linkedin.com/in/usersourav) |
| GitHub   | [github.com/UserSourav](https://github.com/UserSourav) |
| Email    | ss6015@srmist.edu.in |

---

## License

This project is open source. Feel free to use it as inspiration for your own portfolio — a credit or star is always appreciated!
