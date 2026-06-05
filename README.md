# Netflix UI Clone

A static front-end clone of the [Netflix](https://www.netflix.com) landing page, styled for the Pakistan region. This project is built with **HTML and CSS only** — no JavaScript frameworks, no backend, and no build step.

**Repository:** [github.com/adilurrehman/netflix-ui-clone](https://github.com/adilurrehman/netflix-ui-clone)

> **Disclaimer:** This is an educational UI clone for learning and portfolio purposes. It is **not** affiliated with, endorsed by, or connected to Netflix, Inc. All branding and media assets belong to their respective owners.

---

## Live Demo

🌐 **Live Site:** [https://adilurrehman.github.io/netflix-ui-clone/](https://adilurrehman.github.io/netflix-ui-clone/)

| | |
|:--|:--|
| **Direct link** | [Open Netflix UI Clone](https://adilurrehman.github.io/netflix-ui-clone/) |
| **Repo shortcut** | Use the **Website** link in the repository sidebar (About section) |

> **Note:** If you click the link from this README, GitHub may show a brief *"You are leaving GitHub.com"* redirect page — this is normal. Click **Continue** to open the live site. Browsers may also warn on Netflix-style clones; the live page includes an educational disclaimer banner.

---

## Features

- **Hero section** — Background image, email signup form, and call-to-action
- **Feature sections** — TV, mobile download, watch everywhere, and kids profiles
- **Embedded video demos** — Looping `.m4v` clips inside device mockups
- **FAQ section** — Accordion-style question list (visual only)
- **Footer** — Multi-column links and language selector
- **Fully responsive** — Media queries for tablet and mobile breakpoints

---

## Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic layout |
| CSS3 | Styling, flexbox, grid, and responsive design |
| GitHub Pages | Static hosting |

No JavaScript, npm, or bundler is required.

---

## Project Structure

```
netflix-ui-clone/
├── index.html              # Main landing page
├── css/
│   └── styles.css          # All styles (extracted from HTML)
├── assets/
│   ├── images/             # Logos, backgrounds, device mockups
│   ├── videos/             # Looping feature section videos
│   └── icons/              # Favicon
└── pages/                  # Reserved for additional HTML pages
```

---

## Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Edge, Safari)
- A local file server is optional but recommended for accurate asset loading

### Clone the repository

```bash
git clone https://github.com/adilurrehman/netflix-ui-clone.git
cd netflix-ui-clone
```

### Run locally

**Option 1 — Open directly**

Double-click `index.html` or drag it into your browser.

**Option 2 — Local server (recommended)**

Using Python:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Using Node.js (`npx`):

```bash
npx serve .
```

---

## Deploy to GitHub Pages

1. Push this repository to [adilurrehman/netflix-ui-clone](https://github.com/adilurrehman/netflix-ui-clone).
2. Go to **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push to `main` — the included workflow deploys the site automatically.
5. Your site will be live at **[adilurrehman.github.io/netflix-ui-clone](https://adilurrehman.github.io/netflix-ui-clone/)**.

---

## Pages & Sections

| Section | Description |
|---|---|
| Navigation | Netflix logo, language selector, Sign In button |
| Hero | Headline, subtext, email input, Get Started CTA |
| Enjoy on your TV | TV mockup with looping video |
| Download offline | Mobile mockup with looping video |
| Watch everywhere | TV mockup with alternate video |
| Kids profiles | Kids-themed section with device image |
| FAQ | Six frequently asked questions |
| Footer | Support links, language selector, region label |

---

## Customization

- **Styles** — Edit `css/styles.css`
- **Content** — Update copy directly in `index.html`
- **Images** — Replace files in `assets/images/` (keep filenames or update paths in HTML/CSS)
- **Videos** — Swap `.m4v` files in `assets/videos/`

---

## Browser Support

Tested and works in all modern browsers that support:

- CSS Flexbox & Grid
- HTML5 `<video>` element
- CSS media queries

---

## License

This project is for **educational use only**. Netflix and its logo are registered trademarks of Netflix, Inc. Do not use this clone for commercial purposes or to misrepresent affiliation with Netflix.

---

## Author

**[Adil Ur Rehman](https://github.com/adilurrehman)**

Built as a front-end practice project — HTML & CSS Netflix landing page clone.
