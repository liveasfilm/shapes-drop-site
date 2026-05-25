# shapes-drop-site

Marketing landing page and privacy policy for **Shapes Drop**, a cozy one-tap
merge puzzle game by [liveasfilm](https://github.com/liveasfilm).

The live site is deployed via **GitHub Pages** from the `main` branch:

- Home: <https://liveasfilm.github.io/shapes-drop-site/>
- Privacy policy: <https://liveasfilm.github.io/shapes-drop-site/privacy.html>

Use the privacy URL in the App Store / Google Play store listings.

## Structure

```
.
├── index.html         # Marketing landing page
├── privacy.html       # Privacy policy (App Store / Play Store compliant)
├── styles.css         # Shared styles (cotton-candy pastel theme)
├── .nojekyll          # Disable Jekyll on GitHub Pages
└── assets/
    ├── app_icon.png
    ├── feature_graphic.png
    └── screenshots/   # 01–05 phone screenshots
```

## Editing copy

Source-of-truth marketing copy lives in the main game repo at
`promo/en/store_listing_en.md`. Update that file first, then mirror changes
into `index.html`.

## Local preview

No build step — just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
open http://localhost:8000/
```
