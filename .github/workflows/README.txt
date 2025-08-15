
Workout Tracker PWA (Progressive Web App)
=========================================

Files
-----
- index.html     : the app
- manifest.json  : PWA manifest (lets iOS/Android install to Home Screen)
- sw.js          : service worker for offline caching
- icon-192.png / icon-512.png : app icons (placeholders; optional)

How to run locally
------------------
You can open index.html directly in a browser. For full PWA behavior, serve with any static host
(GitHub Pages, Netlify, Vercel).

iPhone install
--------------
1) Deploy to a static host (e.g., Netlify drag-and-drop).
2) Open the site in Safari on iPhone.
3) Share button → Add to Home Screen.
4) It will open fullscreen and work offline.

Progressive overload
--------------------
- Enter sets as you train (exercise, reps, weight). The app groups sets by exercise.
- It compares the current "top set" (highest weight, tie-breaker reps) to your last session
  of the same exercise:
    📈 means improved (weight or reps), → same, 📉 decreased, 🆕 new exercise.
- History shows per-exercise trend vs your previous workout.

Backup
------
- Use Export to download a workouts.json backup.
- Use Import to restore from that file.
