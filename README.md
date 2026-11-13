# Media Library information site

Public app information and privacy disclosures for the owner's private Media Library installation.

- Homepage: https://rayaana.github.io/media-library-info/
- Privacy policy: https://rayaana.github.io/media-library-info/privacy.html
- Contact: https://github.com/RayaanA/media-library-info/issues

This repository contains static information pages only. Application source, runtime data, credentials, private media, account inventories, and private service addresses belong outside this repository.

GitHub Pages publishes the `main` branch's root folder. No build or third-party frontend dependencies are needed. Edit the HTML/CSS and push to update the site. `.nojekyll` keeps the pages as plain static files.

Google Auth Platform Branding should use the app name **Media Library**, the operator's monitored support email, the homepage and privacy policy above, and the authorized domain **rayaana.github.io**. Keep the existing localhost OAuth callback in the private application's Web client. Publishing these information pages does not expose or host the private application.

If Google requests ownership verification, add a **URL-prefix** property for the homepage in Google Search Console using the Google account that owns the OAuth project. Use HTML-tag verification and add its exact `google-site-verification` meta tag to `index.html`, publish it, then click Verify. A verification tag is an ownership proof, not an OAuth client secret. Preserve it in later edits. A shared hosting domain cannot be verified with a DNS record you do not control.
