# my_portfolio

A minimal, clean personal portfolio built with plain HTML, CSS and JavaScript.
No build step, no dependencies.

## Features

- Single-page layout: Hero, About, Projects, Contact
- Responsive, mobile-first with a slide-down mobile menu
- Light / dark theme toggle (remembers your choice)
- Scroll-reveal animations (respects `prefers-reduced-motion`)
- Active nav highlighting and smooth scrolling

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customize

All content is marked with `<!-- EDIT: ... -->` comments in `index.html`.

1. **Name / logo / hero** — edit the nav brand and hero text.
2. **Bio & skills** — edit the About section and its `<ul class="tags">`.
3. **Projects** — duplicate an `<article class="card">` block per project.
4. **Contact & socials** — set your email and social URLs.
5. **Images** — add files to `assets/images/`:
   - `profile.jpg` (square, for the About portrait)
   - `project-1.jpg`, `project-2.jpg`, ... (16:10 works best)
   - Missing images fall back to a labeled placeholder automatically.
6. **Colors** — tweak the CSS custom properties at the top of
   `css/style.css` (`--accent`, `--bg`, `--text`, etc.) for both themes.

## Project structure

```
.
├── index.html
├── css/style.css
├── js/main.js
└── assets/images/
```
