# Noviq Studios — noviqstudios.nl

Static site for Noviq Studios. Hand-coded, no build step, hosted on GitHub Pages.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `services.html` | Services |
| `work.html` | Work |
| `process.html` | Process |
| `faq.html` | FAQ |
| `proposal.html` | Request a proposal |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms & Conditions |
| `cookies.html` | Cookie Policy |
| `refund.html` | Refund & Cancellation Policy |

## Shared parts

`SiteNav.dc.html`, `SiteFooter.dc.html` and `SiteChat.dc.html` hold the header, footer and chat
assistant. Every page loads all three, so editing one of these files changes that element
site-wide. They must stay in the same folder as the pages.

`support.js` is the small runtime the pages load. It has to sit next to them.

## Assets

- `fonts/` — Outfit, DM Sans and JetBrains Mono, self-hosted. No requests go to Google Fonts.
- `img/` — the logo mark and the Haven Physio concept screenshots.
- `CNAME` — the custom domain.
- `.nojekyll` — tells GitHub Pages to serve the files as they are.

## Deploying

Commit the contents of this folder to the repository root, on the branch GitHub Pages is set to
serve. All paths are relative, so the site also opens by double-clicking `index.html`.

## Before going live

Fill in these placeholders, which appear in the policy pages and the footer:

- `[Your full legal name]`
- `[KvK number]`
- `[14]` days — the payment term in `terms.html`
- `[your district/city]` — the court named in `terms.html`

The policy pages are plain-English templates, not legal advice. Have them reviewed before you
rely on them for paying clients.

## Timings used across the site

Meet & plan, 4 business days · Build & test, 2 business days · Connect & launch, 3 business days —
nine business days in total. If you change these, they appear on `index.html`, `process.html`,
`faq.html`, `work.html`, `services.html` and in the chat assistant's answers in `SiteChat.dc.html`.
