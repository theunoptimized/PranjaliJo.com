# Pranjali Joshi website

Complete static export of the current portfolio. No React, npm, or build step required.

## Replace your website
1. Upload index.html, favicon.svg, robots.txt, sitemap.xml, .nojekyll, and the assets folder to the folder GitHub Pages publishes. Upload the contents of this folder, not the enclosing folder.
2. Replace the existing index.html. README.md can remain repository documentation.
3. Keep the existing CNAME and custom-domain settings if pranjalijo.com already works. The supplied CNAME contains pranjalijo.com.
4. Under repository Settings > Pages, confirm the publishing branch and folder match where you uploaded the files. Use main and /(root) only if that is your intended publishing source.
5. Commit the files and wait for the Pages deployment to finish.

If your site uses a GitHub Actions build instead of branch publishing, place the files in that workflow's static publishing source.

## Photo
assets/pranjali-portrait.jpg is your supplied photo. Keep the folder and filename unchanged.

## Enquiries
The form submits to your existing Formspree endpoint xredbyvo. Launch-update requests are emails for you to manage manually, not an automatic newsletter service. Verify Formspree accepts submissions from pranjalijo.com in your account settings.

## Existing email
The site preserves thunoptimized@pranjalijo.com exactly as it appeared on your original website. Change all occurrences in index.html if that spelling is incorrect.

## External services
Fonts load from Fontshare; enquiries use Formspree. The photo and site code are hosted in your own repository. Test one real enquiry after deployment.

## Preview
Open index.html in a browser, or serve this folder using python3 -m http.server 8000.
