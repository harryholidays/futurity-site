# Futurity Site

Static export of the Futurity website (Webflow). Pages are plain HTML; CSS, JS,
images and video are served from Webflow's CDN via absolute URLs, so the site is
fully functional when served as static files.

## Structure
- `index.html` and top-level pages (`about`, `contact`, `faqs`, etc.)
- `news/` — article pages
- `netlify.toml` — Netlify config (publish root, 404 fallback)

## Deploy
Hosted on Netlify as a static site (publish directory = repo root).
