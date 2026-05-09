# mcmillinanalytics-site

Static landing page for [mcmillinanalytics.com](https://mcmillinanalytics.com).

Deployed via Cloudflare Pages on every push to `main`.

## Local preview

```powershell
python -m http.server 8000
# then open http://localhost:8000
```

## Files

- `index.html` — single-page site (inline CSS, no build step)
- `robots.txt` — allow-all + sitemap pointer
- `sitemap.xml` — homepage entry
- `_headers` — Cloudflare Pages security headers
- `og-card.png` — Open Graph / Twitter Card preview image
- `screenshots/` — featured-project images
