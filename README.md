# Arab Community Alliance (ACA)

Landing page for [arabcommunityalliance.org](https://www.arabcommunityalliance.org) — a not-for-profit community organization serving Arab-Americans in Tampa Bay, Florida.

Static site (plain HTML/CSS), hosted on GitHub Pages.

## Files

- `index.html` — the page
- `styles.css` — styles (bilingual EN/AR, responsive)
- `qr.svg` — QR code pointing to the site
- `CNAME` — custom domain config for GitHub Pages
- `.nojekyll` — disables Jekyll processing

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploy

Pushed to `main` on GitHub, served via GitHub Pages with custom domain `arabcommunityalliance.org`.

## Edit content

All text lives in `index.html`. Contact details, program lists, and Arabic strings are plain text you can edit directly.
