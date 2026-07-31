# Hannah's 1st Birthday Invitation

Static invitation page — **Sunday 9 Sept 2026, 12:00 PM · Cook Park Picnic Grounds, Ramsgate Beach.**

Live: https://eka-bot-account.github.io/hannah-invitation/

## Files

- `index.html` — the whole page. Self-contained (inline styles + SVG), no build step, no JS.
- `og-preview.png` — 1200×630 social preview image (WhatsApp / iMessage / Twitter link cards).
- `.nojekyll` — tells GitHub Pages to serve files as-is.

Originally designed in Claude Design (`Hannah Invitation.dc.html`). The `.dc.html` template
variables and the `support.js` runtime have been pre-rendered away, so this is plain static HTML.

## Editing

Open `index.html` and edit directly. Things you'll likely want:

| What | Where |
| --- | --- |
| Date / time | `Sunday · 9 Sept 2026 · 12:00 PM` |
| Venue | `Ramsgate Beach` / `Cook Park Picnic Grounds` |
| Map link | the `maps.app.goo.gl` href on the "Get directions" button |
| Accent colour | `#e59a86` (appears several times) |

## Note after transferring the repo

The `og:image` / `twitter:image` meta tags use an absolute URL pointing at
`eka-bot-account.github.io`. After transferring the repo to another account, update those two
URLs to the new Pages domain, or link previews will break.
