# UrbanAI-101

Spatial statistics and urban analytics — Jupyter Book.

## Read online

The book will be available at:

**https://\<your-username\>.github.io/UrbanAI-101/**

after you enable GitHub Pages (see below).

## Build locally

```bash
pip install -r requirements.txt
jupyter-book build .
# Open _build/html/index.html in browser
```

## Deploy to GitHub Pages

1. **Enable GitHub Pages**  
   In the repository: **Settings** → **Pages** → **Build and deployment** → set Source to **GitHub Actions**.

2. **Push code**  
   After pushing this repo to GitHub, each push to the `main` (or `master`) branch will trigger the Actions workflow to build and publish the book.

3. **View the site**  
   When the build finishes, the site URL appears under **Settings** → **Pages**, usually:
   `https://<username>.github.io/UrbanAI-101/`

## Repository structure

- `_config.yml` — Jupyter Book configuration
- `_toc.yml` — Table of contents
- `intro.md` — Book landing page
- `2_spatial-statistics/` — Spatial statistics chapter and notebooks
