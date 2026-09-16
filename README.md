# Ferrum - one-to-one personal training, Chelsea, London

One page. Static, no build step. Only external dependency: Google Fonts.

## Files
- `index.html` - the page (SEO head, schema.org data, all styles inline)
- `support.js` - runtime helper, must stay next to index.html
- `img/` - WebP photos and the location map
- `robots.txt`, `sitemap.xml`

## Before going live
Replace `https://ferrum.london/` with the real domain in three places:
1. `index.html` - canonical, og:url, og:image, schema.org `url`/`image`
2. `robots.txt` - the Sitemap: line
3. `sitemap.xml` - the `<loc>` value

## Still to fill in
- Trainer names, qualifications and real portrait photos (current images are placeholders, marked as such in their alt text)
- Prices in GBP for the 4 / 8 / 12 session packages

## Local preview
    python3 -m http.server 8000

## GitHub Pages
Push everything to the repo root, then Settings -> Pages -> Deploy from branch -> `main` / `/ (root)`.

## Contact details
Set in the `Component` class at the bottom of `index.html`:
- phone 020 7946 0192 · email hello@ferrum.london · instagram @ferrum.studio
- address 27 Kings Road, Chelsea, London SW3 4RP
