# TriPylon Touch website

Static, responsive one-page website for TriPylon Touch. The page is self-contained in `index.html` (including its styles) and needs no build step or package manager.

## Files

- `index.html` — page markup, metadata, structured data, and styles
- `site.webmanifest` and `favicon.ico` — browser metadata
- `assets/brand/` — current TriPylon logo variants
- `assets/icons/` — browser and device icons
- `assets/images/` — optimized page imagery

## Preview

Serve this directory with any static HTTP server, then open `index.html` at the server URL. For example, `python -m http.server 8765` serves it at `http://localhost:8765/`.

## Publishing

Deploy the repository root as a static site. There is no build command and no output directory. The production URL in the page metadata is `https://tripylon.io/`.
