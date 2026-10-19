# DésiTrue Services LLC website

Static marketing site for Désirée Truesdale's bookkeeping, admin-support and creative-marketing business, served by GitHub Pages from `main` / root. The owner is not a developer: explain changes in plain words, show a preview (Browser pane, phone and desktop width) and wait for her OK before committing or pushing.

Gotchas the files won't tell you:
- No build step, on purpose. Plain HTML + `css/site.css`; don't add a framework, bundler or npm.
- Header and footer are repeated in all four `.html` files. A change to either goes into every page.
- Brand tokens live in `:root` of `css/site.css`. Rose gold `#B76E79` is decoration only (fails contrast as text); text-carrying colour is deep rose `#8A4A56`.
- Photos are fixed filenames in `assets/img/` (slots and prompts in `docs/PHOTO-PROMPTS.md`; originals go in the git-ignored `incoming-photos/`); a missing photo hides itself, so don't add placeholder images.
- `404.html` uses root-absolute links because GitHub serves it at any path; keep them that way.
- Pull before starting and before pushing: GitHub commits `CNAME` to `main` itself on domain day. Never force-push.
- The repo and the site are both public. Never commit client data, credentials or private documents.
- Don't create or edit `CNAME`, and don't suggest DNS changes; the domain cutover is a one-time step in the owner guide (private repo `desitruellc/desitrue-website-guide`, section 7). Email DNS records (MX, SPF, DKIM) must never be touched.
- Search tags (canonical, og:url/og:image, JSON-LD, `sitemap.xml`) use absolute `https://desitrue.com/` URLs on purpose, ahead of the domain move. A new page needs the same head tags and an entry in `sitemap.xml`. `_config.yml` keeps internal Markdown (this file, CLAUDE.md, README.md, docs/PHOTO-PROMPTS.md) off the published site.
- Square-bracket text like `[email]` is an unfilled placeholder, not literal copy.

This file is the single set of rules for every AI assistant (Codex reads it directly; Claude Code reads it via CLAUDE.md). When the owner corrects you, add the rule here.

How-tos for the owner live in the private repo `desitruellc/desitrue-website-guide` (README.md and OWNER-GUIDE.html, kept in step). Keep it accurate when a change makes a step in it wrong.
