# Gerrymander

A daily map-drawing puzzle. Carve a 5×5 island of 14 purple and 11 orange blobs into 5 contiguous districts of 5, so the outnumbered Orange wins 3 seats.

- **Play:** open `index.html` in a browser (single file, no build step). Works on GitHub Pages.
- **Daily puzzle:** seeded from the local date (#1 = 17 Nov 2026). Every puzzle is checked against all 4,006 possible maps, and only boards where 0.4–3% of maps are winning are used, so each one is hard but solvable.
- **Score:** *Suspicion* is how spread out your districts are (lower = tidier). Par is the tidiest winning map that exists.
- Sounds are synthesised with Web Audio, and your best daily result is saved in localStorage.
