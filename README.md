# minerals.ma — website starter

A responsive static website starter for Morocco's mining and minerals industry.

## Files
- `index.html` — homepage and page sections
- `assets/style.css` — responsive visual design
- `assets/script.js` — mobile navigation, listing filters and email inquiry form

## Preview locally
Open `index.html` in a browser.

## Deploy with Cloudflare Pages and GitHub
1. Create a GitHub repository named `minerals-ma`.
2. Upload the contents of this ZIP to the repository root. The `index.html` file must be at the top level, not inside another folder.
3. In Cloudflare, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
4. Select the `minerals-ma` repository and branch `main`.
5. For a plain static site, choose **None** as the framework preset. Leave the build command empty and set the build output directory to `/` (if the dashboard rejects `/`, use `.`).
6. Deploy. Cloudflare will provide a `pages.dev` preview address.
7. In the Pages project, open **Custom domains** and add `minerals.ma`. Add `www.minerals.ma` too if you want the www version.

## Before public launch
- Replace the sample/demo marketplace cards with real, permissioned listings.
- Confirm the email address `hello@minerals.ma` exists, or change it in `assets/script.js`.
- Add real company contact details, privacy policy and terms.
- Add French and Arabic translations if launching multilingual.
- Add a backend/database before enabling user accounts, listing submissions, document rooms or messaging.

## Important
This is a static front-end starter. The contact form opens the visitor's default email application; it does not store or send form submissions to a server. Demo listings are clearly marked as illustrative and must not be represented as verified offers.
