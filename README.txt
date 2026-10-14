12-WEEK HYPERTROPHY TRACKER — PWA PACKAGE

FILES
- index.html: the app
- manifest.webmanifest: install metadata
- sw.js: offline cache service worker
- icon-192.png / icon-512.png: app icons

HOW TO USE
1. Extract the ZIP to a folder.
2. Host the contents on any static HTTPS host (for example, GitHub Pages, Netlify, or another static web host). Keep all files in the same folder.
3. Open the HTTPS URL in Safari on your iPhone.
4. Tap Share, then Add to Home Screen.
5. Launch the Home Screen icon. The app caches its files for offline use after the first successful load.

DATA & BACKUPS
Workout sessions, set entries, settings, and bodyweight records are stored in localStorage in the browser on that device. They do not automatically sync to another device. Use Settings > Export full backup regularly, and import that JSON backup on another device to restore it. CSV export is available for workout logs.

NOTES
- This is a client-side PWA; no account or server database is included.
- Browser storage can be cleared by the user or operating system. Export backups regularly.
- For installability and service-worker offline caching, serve over HTTPS (localhost is also supported for development). Opening index.html directly as a file is suitable for a quick preview but does not enable PWA installation or service-worker caching.
