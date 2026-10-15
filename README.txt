LUTS CAD SERVICES — GitHub Pages website

FILES
- index.html: the website homepage (HTML, CSS and JavaScript are all included)
- assets/: logo and real project visuals cropped from LUTS CAD WORKS.pdf

PUBLISH ON GITHUB PAGES
1. Open your repository: https://github.com/lutscad-hub/lutscadservices.github.io
2. Upload index.html and the entire assets folder. Keep the assets folder beside index.html.
   Easiest method: use Add file > Upload files and drag in index.html and the assets folder's contents.
3. Commit the upload to the main branch.
4. Open Settings > Pages.
5. Under Build and deployment, select Deploy from a branch, branch main, folder /(root), then Save.
6. Wait a few minutes and visit https://lutscad-hub.github.io/lutscadservices.github.io/

IMPORTANT CONTACT FORM SETUP
The form currently prepares an email in the visitor's email app; it does not send messages directly or store submissions. In index.html, find:
const BUSINESS_EMAIL='YOUR_EMAIL@example.com';
Replace the placeholder with your real business email address before you expect enquiries. The displayed email in the contact section should also be updated to match.

The site is static and designed for free GitHub Pages hosting. No paid hosting or build tools are required.
