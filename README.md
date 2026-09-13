# Helion Compact — promo

Public marketing site for **THE HELION COMPACT** (helioncompact.com).

Live offer: **LOW WATER — Early Access Copy** (Book 1), USD $19.99.

- **Domain:** helioncompact.com (Cloudflare Pages project `helioncompact`)
- **Ops / canon:** private `helion-compact-ops` (not this repo)
- **Do not** commit manuscripts, enhance drafts, or secrets here
- Locked cover only: `cover-A2r.jpg` (do not replace or regenerate)

## Stack
Static Cloudflare Pages. PayPal Buttons SDK on the landing page (`currency=USD`, `intent=capture`). After capture, checkout sends buyers to `thanks.html` for a delivery-email capture.

Formspree actions:

- Fulfillment (thanks page): `https://formspree.io/f/xeaqbpjn`
- Release notes (index): `https://formspree.io/f/moeqopab`

`robots.txt` allows the public promo URL and disallows `/thanks.html` and `/thanks/`. `sitemap.xml` lists `https://helioncompact.com/` only.
