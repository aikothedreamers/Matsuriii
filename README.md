# Matsuri Light — Vercel Static

This version is intentionally **static-only** while the payment/registration system is paused.

## Included
- `index.html` — public tournament website
- `assets/` — race preview, skills, hero artwork
- `css/` and `js/` — public site assets
- `admin.html` — kept as a dormant file for later backend restoration; it is not linked from the public site

## Temporarily removed
- `registration.html`
- Registration/payment API
- Midtrans / GoPay integration
- Fonnte integration
- Node server
- Vercel serverless functions

## Vercel
Upload/push the **contents of this folder** to the GitHub repository root. There is intentionally no `package.json`, `vercel.json`, `api/`, or Node server in this version, so Vercel serves it as a plain static site.
