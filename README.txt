Daily Compass PWA — starter version

Files:
- index.html: app interface and tracking logic
- manifest.webmanifest: installable PWA metadata
- sw.js: offline cache service worker
- icon.svg: app icon

How to use:
1. Upload the contents of this folder to an HTTPS static host (for example, GitHub Pages or Netlify).
2. Open the hosted URL in Chrome on Android.
3. Use Chrome menu (⋮) → Install app / Add to Home screen.
4. Open the installed app. Your data is stored locally in that browser on that device.
5. Use Settings → Export my data regularly for a backup.

Important:
- The app is a first-version local prototype. It does not sync across devices.
- The service worker and installation require HTTPS (or localhost for development).
- Prayer times are editable estimates; adjust them when your masjid changes its Jamaat schedule.
- Schedule templates are flexible guides, not alarms or rigid commitments.
