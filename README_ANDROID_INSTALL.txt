SMALL BUSINESS PROFIT TRACKER — ANDROID INSTALLABLE PWA PACKAGE

WHAT THIS PACKAGE IS
This folder contains the mobile web app, a web-app manifest, app icons, and a service worker that caches the app so its main screen can load offline after the first successful online visit.

IMPORTANT: THIS PACKAGE IS NOT YET HOSTED
Android's normal “Install app” / “Add to Home screen” experience requires the app to be served from a secure HTTPS website (localhost is allowed for development). Simply opening index.html from Downloads will not register the service worker and will not provide the full installable PWA experience.

HOW TO INSTALL ON AN ANDROID PHONE AFTER HOSTING
1. Upload all files and folders in this package to the same HTTPS website location. Keep index.html, manifest.json, service-worker.js and the icons folder together.
2. On Android, open that HTTPS address in Chrome while online.
3. Open Chrome's menu (⋮), then choose “Install app” or “Add to Home screen” if shown.
4. Launch Profit Tracker from the new home-screen icon.
5. While still online, open the app once and wait for it to load completely. Then test airplane mode to verify offline loading.

DATA AND PRIVACY
- Sales and expense records are saved in browser localStorage on that device.
- The service worker caches the app files, not a cloud copy of your records.
- Records do not synchronise to another phone or computer.
- Use Settings > Back up records regularly and store the backup safely.
- Test all calculations and backups with sample records before using it for real business accounts or distributing it to customers.

FILES
index.html             Mobile app
manifest.json          Install name, appearance and app icons
service-worker.js      Offline app-file cache
icons/                 Android app icons
