# Jeffrey Willeford — Author Site

A fast, single-file website for my books and author info. Dark fantasy, horror, and sci-fi that hit like thunder—browse the books and jump to my Amazon Author Page.

**Live site:** https://YOUR-SITE-URL (replace after deploy)

---

## Features
- ⚡ Single HTML file (images embedded as data URIs)
- 🔒 HTTPS-friendly with Content Security Policy meta
- 🔗 Social share tags (Open Graph/Twitter ready)
- 🧼 No frameworks, zero build step

## Getting Started
- Open `index.html` in any modern browser (Chrome/Edge).
- To update covers/author photo, rebuild `index.html` with the PowerShell script you used (it re-embeds selected images directly into the file).

## Deploy
**Netlify (recommended)**
1. Drag `index.html` (or a ZIP of the folder) to **Add new site → Deploy manually**.
2. In Site settings → Domain management, enable HTTPS (usually automatic).

**GitHub Pages**
1. Create repo `jeffwilleford.github.io`.
2. Upload `index.html` to the repo root.
3. Repo Settings → Pages → Enforce HTTPS.

## SEO & Sharing
Add/adjust in `<head>` of `index.html`:
```html
<meta name="description" content="Jeffrey Willeford writes dark fantasy, horror, and sci-fi that hit like thunder. Browse books and start your next obsession.">
<meta property="og:title" content="Jeffrey Willeford — Author">
<meta property="og:description" content="Dark fantasy, horror, and sci-fi that hit like thunder.">
<meta property="og:type" content="website">
<!-- Set og:image to a hosted image URL once live -->
index.html
LICENSE            # MIT license for site code
CONTENT-LICENSE    # All rights reserved for text & images
.gitignore

Want me to drop in your actual live URL and tailor the SEO block for it?
