# Portfolio (GitHub Pages ready)

Static site for Tipape Matayo's portfolio and UNITY WITHIN initiative. Everything runs client-side with plain HTML/CSS/JS plus CDN-loaded Bootstrap and icons, so it can be served directly by GitHub Pages without a build step.

## Quick start (local)
1. Clone the repo and open the folder.
2. Open `index.html` in your browser, or run a simple server (for example, `python -m http.server 8000`).

## Deploy to GitHub Pages
1. Push this repository to GitHub (e.g., `TIPAPE-254/my-portfolio`).
2. In GitHub: Settings → Pages.
3. Source: **Deploy from a branch**. Branch: **main**. Folder: **/ (root)**. Save.
4. Wait for Pages to build. Your site will be live at `https://<username>.github.io/my-portfolio/`.

### Custom domain (optional)
If you have a domain, add it in Settings → Pages under **Custom domain**, then create the suggested DNS records (usually a CNAME to `<username>.github.io`).

### Notes
- Asset paths are relative (e.g., `assets/...`), so they work on both the root domain and the repository subpath.
- External dependencies (Bootstrap, Bootstrap Icons, Google Fonts) load via HTTPS CDNs; no additional configuration is required.
- WhatsApp CTA uses `https://wa.me/254715765561` so it works correctly on GitHub Pages.
