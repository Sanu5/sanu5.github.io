# Mehfil · website

The public homepage, privacy policy and terms for the Mehfil apps, served by GitHub Pages at
**https://sanu5.github.io/** — the domain Google's OAuth consent screen, the App Store and Google Play link to.

- `index.html` — homepage · `privacy/` — privacy policy · `terms/` — terms of use · `style.css`, `icon.png`
- Plain HTML, no build step. Edit and push; Pages redeploys in about a minute.

## Search Console verification (once)
Google needs proof you own `sanu5.github.io` before it accepts it as an authorized domain:
1. [search.google.com/search-console](https://search.google.com/search-console) → **Add property → URL prefix** → `https://sanu5.github.io/` → Continue.
2. Choose **HTML tag**, copy the `<meta name="google-site-verification" …>` line.
3. Paste it into `index.html` where the comment says so, push, wait a minute, click **Verify**.
