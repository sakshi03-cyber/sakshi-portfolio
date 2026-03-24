# 🌐 Sakshi Mishra — Personal Portfolio Website

> A vibrant, professional single-page portfolio for a Generative AI & LLM Engineer.

---

## ✨ Live Preview

Open `sakshi_portfolio.html` in any modern browser — no build step, no dependencies, no server required.

---

## 📁 Project Structure

```
portfolio/
├── sakshi_portfolio.html   # Single-file portfolio (HTML + CSS + JS)
└── README.md               # This file
```

Everything lives in one self-contained HTML file — styles, scripts, fonts, and content.

---

## 🎨 Design Highlights

| Feature | Details |
|---|---|
| **Color Palette** | Electric cyan `#00f5d4`, violet `#b060ff`, gold `#ffc947`, blue `#4ca3ff` |
| **Fonts** | Syne (headings), Instrument Serif (display), IBM Plex Mono (code/labels) |
| **Theme** | Dark — deep navy/black background with vibrant neon accents |
| **Layout** | Fully responsive, mobile-first |

### Animations & Interactions
- 🌌 **Particle network canvas** — animated colored dots with connecting lines across the full background
- 🎯 **Custom cursor** — glowing dot + ring that shifts color on hover
- 🌈 **Gradient animated name** — cycles through cyan → violet → gold
- 📜 **Scroll reveal** — staggered fade-up animations as sections enter the viewport
- 🔮 **Frosted glass nav** — appears with blur effect on scroll
- 💡 **Hover effects** — cards lift, borders illuminate, skill pills brighten

---

## 📑 Sections

1. **Hero** — Name, title, intro, CTA buttons, and key metrics (5+ projects, 1 live internship, 2 certifications)
2. **About** — Bio, career focus, info cards (role, education, contact, soft skills)
3. **Skills** — Three color-coded skill boxes: AI/GenAI · Frameworks & APIs · Languages & Tools
4. **Experience** — AstroMystery.AI internship with live status badge
5. **Projects** — Six projects including featured RAG Chatbot, AI Document Analyzer, Tool-Calling Agent, Customer Support Agent, Automation Platform, Portfolio Website
6. **Education** — BCA at Siddharth Nagar University, CCC & O Level certifications
7. **Contact** — Email link, phone, LinkedIn

---

## 🚀 Projects Featured

| # | Project | Type |
|---|---|---|
| 01 | RAG Chatbot — Intelligent Document Q&A | RAG System |
| 02 | AI Document Analyzer | AI Pipeline |
| 03 | AI Tool-Calling Agent | AI Agent |
| 04 | AI Customer Support Agent | AI Agent |
| 05 | AI Portfolio & Document Automation Platform | Automation |
| 06 | Personal Portfolio Website | Frontend |

---

## 🛠️ Tech Stack (Portfolio itself)

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, keyframe animations, backdrop-filter
- **Vanilla JavaScript** — canvas particle system, custom cursor, scroll reveal via IntersectionObserver
- **Google Fonts** — Syne, Instrument Serif, IBM Plex Mono
- **No frameworks. No build tools. No dependencies.**

---

## 📦 How to Use

### Option 1 — Open Locally
```bash
# Just double-click the file, or:
open sakshi_portfolio.html        # macOS
start sakshi_portfolio.html       # Windows
xdg-open sakshi_portfolio.html    # Linux
```

### Option 2 — Deploy to GitHub Pages
```bash
git init
git add sakshi_portfolio.html README.md
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
# Then enable GitHub Pages in repository Settings → Pages → Deploy from branch: main
```

### Option 3 — Deploy to Netlify (Drag & Drop)
1. Go to [netlify.com](https://netlify.com) → Log in
2. Drag and drop `sakshi_portfolio.html` onto the Netlify dashboard
3. Your site goes live instantly with a free URL

### Option 4 — Deploy to Vercel
```bash
npm i -g vercel
vercel --name sakshi-portfolio
# Follow prompts — deploy in under a minute
```

---

## ✏️ Customization Guide

### Update Contact Info
Search for these strings in the HTML and replace:
```
msakshi5656@gmail.com     → your email
+91 6307635894            → your phone
sakshi-mishra-2525763aa   → your LinkedIn username
```

### Change Accent Colors
Edit the CSS variables at the top of the `<style>` block:
```css
:root {
  --cyan:   #00f5d4;   /* primary accent */
  --violet: #b060ff;   /* secondary accent */
  --gold:   #ffc947;   /* tertiary accent */
  --blue:   #4ca3ff;   /* quaternary accent */
}
```

### Add a New Project
Copy any `.proj-card` block inside `.projects-grid` and update the content. Use one of the existing badge classes: `badge-ai`, `badge-rag`, `badge-agent`, `badge-web`.

### Adjust Particle Density
In the `<script>` section, change `70` to increase or decrease the number of particles:
```js
const pts = Array.from({length: 70}, () => ({ ... }))
//                              ^^
//                        increase for more particles
```

---

## 📬 Contact

**Sakshi Mishra** — Generative AI & LLM Engineer  
📧 msakshi5656@gmail.com  
📞 +91 6307635894  
🔗 [linkedin.com/in/sakshi-mishra-2525763aa](https://linkedin.com/in/sakshi-mishra-2525763aa)  
📍 Lucknow, Uttar Pradesh, India

---

*Built with pure HTML, CSS & JavaScript — no frameworks, no fluff.*
