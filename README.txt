HUMA TRADERS Professional Pro — Android setup

FILES
- index.html: complete app interface and local business logic
- manifest.json: installable PWA metadata
- sw.js: service worker for caching on HTTPS hosting

ANDROID QUICK START (Acode)
1. Make a folder named huma-traders-pro.
2. Put all three files in the same folder.
3. Open index.html in Acode and preview it for basic testing.
4. For installation/offline caching, upload the folder to an HTTPS host (for example your existing Vercel project). Keep all three files at the same deployment root.
5. Open the HTTPS site in Chrome on Android, then Chrome menu > Add to Home screen / Install app.
6. Download a JSON backup from More > Backup / Export before clearing browser data or changing devices.

IMPORTANT
- This is a single-device local-storage edition; it does not sync between phones.
- The browser may clear local data; make backups regularly.
- The app starts with sample/demo products and customers. Edit/delete them and enter actual shop records before live billing.
- The app does not validate GST compliance or replace accounting/tax advice.
- Thermal printing depends on Android browser and printer compatibility. Test with a sample bill first.
- Purchase photo storage consumes browser storage. Keep photos small and back up regularly.
- Local browser storage is not encrypted by this app. Protect the phone and backup files.
