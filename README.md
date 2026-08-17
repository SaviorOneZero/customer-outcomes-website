# PromiseArc marketing website

Initial public site for PromiseArc, a product from Outcome Labs. The site is static, dependency-free, and has no build step.

## Structure

- `index.html` — primary marketing page
- `styles.css` — design system and responsive layout
- `script.js` — accessible mobile navigation and small header enhancements
- `privacy.html`, `terms.html` — clearly marked interim legal placeholders
- `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll` — static hosting infrastructure
- `assets/` — icons and social sharing image

## Run locally

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## GitHub Pages

In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. The expected URL is `https://savioronezero.github.io/customer-outcomes-website/`.

If a custom domain is introduced, update the canonical and social URLs in `index.html`, plus `robots.txt` and `sitemap.xml`.

## Before public launch

- Confirm `hello@promisearc.com` is the correct contact address.
- Replace Privacy and Terms placeholders with counsel-approved policies.
- Replace the intentional capability view with approved product screenshots when available.
- Confirm the production domain and update canonical metadata.

No analytics, tracking pixels, cookies, or third-party dependencies are included.
