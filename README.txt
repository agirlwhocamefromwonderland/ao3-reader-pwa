AO3 Reader — PWA

Files:
- index.html       Your reader, with PWA metadata + service-worker registration
- manifest.json    Home-screen app configuration
- sw.js             Offline app-shell cache
- icon-192.png     App icon
- icon-512.png     App icon

IMPORTANT:
A browser generally will not offer "Install app" for a local file (file://).
The app needs to be served from HTTPS (or localhost).

EASIEST WAY:
1. Put these files in a GitHub repository.
2. Enable GitHub Pages for the repository (Settings -> Pages -> Deploy from branch).
3. Open the resulting https://...github.io/... address in Chrome on Android.
4. Use Chrome's menu -> Add to Home screen / Install app.
5. After the first visit, the app shell can work offline.

Your actual books are NOT bundled into this app. Use the existing Open button to pick
your HTML/EPUB files from the phone, just as you do now.
