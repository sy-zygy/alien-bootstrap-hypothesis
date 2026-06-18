# Alien Bootstrap Hypothesis

A general-audience article on the Alien Bootstrap Hypothesis and the Kent Equation,
by Gabriel Kent (Rhomega Corp.).

**Read it online:** https://sy-zygy.github.io/alien-bootstrap-hypothesis/

## Layout

- `article/index.html` — the article (a self-contained HTML page). This folder is
  what gets published to GitHub Pages.
- `src/` — the source papers:
  - `Alien Bootstrap Hypothesis.pdf`
  - `The Kent Equation v5.pdf`

## Publishing

GitHub Pages is built by the workflow in `.github/workflows/pages.yml`, which
publishes the `article/` folder. Any push to `main` that touches `article/`
redeploys the live site automatically. The Pages source must be set to
**GitHub Actions** (Settings → Pages → Build and deployment → Source).
