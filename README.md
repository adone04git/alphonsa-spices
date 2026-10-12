# ALPHONSA SPICES website

A responsive static website for GitHub Pages. No build process or paid hosting required.

## Before publishing
- Confirm the contact numbers and address in `index.html`.
- WhatsApp links currently use +91 79073 66078 (7907366078).
- Instagram is set to `@alphonsa.spices`.
- Photos load from Unsplash and fonts load from Google Fonts, so those features need an internet connection.
- Replace the image URLs with your own product/plantation images if desired.

## Publish on GitHub Pages
1. Sign in to GitHub and create a **public** repository, e.g. `alphonsa-spices`.
2. Upload all files and folders in this package to the repository root.
3. Open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. When the site is live, under **Settings → Pages → Custom domain**, enter `alphonsaspices.in` and Save.
5. At your domain registrar, set these DNS records:
   - A, host `@`, value `185.199.108.153`
   - A, host `@`, value `185.199.109.153`
   - A, host `@`, value `185.199.110.153`
   - A, host `@`, value `185.199.111.153`
   - CNAME, host `www`, value `YOUR-GITHUB-USERNAME.github.io` (replace with your actual GitHub username)
6. Return to Settings → Pages and enable **Enforce HTTPS** once available.

DNS changes can take up to 24 hours. Follow GitHub's official documentation: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Notes
- This is a static catalogue/marketing website, not an online checkout store.
- No hosting fee is required for a public GitHub Pages site. You still pay your domain registrar for the domain and renewals.
