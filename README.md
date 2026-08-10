# Andreza Mackowiak — Portfolio

A single-page portfolio for a **Web & Email Developer**, built as a static site for GitHub Pages. Hand-coded HTML/CSS with a purple & lime theme, anchor-based navigation, and a mobile-responsive layout.

## Sections
- **Home** — intro / hero
- **About** — background and focus
- **Skills** — email development, front-end, CMS/platforms, QA & performance
- **Experience** — work history timeline
- **Projects** — selected builds and maintenance work
- **Contact** — email & LinkedIn

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Deploy to GitHub Pages
1. Create a repo (e.g. `portfolio` or `<username>.github.io`).
2. Push these files.
3. In **Settings → Pages**, set the source to the `main` branch, root folder.
4. Your site publishes at `https://<username>.github.io/<repo>/`.

## Tech
- Plain HTML5 & CSS3 (no build step)
- Vanilla JS for the mobile menu
- Google Fonts: Space Grotesk + Inter
