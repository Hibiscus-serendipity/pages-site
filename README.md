# pages-site

This repository now contains a minimal static website scaffold in the `public/` folder and a GitHub Actions workflow to deploy it to GitHub Pages.

How to preview locally:

```bash
# from repository root
python3 -m http.server --directory public 8000
# then open http://localhost:8000
```

What's included:
- `public/index.html` — main page
- `public/styles.css` — styling
- `.github/workflows/pages.yml` — deploy workflow

Edit the site files under `public/`, commit, and push to `main` (or branch `add-site`) to trigger Pages deployment.
# pages-site