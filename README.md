# Vehicle Service & Estimation PWA

## Files
- `index.html` — the app
- `manifest.webmanifest` — install details and app icon declarations
- `sw.js` — service worker for offline caching
- `icons/` — 192px and 512px app icons

## Important: PWA needs HTTPS
A Progressive Web App cannot be installed from a normal `file://` HTML file. Host this folder on an HTTPS website (for example, GitHub Pages, Netlify, or your own HTTPS hosting).

## Easiest setup with GitHub Pages
1. Create/sign in to GitHub and create a new **public** repository.
2. Upload all files and folders from this ZIP (keep the folder structure).
3. In the repository, open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for the Pages URL to appear.
6. Open that HTTPS URL in Chrome on your Android phone.
7. Open Chrome menu (⋮) → **Install app** or **Add to Home screen**.

## Notes
- First open the hosted app while online so the service worker can cache the app shell and external styling assets.
- The estimate's WhatsApp button opens WhatsApp with the message pre-filled; the customer must still tap Send.
- Pricing and GST are editable/defined in the JavaScript. Confirm your workshop's actual prices and applicable tax treatment before using customer estimates.
- This is a browser-based PWA, not a Play Store APK.
