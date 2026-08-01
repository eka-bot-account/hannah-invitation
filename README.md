# Hannah's 1st Birthday Invitation

Static invitation page — **Sunday 6 Sept 2026, 12:00 PM · Cook Park Picnic Grounds, Ramsgate Beach.**

Live: https://yen223.github.io/hannah-invitation/

## Files

- `index.html` — the whole page. Self-contained (inline styles + SVG), no build step, no JS.
- `og-preview-square.png` — 1200×1200 social preview image (WhatsApp / iMessage / Twitter link cards).
  Square because the card is taller than it is wide — a 1200×630 crop clipped the sun off the top
  and the sign-off off the bottom.
- `invite-card.png` — 1320×1263 flat render of just the card, desktop proportions. For sending the
  invite as an image instead of a link.
- `invite-card-mobile.png` — 1170×1764, the same thing at phone width (390px @ 3x).
- `.nojekyll` — tells GitHub Pages to serve files as-is.

Originally designed in Claude Design (`Hannah Invitation.dc.html`). The `.dc.html` template
variables and the `support.js` runtime have been pre-rendered away, so this is plain static HTML.

## Editing

Open `index.html` and edit directly. Things you'll likely want:

| What | Where |
| --- | --- |
| Date / time | `Sunday · 6 Sept 2026 · 12:00 PM` |
| Venue | `Ramsgate Beach` / `Cook Park Picnic Grounds` |
| Accent colour | `#e59a86` (appears several times) |
| Phone layout | the `@media (max-width: 560px)` block |

## Note after transferring the repo

The `og:image` / `twitter:image` meta tags use an absolute URL pointing at
`yen223.github.io`. After transferring the repo to another account, update those two
URLs to the new Pages domain, or link previews will break.
