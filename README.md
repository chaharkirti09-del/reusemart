# ReuseMart starter

A mobile-friendly marketplace prototype with:
- Responsive home page and category filters
- Search and price sorting
- Demo sell-item form with optional photo
- Saved items
- My listings
- Admin preview and JSON export
- PWA manifest and service worker

## Important limitations
This starter is a front-end demo. Data is stored in the current browser's localStorage, so listings do **not** sync between users or devices. There is no real authentication, secure admin, messaging, payments, or moderation yet. Do not use it for real transactions until a secure backend is connected.

## Run locally
Open `index.html` in a browser. PWA installation/service-worker support generally requires HTTPS or localhost.

## Publish a free test website
1. Create a GitHub account and a repository named `reusemart`.
2. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
3. Create a Netlify account and use **Add new site → Import an existing project** to connect the GitHub repository.
4. Deploy. Netlify will provide a free subdomain, subject to its current plan limits.
5. Open the HTTPS site in Android Chrome. Use the browser menu and choose **Install app** or **Add to Home screen** if offered.

## Next development stage
Connect a real backend such as Supabase (database, authentication, and image storage). Add server-side validation, access rules, admin roles, abuse reporting, and privacy safeguards before inviting public users.
