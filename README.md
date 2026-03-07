# harmishkachhadiya.in

Personal portfolio of **Harmish Kachhadiya** — Computer Science student, full-stack developer, Telegram bot builder, and IoT tinkerer.

Built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools, no dependencies — just raw code with bold design choices.

**[Live Site](https://harmishkachhadiya.in)**

---

## What is Neo-Brutalism?

Neo-brutalism is a UI style inspired by brutalist architecture — raw, bold, and unapologetically loud. It rejects the polished, rounded sameness of modern web design and replaces it with:

- **Thick black borders** — every element has a hard, visible edge
- **Flat, offset box shadows** — solid color blocks shifted by a few pixels (`box-shadow: 8px 8px 0 #000`)
- **High-contrast color palettes** — bright yellows, pinks, cyans, and greens
- **Visible structure** — the bones of the layout are intentionally exposed
- **Playful imperfection** — tape stickers, hand-drawn vibes mixed with geometric precision

---

## Design System

### Colors

| Color  | Variable   | Usage                        |
|--------|------------|------------------------------|
| Yellow | `--yellow` | Primary accent, CTAs, loader |
| Cyan   | `--cyan`   | Code elements, highlights    |
| Pink   | `--pink`   | Secondary accent             |
| Green  | `--green`  | Success states, highlights   |
| Black  | `--border` | Borders, shadows, text       |

### Typography

- **Space Grotesk** — headings and body text
- **Space Mono** — code snippets and terminal elements
- **Caveat** — handwritten annotations

---

## Key Features

**Bento Grid About Section** — Asymmetric card layout with bio, availability status, stats, location, and tech stack tags.

**Book Flip Timeline** — The projects section starts as a closed book that flips open to reveal the project timeline and animated skill bars.

**Scroll-Driven Highlights** — Text highlights animate in from left/right on scroll, mimicking a highlighter pen.

**Animated Skill Bars** — Categorised skill bars (Languages, Backend, Frontend, Tools) animate into view via IntersectionObserver.

**Matrix Typing Effect** — The hero greeting scrambles through random characters before resolving to the final text.

**Falling Decorative Icons** — SVG icons around the hero photo drop with gravity on scroll.

**Dark / Light Theme** — Full theme toggle with CSS custom properties.

---

## Project Structure

```
.
├── index.html          # Main portfolio (neo-brutalist)
├── neo-styles.css      # Styles for index.html
├── terminal.html       # Terminal-style resume
├── styles.css          # Styles for terminal.html
├── script.js           # Terminal logic & commands
├── favicon.svg         # Site favicon
├── image/              # Assets (avatar, icons)
├── CNAME               # Custom domain config
├── robots.txt          # Search engine directives
├── sitemap.xml         # Sitemap for SEO
└── LICENSE             # Proprietary license
```

---

## Tech Stack

- **HTML/CSS/JS** — no frameworks, no build step
- **Font Awesome** — icons
- **Google Fonts** — Space Grotesk, Space Mono, Caveat, Fira Code

---

## Run Locally

```bash
npx serve .
# or
python3 -m http.server 8000
```

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
