# MB Portfolio — Behavioral Health RCM

A responsive, motion-rich GitHub Pages portfolio for full-cycle behavioral health, mental health, ABA, SUD, IOP, PHP, RTC, detox, outpatient, CMS-1500 and UB-04 billing.

## Publish
1. Create a public GitHub repository.
2. Upload the contents of this folder.
3. Open Settings → Pages and choose GitHub Actions.
4. Push to `main`; `.github/workflows/deploy.yml` publishes the site.

## Included sanitized samples
- Behavioral health billing SOP
- Denial tracker CSV
- KPI dashboard CSV

## Compliance
Do not add PHI, patient screenshots, claim numbers, client credentials, payer portal screenshots, or confidential reports. Testimonials should be published only with permission. Code/modifier use depends on current payer policy, contract, state, setting, and documentation.


## Important GitHub upload rule
Upload the **contents inside** `mb-rcm-portfolio-v3` to the repository root. `index.html`, `styles.css`, `script.js`, and the `assets` folder must sit at the same repository level. The portrait is also embedded directly in `index.html`, so it remains visible even if an asset path is misconfigured.


## v4 production notes
- Upload the ZIP contents directly to the repository root.
- The root contains `favicon.ico`, PNG favicons, Apple touch icon, PWA manifest, `robots.txt`, `sitemap.xml`, Open Graph image and structured data.
- Chrome aggressively caches favicons. After deployment, open `https://bilawal-1.github.io/portfolio1/favicon.ico?v=4`, then hard-refresh the portfolio or reopen Chrome.
- The site is optimized for desktop, laptop, macOS, tablets and phones down to 320px width.


## v6 update
- Keeps all content from the supplied v4 index.
- Restores the portrait via `assets/profile-circle.png`.
- Adds 50-state readiness, CMS-1500/837P and UB-04/837I visual metrics.
- Adds visible service, coding, modifier and POS matrix.
- Adds analytics comparisons and a fixed fox mascot whose eyes follow the cursor and reacts when poked.
