# Portfolio Website (GitHub Pages)

This repository contains a static portfolio website built with **HTML, CSS, and JavaScript** and configured for **automatic GitHub Pages deployment**.

## What is included

- `index.html` – page structure and content
- `style.css` – site styling and responsive layout
- `script.js` – client-side interactions
- `assets/` – image assets
- `.github/workflows/deploy.yml` – GitHub Actions workflow that deploys this site to GitHub Pages

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Ensure your default branch is `main`.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **GitHub Actions**.
5. Push to `main` (or run the workflow manually from **Actions**).

After deployment, the site will be published at:

- `https://<your-username>.github.io/<repo-name>/`

If you publish from a project repository (not `username.github.io`), keep asset paths relative (as already done in this project).

## Local preview

You can preview locally by opening `index.html` directly in a browser, or run a simple static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
