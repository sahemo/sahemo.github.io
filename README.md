# Sahemo portfolio

A static HTML and CSS portfolio and print-friendly résumé for Sabbir Ahmed Hemo. No build command, package installation, or API key is needed.

- `index.html` is the portfolio.
- `resume.html` is the résumé. Use the Print / Save PDF button to open the browser’s print dialog.
- `styles.css` styles both pages. Google Fonts is optional and has local font fallbacks.

## Preview locally

Extract the ZIP and open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a public repository named `sahemo.github.io` under the `sahemo` account, or use an existing repository intended for the portfolio.
2. Commit the contents of this folder to the root of the `main` branch, including the hidden `.nojekyll` file.
3. In repository **Settings → Pages**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. When the Pages deployment finishes, open the published URL shown in the settings. For the account site it is `https://sahemo.github.io/`.

## Use the domain

Once the GitHub Pages site is working, follow GitHub’s domain verification steps, then add the domain in the repository’s **Settings → Pages → Custom domain**. To use `www.sahemo.dev`, set the Namecheap CNAME for host `www` to `sahemo.github.io`. For the apex `sahemo.dev`, follow GitHub’s apex instructions and check for pre-existing website records before replacing them. Keep the email MX, SPF and DKIM records. Enable **Enforce HTTPS** when GitHub makes it available.

[GitHub Pages quickstart](https://docs.github.com/en/pages/quickstart) · [Verify a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/verifying-your-custom-domain-for-github-pages) · [Configure a custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
