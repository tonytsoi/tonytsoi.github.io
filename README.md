# Personal Website

Personal website of Tony Tsoi — data science, economics and quantitative finance.

Built with plain HTML, CSS and JavaScript (no frameworks, no build step) and hosted on GitHub Pages.

## Structure

- `index.html` — single-page site (about, skills, experience, projects, articles, contact)
- `css/style.css` — styles, with light/dark theme via CSS variables
- `js/main.js` — mobile nav, active-section highlighting, scroll reveal
- `assets/` — images (profile photo, etc.)

## Local preview

Open `index.html` directly in a browser, or serve it:

```
python -m http.server
```

## Deployment

Served by GitHub Pages from the `main` branch root. Enable under **Settings → Pages → Deploy from a branch → main / (root)**.
