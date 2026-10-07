# TriPylon website

Static, responsive website for TriPylon Touch and business offerings. Each HTML page includes its own styles; no build step or package manager is needed.

## Files

- `index.html` — TriPylon Touch landing page
- `business.html` — business HSM and SDK page
- `whitelabel.html` — White Label hardware wallet page
- `site.webmanifest` and `favicon.ico` — browser metadata
- `robots.txt` and `sitemap.xml` — search crawler guidance
- `assets/brand/` — current TriPylon logo variants
- `assets/icons/` — browser and device icons
- `assets/images/` — optimized page imagery

## Preview

Serve this directory with any static HTTP server, then open `index.html` at the server URL. For example, `python -m http.server 8765` serves it at `http://localhost:8765/`.

## Publishing

Deploy the repository root as a static site. There is no build command and no output directory. The production URL in the page metadata is `https://tripylon.io/`.
