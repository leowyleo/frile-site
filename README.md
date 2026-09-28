# Frile support site

Static bilingual pages for the App Store privacy-policy and support URLs.

- `/privacy/` and `/support/` — English
- `/zh/privacy/` and `/zh/support/` — Simplified Chinese
- `/` and `/zh/` — landing pages

Cloudflare Pages `_redirects` keeps the six canonical routes working with or without the trailing slash.

The paths are ready for a static host that serves `index.html` for directory URLs. Before publishing, confirm the domain and email address, then verify each public URL over HTTPS. These files are not live until deployed.
