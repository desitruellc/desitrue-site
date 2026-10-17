# DesiTrue Services LLC website

Static marketing site for Desirée Truesdale's bookkeeping, admin-support and creative-marketing business, served by GitHub Pages from `main` / root. The owner is not a developer: explain changes in plain words, show a preview (Browser pane, phone and desktop width) and wait for her OK before committing or pushing.

Gotchas the files won't tell you:
- No build step, on purpose. Plain HTML + `css/site.css`; don't add a framework, bundler or npm.
- Header and footer are repeated in all four `.html` files. A change to either goes into every page.
- Brand tokens live in `:root` of `css/site.css`. Rose gold `#B76E79` is decoration only (fails contrast as text); text-carrying colour is deep rose `#8A4A56`.
- Photos are fixed filenames in `assets/img/` (see `ASSETS.html`); a missing photo hides itself, so don't add placeholder images.
- `404.html` uses root-absolute links because GitHub serves it at any path; keep them that way.
- Pull before starting and before pushing: GitHub commits `CNAME` to `main` itself on domain day. Never force-push.
- The repo is public. Never commit client data, credentials or private documents.
- Don't create or edit `CNAME`, and don't suggest DNS changes; the domain cutover is a one-time step in `docs/OWNER-GUIDE.html` §7. Email DNS records (MX, SPF, DKIM) must never be touched.
- Square-bracket text like `[email]` is an unfilled placeholder, not literal copy.

How-tos for the owner live in `docs/OWNER-GUIDE.html`; keep it accurate when a change makes a step in it wrong.
