# SPARK Mission Website

A static, GitHub-ready website for **SPARK — Solar Particle Acceleration, Radiation and Kinetics**, an ESA M-class mission concept focused on solar flare particle acceleration, radiation and kinetics.

## Files

```text
spark-website/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── favicon.svg
│   └── spark-og.svg
└── .github/
    └── workflows/
        └── pages.yml
```

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploying with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder.
3. In GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, select **GitHub Actions**.
5. Push to the `main` branch. The included workflow will publish the site.

## Editing content

Most content is in `index.html`. Styling is in `styles.css`. The mobile menu and reveal animations are in `script.js`.

## Suggested future additions

- Replace abstract SVG social image with a mission render or approved SPARK visual.
- Add dedicated pages for Science, Mission Concept, Instruments, Team, News and Outreach if the one-page site grows.
- Add real partner logos once permissions and branding rules are confirmed.
- Add mission diagrams, LASSAN/HiFI instrument sketches and flare imagery.
