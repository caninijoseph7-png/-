TAKOYONKE PWA — GITHUB PAGES PACKAGE

Files:
- index.html: your Takoyonke app
- manifest.webmanifest: installable-app settings
- sw.js: service worker for offline app-shell caching
- icon-192.png and icon-512.png: install icons

PUBLISH:
1. Extract this ZIP.
2. Create a new GitHub repository (Public is simplest for GitHub Pages).
3. Upload the CONTENTS of this folder to the repository root, not the ZIP itself.
4. In GitHub, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for deployment, then open the Pages URL on your phone.
8. In Chrome on Android, use the browser menu > Install app (or Add to Home screen).

NOTES:
- The app registers sw.js and references manifest.webmanifest and icon-192.png.
- App records and theme preferences are stored in browser localStorage on that device/browser.
- This package does not create cloud sync or a native Play Store APK.
- Keep the app's backup/export feature enabled in your routine; browser data can be lost if site data is cleared.
