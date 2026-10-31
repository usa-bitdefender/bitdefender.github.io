# Bitdefender Antivirus Help Guides — GitHub Pages

This package contains the Bitdefender Antivirus article website, prepared for GitHub Pages.

## Files
- `index.html` — homepage with searchable article titles and title-based **Read Article** buttons.
- `articles/` — 100 individual article pages.
- `support.html` — separate support page with the **Contact Support** button.
- `.nojekyll` — helps GitHub Pages serve the static files as provided.

## Publish the site
1. Download and extract this ZIP on your computer.
2. Create a repository on GitHub, for example `bitdefender-help-guides`.
3. In the repository, choose **Add file → Upload files**.
4. Upload the extracted folder's contents, not the ZIP itself. Make sure `index.html`, `support.html`, `.nojekyll`, and the `articles` folder are at the repository root.
5. Click **Commit changes**.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, select **Deploy from a branch**.
8. Choose branch `main` and folder `/(root)`, then click **Save**.
9. Wait for GitHub Pages to publish the site. Open the URL shown in Settings → Pages.

## Button and link setup
- Each homepage article card has a **Read Article** button that opens its own HTML page.
- Each article page links back to the homepage and has an internal button to open `support.html`.
- The external contact destination is attached only to the inner **Contact Support** button on `support.html`.

This is an independent informational resource and is not the official Bitdefender website. Product instructions can vary by version and operating system; verify account and security matters through official resources.
