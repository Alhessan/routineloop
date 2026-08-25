# RoutineLoop — Public Site

Public landing page and privacy policy for the **RoutineLoop** Android app.

This repository exists only to host these pages via GitHub Pages, because the
main app repository is private (GitHub Pages is not available for private repos
on the Free plan).

## Live URLs

| Page | URL |
| --- | --- |
| Home | https://alhessan.github.io/routineloop-privacy/ |
| Privacy Policy | https://alhessan.github.io/routineloop-privacy/privacy-policy.html |

The Privacy Policy URL is the one registered in Google Play Console under
**App content → Privacy policy**. Do not rename or move `privacy-policy.html`
without updating Play Console — a 404 there blocks app review.

## Editing

Both pages are single self-contained HTML files (inline CSS/JS, no build step,
no local assets). The only external request is Google Fonts.

`privacy-policy.md` is the plain-text source of the policy, kept in sync for
reference.

Source of truth for edits lives in the private app repo under `docs/`; copy
changes here and push to `main` to publish.
