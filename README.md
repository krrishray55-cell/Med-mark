# Medimark Pharmacy & Clinic website

Static website (HTML + CSS). No build step, no dependencies.

## Files
- `index.html` – the page
- `css/style.css` – all styling
- `images/storefront.jpg` – storefront photo (the only photo on the site)
- `images/logo.png`, `images/favicon.png` – logo

## Publish on GitHub Pages
1. Open your repository (e.g. `MedfriendPharmacy-`), click **Add file > Upload files**.
2. Upload everything in this folder so `index.html` sits at the top level, with the `css` and `images` folders. Replace the old files and commit.
3. Go to **Settings > Pages**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and Save.
4. The site goes live in a minute or two at `https://<username>.github.io/<repo>/`.

## To update later
- Phone, email and address: edit `index.html` (search for `tel:` and `mailto:`).
- Doctor details: edit the `doc` blocks in `index.html`.
