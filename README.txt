CIVICTRACK AFRICA — WEB + INSTALLABLE PWA DEMO

FILES
- index.html: the app interface
- manifest.webmanifest: installable app metadata
- sw.js: service worker for caching/offline app shell on supported browsers
- icon.svg: app icon

LOCAL TEST
Open index.html in Chrome to test the demo features. Browser security rules do not allow service-worker offline caching from a file:// URL. To test installation/offline caching, publish the folder to an HTTPS host (for example Vercel or GitHub Pages), open the HTTPS URL in Android Chrome, then use Chrome menu > Add to Home screen / Install app.

IMPORTANT LIMITATIONS
This is a front-end prototype. Cases are stored in the current browser/device only. It does not provide shared multi-user data, real authentication, verified role permissions, a production database, secure agency separation, or government-grade security. Do not enter real confidential citizen or government information. The public indicators are local demo data only. Before government use, connect a secure backend, implement server-enforced access control, encryption, retention rules, audit logging, backups, incident response and an independent security review.

FOOTER BRANDING
Designed by Alhaji Abu Koroma
