# PromiseArc marketing website

Initial public site for PromiseArc, a product from Outcome Labs. The site is static, dependency-free, and has no build step.

## Structure

- `index.html` — primary marketing page
- `styles.css` — design system and responsive layout
- `script.js` — accessible mobile navigation and small header enhancements
- `privacy.html`, `terms.html` — clearly marked interim legal placeholders
- `404.html`, `robots.txt`, `sitemap.xml`, `.nojekyll` — static hosting infrastructure
- `assets/` — icons and social sharing image
- `docs/website-execution-guide.md` — standing execution rules for agents changing the marketing site

## Execution guide

Before making substantive website changes, read [`docs/website-execution-guide.md`](docs/website-execution-guide.md).

GitHub Issues remain the source of truth for **what** to change. The execution guide defines **how** work should be selected, implemented, validated, and handed off while preserving the current PromiseArc strategy, public-claims discipline, static architecture, responsive behavior, and accessibility expectations.

## Run locally

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## GitHub Pages

In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. The expected URL is `https://savioronezero.github.io/customer-outcomes-website/`.

If a custom domain is introduced, update the canonical and social URLs in `index.html`, plus `robots.txt` and `sitemap.xml`.

## Public-site follow-ups

- Confirm `hello@promisearc.com` remains the correct contact address.
- Replace Privacy and Terms interim language with counsel-approved policies when available.
- Replace the intentional capability view with approved product screenshots when the canonical demo portfolio is ready.
- Keep canonical and social metadata aligned with the production domain and current GTM positioning.

No analytics, tracking pixels, cookies, or third-party dependencies are included.

## Ownership and licensing

PromiseArc is marketed under the Outcome Labs brand. Copyright in the first-party website source, copy, visual design/expression, artwork, documentation, and brand assets remains with Andrew E. Reynolds until formally assigned.

This repository is publicly readable but is not open source. Public access grants no permission to copy, modify, distribute, or reuse first-party materials. See [`LICENSE`](LICENSE) for the proprietary terms and third-party-rights notice.
