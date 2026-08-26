# Ferum - private fitness studio (Chelsea, London)

One-page site. Static, no build step.

## Files
- `index.html` - the page
- `support.js`, `image-slot.js` - runtime helpers (must stay next to index.html)
- `uploads/` - photos and the location map

## Local preview
Serve the folder over HTTP (opening the file directly can block script loading):

    python3 -m http.server 8000

Then open http://localhost:8000

## GitHub Pages
Push this folder to a repo, then Settings -> Pages -> Deploy from branch -> `main` / `/ (root)`.

## Contact data in one place
Phone, Instagram and the reviews toggle are props at the bottom of `index.html` (`data-props` + the `Component` class). Change the defaults there:
- phone: 020 7946 0192
- instagram: @ferum.studio
- address: 27 Kings Road, Chelsea, London SW3 4RP
