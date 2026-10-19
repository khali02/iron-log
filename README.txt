IRON LOG — iPhone 6s workout tracker

WHAT IT IS
A small static offline-first web app. No account, subscription, database server or purchased domain. Workout records stay in this phone's local browser storage.

INSTALL (FREE GITHUB PAGES)
1. Create a free GitHub account if you don't have one.
2. Create a PUBLIC repository named iron-log.
3. Upload all files and the icons folder contents, preserving their paths (index.html, style.css, app.js, sw.js, manifest.webmanifest, icons/*).
4. In repository Settings > Pages, choose Deploy from a branch, main branch, / (root), then Save.
5. After publishing, open https://YOUR-USERNAME.github.io/iron-log/ in Safari on your iPhone 6s.
6. Tap Safari Share > Add to Home Screen > Add.
7. Launch Iron Log from the Home Screen while connected once; then it should work offline after caching.

IMPORTANT
- Do NOT open index.html directly in the Files app and expect Home Screen installation/offline caching. Use HTTPS hosting.
- GitHub Pages publicly hosts the app's CODE, not your workout records. Don't put personal records into the repository.
- Export backups in Settings and save them to Files/iCloud Drive. Browser data can be lost.
- If you update the app, reload online. Service worker updates may take an additional app restart.
- For dumbbell lifts, enter the weight of ONE dumbbell (kg per hand).
- Start with the Return phase; only switch to Main when recovery is stable.
- The calendar is a plan; the next core session is determined by completed core workouts. Missing days does not advance the rotation.
- No notifications, cloud sync or automatic Apple Calendar integration in v1.
