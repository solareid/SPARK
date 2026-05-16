# SPARK Mission Website — Version 2

Enhanced multi-page static website for **SPARK — Solar Particle Acceleration, Radiation and Kinetics**.

## Structure

```text
index.html          Home
science.html        Science case and objectives
mission.html        Mission concept and observing strategy
instruments.html    LASSAN and HiFI
data.html           Open science and data products
team.html           Consortium and collaboration
outreach.html       Outreach and education
news.html           News placeholders
contact.html        Contact information
styles.css          Shared styling
script.js           Mobile navigation and reveal animation
assets/             SVG favicon and social preview image
.github/workflows/  GitHub Pages deployment workflow
```

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## GitHub Pages

This repository includes a GitHub Actions workflow for Pages deployment. Commit these files to the repository root and GitHub Pages will deploy the site from the `main` branch.

## Editing

Visible text is contained in the individual HTML pages. Shared styling is in `styles.css`.
