# soulcamp

Website for SOUL CAMP — a creative training camp for girls to learn AI tools and compete in a 24-hour challenge. November 21–22, 2026, Almaty.

Live site (once GitHub Pages is on): https://angrytengri.github.io/soulcamp/

## Files

- `index.html` — the whole page (HTML, CSS and JS in one file)
- `assets/` — logo, apply button and trophy images
- `.nojekyll` — tells GitHub Pages to serve the files as they are

## Run locally

```bash
python3 -m http.server 4321
```

Then open http://localhost:4321

## Publish with GitHub Pages

1. Push to `main`.
2. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: `main`, folder: `/ (root)` → **Save**.
4. After a minute or two the site is live at the URL above.

## To do

- Replace the dark photo placeholders (`<div class="ph">`) with real photos
- Connect the registration form to a form service (see the `TODO` in `index.html`)
- Fill in real contact details
