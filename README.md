# Andreza Mackowiak — Portfolio

A single-page portfolio for a **WordPress Developer**, built as a static site for GitHub Pages. Hand-coded HTML/CSS in a bold editorial style — cream, lime & near-black, oversized display type, monospace labels — with anchor-based navigation and a mobile-responsive layout.

## Add your photo
The hero shows a styled placeholder (an "AM" monogram) until you add a photo. Drop a portrait at **`assets/andreza.jpg`** and it will replace the placeholder automatically. For best results use a portrait-orientation image (roughly 700×1000px or taller).

## Sections
- **Home** — intro / hero
- **About** — background and focus
- **Skills** — WordPress development, front-end, back-end & data, QA & performance
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
- A few lines of vanilla JS for the scroll-reveal nav
- Google Fonts: Archivo Black + Archivo + Space Mono + Open Sans
