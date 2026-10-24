# Scout Vision Labs — GitHub Pages Website

## Upload
1. Create a **public** GitHub repository (for example `scoutvisionlabs-website`).
2. Upload the **contents of this folder** to the repository root (not the enclosing folder).
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, `main`, `/(root)`, and Save.
4. Set your custom domain to `scoutvisionlabs.site` under **Settings → Pages**. The included `CNAME` file already declares it.
5. At your DNS provider, configure apex A records for GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`; optionally add a `www` CNAME to `<your-github-username>.github.io` (replace the placeholder with your actual username). Follow GitHub's current Pages documentation and remove conflicting records only after reviewing them.
6. After DNS resolves, enable **Enforce HTTPS** in Pages settings when available.

## Routes
- `/` — Home
- `/about` — About Us
- `/privacypolicy` — Privacy Policy
- `/contact` — Contact Us

The route folders contain `index.html`, so GitHub Pages supports clean URLs (it may canonicalize them with a trailing slash).

## Before publishing
- Set up and test `contact@scoutvisionlabs.site` (placeholder mailbox used throughout).
- Review all company statements and privacy disclosures for accuracy.
- This privacy policy describes the website only, **not your mobile games**. Publish accurate game-specific policies as required.
- If you change the domain, update the CNAME file, page links, and email addresses.
