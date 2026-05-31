# Poteeswaran M — Portfolio

Static portfolio site for [poteeswaran02.github.io/portfolio](https://poteeswaran02.github.io/portfolio/).

## Local preview

Open `index.html` in a browser, or run a simple server:

```bash
cd p:\pppp
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Deploy to GitHub Pages

This site is meant to live in the **`portfolio`** folder of your GitHub Pages repo (project site at `/portfolio/`).

1. Clone your portfolio repo (or the repo that hosts Pages).
2. Copy `index.html` and the `assets/` folder into the repo root or `portfolio/` subfolder — whichever matches your current Pages URL.
3. Commit and push to `main`:

```bash
git add index.html assets/
git commit -m "Sync portfolio content with 2026 resume"
git push origin main
```

Pages usually updates within 1–2 minutes.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Single-page portfolio |
| `assets/avatar.png` | Profile photo |
| `assets/resume.pdf` | Downloadable resume |
