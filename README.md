# AtoZHandicrafts — Website (GitHub Pages)

This repository contains the static website for A to Z Handicrafts.

Public site (after enabling GitHub Pages):
- https://kumawatpriyanshi44-blip.github.io/AtoZHandicrafts/

How to publish (quick):
1. Go to your repository Settings → Pages.
2. Under "Source", select the branch `main` (or whichever branch you use) and the root (/ ) folder, then Save.
3. Wait a few minutes — the site will be available at the URL above.

Short link options (two choices — external and self-hosted):

- Option A — External shortener (fast, recommended):
  - Use a service like TinyURL or Bitly to create a short alias that redirects to the Pages URL above.
  - Steps (TinyURL):
    1. Go to https://tinyurl.com/create
    2. Paste the GitHub Pages URL and choose a custom alias (for example `atozhandicrafts`) if available.
    3. Create the short link and copy it for sharing.

- Option B — Self-hosted short redirect (keeps everything under your GitHub Pages domain):
  - This repo includes `short.html` at the repository root. When the site is published, the URL
    `https://kumawatpriyanshi44-blip.github.io/AtoZHandicrafts/short.html` will immediately redirect to the main site.
  - If you prefer a cleaner path like `/s`, you can create a folder `s/` and put an `index.html` redirect there.

Files added in this commit:
- `README.md` — contains publishing instructions and short-link options
- `short.html` — a 0-second meta-refresh redirect to the GitHub Pages site

Security note:
- The site currently uses a client-side prompt with a hard-coded password for the Owner Panel (in `index.html`). This is not secure. If you plan to accept updates through the site, move owner/admin actions to a secure server-side admin interface or remove the owner panel from the publicly accessible site.

If you want me to use a different branch than `main`, or to add a `/s/index.html` alias instead of `short.html`, tell me and I will update the commit.
