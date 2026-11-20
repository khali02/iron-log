IRON LOG v4.8 — Flexible Training + Nutrition Quick Add

INSTALL
1. Export your workout and nutrition backups from Iron Log first.
2. In your existing GitHub Pages Iron Log repository, replace these five files at the repository root:
   app.js, nutrition.js, nutrition.css, index.html, sw.js
3. Do NOT delete style.css, manifest.webmanifest, or icons/ from your repository.
4. Commit, wait for GitHub Pages to deploy, then fully close/reopen the iPhone Home Screen app. If needed reload twice to refresh the service worker.
5. Your local workout/nutrition data is not overwritten by this patch. Back up before updating anyway.

CHANGES
- Exercise-specific units: kg, lb, machine level, unmarked setting, bodyweight/assisted. Values are not silently converted.
- Add working sets and drop sets; remove last set.
- Add/replace/remove exercises during training. New exercise names can be saved in a custom exercise library.
- For workout changes, choose whether to persist them to the weekly plan. Today's workout only is the default.
- Nutrition: faster food library with favorites, recently logged foods and collapsed custom-food editor. Existing saved meals and offline foods retained.
- Updated service worker cache version.

LIMITATIONS
- Exercise selection currently uses a compact native name-search dialog, not a full graphical library screen.
- Online nutrition database is NOT connected: there is no configured API/provider. Built-in offline food database and custom foods remain available.
- The existing food estimates are indicative, not a verified nutrition database.
- Unit changes are blocked once weight values exist in that exercise session to avoid corrupting historical unit meanings.
- Drop sets are labeled, but the existing progress graphs have not yet been redesigned to separate drop-set volume.
- Existing workouts in the backup retain their original units unless manually corrected in a future migration.
- Browser/device QA on iPhone 6s has not been performed; JS syntax and ZIP integrity were checked.
