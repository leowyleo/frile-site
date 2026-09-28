# Frile support site

Static bilingual pages for the App Store privacy-policy and support URLs.

- `/privacy/` and `/support/` — English
- `/zh/privacy/` and `/zh/support/` — Simplified Chinese
- `/` and `/zh/` — landing pages

Cloudflare Pages `_redirects` keeps the six canonical routes working with or without the trailing slash.

Deployed on Cloudflare Pages from the `main` branch. The production URL is <https://frile.leowy.cc>; the Cloudflare Pages fallback is <https://frile-site.pages.dev>.

Cloudflare Pages `_redirects` keeps the six canonical routes working with or without the trailing slash. Verify all six routes after content changes.
