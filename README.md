# Soheil Mohammadkhani — Academic Homepage

A static academic homepage built from `cv/cv.tex`. It has no backend and no build step, so it can be hosted directly with GitHub Pages.

## Preview locally

From the repository root, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Updating the CV

The website links to `cv/cv.pdf`. After editing `cv/cv.tex`, rebuild it with:

```bash
cd cv
latexmk -pdf cv.tex
```

## Publishing with GitHub Pages

Push the repository to GitHub, then select **Deploy from a branch** and the repository root in **Settings → Pages**.
