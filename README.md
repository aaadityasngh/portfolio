# Aditya Singh — AI/ML Portfolio

A modern, animated, fully responsive personal portfolio website built with pure **HTML + CSS + JavaScript**.

This project showcases AI/ML-focused work, technical skills, achievements, and contact channels in a high-contrast, futuristic interface with smooth interactions.

---

## ✨ Why this portfolio is unique

- **Zero-framework frontend**: fast load, clean code, no runtime dependency bloat
- **Dual theme system**: dark mode by default + light mode toggle with persistence
- **Narrative-first structure**: projects, publication, startup journey, and achievements in one cohesive flow
- **Interaction-rich UI**: scroll reveals, active nav tracking, project glow effects, and polished mobile behavior

---

## 🚀 Key features

- Sticky navigation with active section highlighting
- Mobile-first hamburger menu with outside-click close
- Smooth reveal-on-scroll animations via `IntersectionObserver`
- Theme toggle with icon swap and localStorage persistence
- Project cards with dynamic mouse-position glow
- Responsive layouts for desktop, tablet, and mobile
- Contact CTA optimized for internships and collaborations

---

## 🧱 Tech stack

- **HTML5**
- **CSS3** (custom properties, gradients, media queries)
- **Vanilla JavaScript (ES6+)**
- **Google Fonts**: Syne, DM Sans, DM Mono

---

## 📁 Project structure

```text
portfolio/
├── index.html      # Main content and sections
├── style.css       # Theme system, layout, animations, responsive styles
├── main.js         # Interactivity (theme, nav, reveal, effects)
└── photo.png       # Profile image asset
```

---

## 🛠️ Getting started

Because this is a static website, setup is simple:

1. Clone the repository:
   ```bash
   git clone https://github.com/aaadityasngh/portfolio.git
   ```
2. Open the project folder.
3. Run locally by opening `index.html` in your browser.

Optional (recommended): use a local static server for best development workflow.

---

## 🎨 Customization guide

### Update personal content
- Edit text content, links, and section data in `index.html`
- Update profile image by replacing `photo.png`

### Adjust visuals
- Update color tokens and theme variables in `style.css` under:
  - `:root, [data-theme="dark"]`
  - `[data-theme="light"]`

### Tune interactions
- Edit behavior in `main.js`:
  - theme toggle logic
  - navbar scroll state
  - reveal observer thresholds
  - project card mouse glow

---

## 📱 Responsive behavior

The layout is tuned for:
- **Desktop** (`>1024px`)
- **Tablet** (`<=1024px`)
- **Mobile** (`<=768px`, `<=480px`)

Breakpoints and adjustments are handled in `style.css` media queries.

---

## 🚢 Deployment

This portfolio can be deployed directly as a static site on:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- Any static hosting provider

No build step is required.

---

## 🤝 Contact

- LinkedIn: [adityasingh-julyai](https://linkedin.com/in/adityasingh-julyai/)
- GitHub: [aaadityasngh](https://github.com/aaadityasngh)
- Email: ddeaditya@gmail.com

If you like this portfolio style, feel free to fork and adapt it for your own profile.
