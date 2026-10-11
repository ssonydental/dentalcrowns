# dentalcrowns.ssonydental.com

Static crowns & bridges landing page for Smile Services of New York.

## Deploy with GitHub Pages
1. Create a new repo (e.g. `ssonydental/ssny-crowns`) and upload every file in this folder to the root (keep the `assets/` folder and the hidden `.nojekyll` file).
2. Settings > Pages > Source: Deploy from a branch > `main` / `/ (root)` > Save.
3. In your DNS, add a CNAME record: `crowns` -> `ssonydental.github.io`.
4. Settings > Pages > Custom domain: `dentalcrowns.ssonydental.com`, then tick Enforce HTTPS once the certificate is issued.

The `CNAME` file in this folder keeps the custom domain set across deploys.

## Still to fill in (search index.html)
- Privacy Policy URL (search "fill in")
- Three real Google reviews (reviews section placeholders)
- Real photos: `assets/hero-smile.jpg` (also used for og:image) and `assets/band-craft.jpg`

## After go-live
- Confirm https://dentalcrowns.ssonydental.com/ loads with the padlock, then submit the sitemap in Google Search Console.
- Verify GTM-MRQ3RPBM fires and the quiz pushes to dataLayer.
