# 🚀 Ujwal Akare — Personal Portfolio

> **Live Site:** [ujwalakare.github.io](https://ujwalakare.github.io) *(update once deployed)*  
> Lead Software Engineer & DevOps Specialist at Persistent Systems, Pune, India.

---

## ✨ Overview

A world-class, single-file personal portfolio website built with pure **HTML, CSS, and Vanilla JavaScript** — no frameworks, no build tools, zero dependencies beyond Google Fonts. Designed with a dark cyberpunk-meets-enterprise aesthetic featuring deep space navy, electric cyan, and warm gold accents.

---

## 🎨 Features

### Visual & Animations
- 🌌 **Particle constellation canvas** — animated star network on the hero with mouse-repulsion effect
- ✍️ **Typing animation** — cycles through roles in a terminal-style display
- 🖱️ **Custom glowing cursor** — cyan dot that turns gold on hoverable elements
- 💎 **Glassmorphism cards** — frosted glass surfaces with neon border glow on hover
- 🃏 **3D tilt effect** — vanilla JS perspective tilt on certification cards
- ✨ **Shimmer sweep** — animated light sweep on cert and award cards
- 🎬 **Cinematic page load** — staggered fade-in reveal on scroll via Intersection Observer
- 🌊 **Smooth scrolling** — section reveal animations throughout

### Sections
| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Full-viewport with particle BG, typing animation, CTA buttons |
| 2 | **About** | Bio, rotating avatar monogram, 4 quick-stat cards |
| 3 | **Skills** | Grouped skill tags with hover tooltips showing experience context |
| 4 | **Experience** | Animated timeline — Persistent Systems / IBM projects with accordion cards |
| 5 | **Certifications** | 3D-tilt cert cards with shimmer effect; "In Progress" badges |
| 6 | **Achievements** | Gold-shimmer award cards — Bravo Awards + IBM appreciation |
| 7 | **Contact** | Click-to-copy email & phone, social links, "Open to opportunities" badge |

### Interactive
- 📋 **Copy tech stack** button on each project card
- 📧 **Click-to-copy** contact details (email, phone)
- 🔽 **Accordion projects** — expand/collapse with smooth animation
- 📥 **Resume download** — direct link to `Ujwal_Akare_CV.pdf`
- 👨‍💻 **Console easter egg** — DevOps-themed ASCII art for fellow developers (open DevTools!)

---

## 🗂️ Project Structure

```
ujwalakare.github.io/
├── index.html          # Entire portfolio (HTML + CSS + JS — single file)
└── Ujwal_Akare_CV.pdf  # Resume file linked for download
```

That's it. Two files. Ship it.

---

## 🛠️ Tech Stack

| Layer | Choice |
|-------|--------|
| Markup | Semantic HTML5 |
| Styling | Pure CSS3 (custom properties, grid, flexbox, keyframes) |
| Scripting | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Syne, DM Sans, JetBrains Mono |
| Icons | Unicode / SVG inline |
| Animation | CSS keyframes + Intersection Observer API + Canvas API |
| Build | None — open `index.html` and go |

---

## 🚀 Deploying to GitHub Pages

### Step 1 — Create the repository

```bash
# Option A: Repo named after your GitHub username → site at https://ujwalakare.github.io
Repository name: ujwalakare.github.io

# Option B: Any other repo name → site at https://ujwalakare.github.io/<repo-name>
Repository name: portfolio  (→ ujwalakare.github.io/portfolio)
```

### Step 2 — Upload files

```bash
git init
git add index.html Ujwal_Akare_CV.pdf
git commit -m "feat: launch portfolio"
git branch -M main
git remote add origin https://github.com/ujwalakare/ujwalakare.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Click **Save**
5. ✅ Live in ~2 minutes at `https://ujwalakare.github.io`

---

## 🔧 Customization Guide

### Update contact details
Open `index.html` and search for the contact section. All personal details are in plain HTML — no config files needed.

### Swap the resume
Replace `Ujwal_Akare_CV.pdf` with your updated resume. Keep the same filename, or update the two `href` references in the HTML:
```html
href="Ujwal_Akare_CV.pdf"
```

### Change color theme
All colors are CSS custom properties at the top of the `<style>` block:
```css
:root {
  --cyan: #00D4FF;   /* primary accent */
  --gold: #FFB347;   /* secondary accent */
  --bg:   #050A14;   /* background */
}
```

### Add a new skill tag
Find the relevant `.skill-group` and add:
```html
<span class="skill-tag" data-tip="Your tooltip text here">SkillName</span>
```

### Add a new certification
Copy an existing `.cert-card` block and update the icon, name, issuer, and date fields.

---

## 🎯 Performance Notes

- **Zero JS frameworks** — no React, Vue, Angular, or jQuery
- **No build step** — works as a raw static file
- **Single HTTP request** for the page itself (fonts load via CDN)
- **Canvas animation** is requestAnimationFrame-based, targeting 60fps
- **Particle count** auto-scales: 50 particles on mobile, 100 on desktop

---

## 📸 Sections Preview

```
┌─────────────────────────────────┐
│  [UA]  About Skills Exp Certs   │  ← Fixed navbar with blur backdrop
├─────────────────────────────────┤
│                                 │
│   ✦ · ✦ · · ✦ · · ✦ · ✦ · ✦  │  ← Particle constellation
│                                 │
│      Hey, I'm                   │
│   UJWAL AKARE                   │  ← Glowing gradient heading
│   > Lead Software Engineer_     │  ← Typing animation
│                                 │
│   [View My Work] [Download CV]  │
│                          3.8+   │
│                      Years Exp  │  ← Floating badge
└─────────────────────────────────┘
```

---

## 🪲 Easter Egg

Open your browser's **DevTools Console** (`F12` → Console tab) to find a DevOps-themed ASCII art message hidden for fellow engineers 👀

---

## 📄 License

This portfolio and its content belong to **Ujwal Akare**. Feel free to use the code structure as inspiration for your own portfolio — just swap out the personal details!

---

<div align="center">

**Built with precision by [Ujwal Akare](https://linkedin.com/in/ujwal-akare)**  
Persistent Systems · Pune, India · 2025

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ujwal--akare-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/ujwal-akare)
[![GitHub](https://img.shields.io/badge/GitHub-ujwalakare-181717?style=flat&logo=github)](https://github.com/ujwalakare)

</div>
