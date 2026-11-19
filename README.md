# Finwell Ocean Trust — Website

Source for the Finwell Ocean Trust public website.

**Live site:** https://finwell-ocean-trust.github.io/website/

## Structure

| File          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| `index.html`  | Homepage: mission, impact figures, programs, partners |
| `about.html`  | Organization history, milestones and leadership       |
| `styles.css`  | Shared stylesheet (brand palette, type, layout)       |
| `favicon.svg` | Site icon                                             |

The site is plain HTML and CSS, with no build step. Fonts (Fraunces and Inter) load from Google Fonts.

## Local preview

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Deployment

The site is deployed with GitHub Pages from the `main` branch (root folder). Changes pushed to `main` go live within a few minutes.

## Contact

Questions about the site go to the communications team: info@finwelloceantrust.org

© 2011–2026 Finwell Ocean Trust
