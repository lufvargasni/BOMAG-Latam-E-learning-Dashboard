# BOMAG LATAM E-learning Dashboard

An interactive dashboard that tracks distributor progress across the BOMAG LATAM e-learning program.

## Live site

Once GitHub Pages is enabled, the dashboard will be available at:

**https://lufvargasni.github.io/BOMAG-Latam-E-learning-Dashboard/**

## Running locally

The dashboard is a single self-contained HTML file. To preview it locally just open `index.html` in a browser, or serve the folder with any static server:

```bash
# Python 3
python3 -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000/.

## Enabling GitHub Pages

1. Push this repository to GitHub (already done).
2. In GitHub, go to **Settings → Pages**.
3. Under *Build and deployment*, set **Source** to `Deploy from a branch`.
4. Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
5. Wait ~1 minute and refresh — the published URL will appear at the top of the Pages settings page.

## Repository contents

- `index.html` — the dashboard (entry point served by GitHub Pages).
- `404.html` — fallback page shown for unknown URLs.
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing so files are served as-is.
- `README.md` — this file.
