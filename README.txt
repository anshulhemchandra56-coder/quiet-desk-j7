QUIET DESK — NO. 01

A small, installable desk display for an older Android phone.

CONTENTS
- index.html: the dashboard
- manifest.webmanifest: install / home-screen settings
- service-worker.js: caches the dashboard so the app shell can open offline
- icon-192.png and icon-512.png: home-screen icons

RECOMMENDED INSTALLATION
1. Create a new public GitHub repository (for example: quiet-desk-j7).
2. Upload the five files in this folder to the repository's root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for GitHub Pages to publish the site. Open the published HTTPS address on the J7 Pro in Chrome.
7. In Chrome's menu choose Add to Home screen or Install app.
8. Launch Quiet Desk from the new home-screen icon.

FIRST-RUN SETUP
- Tap the gear and enter the town/city for weather.
- Add several photographs using the + button. Images are resized and stored in the browser's local IndexedDB database on the phone.
- Leave the phone in landscape orientation.
- Use the full-screen button if the browser window is not already immersive.

NOTES
- Clock, date and timer work without internet.
- Weather needs internet and uses Open-Meteo (no API key required); attribution is shown in the app.
- The installed app shell is cached for offline launch. Weather refreshes when internet is available.
- Do not clear Chrome site data for this page unless you are happy to remove its saved photo library and preferences. Keep the originals in your Gallery too.
- The page contains no account sign-in, analytics or third-party scripts.
