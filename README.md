# Holonote site

Static, three pages, no build step. Upload the folder as-is to any host (Netlify, Cloudflare Pages, GitHub Pages, or plain S3).

- `index.html` — icon, name, tagline, App Store badge, footer links
- `privacy.html` — the 3.0 privacy policy (matches the "Data Not Collected" store label)
- `terms.html` — points at Apple's standard EULA
- `style.css` — the app's light and dark grounds; follows the visitor's system setting
- `icon.png` — 512px app icon, also the favicon

The App Store badge is Apple's own, served from tools.applemediaservices.com (the official
way to link a badge). The link goes to app id 6498865976.

`preview-*.png` are screenshots for review, not part of the site.
