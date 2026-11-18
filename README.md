# Gerrymander

A daily map-drawing puzzle. Each day gets a new island split into 25 irregular precincts holding 14 purple and 11 orange blobs. Carve it into 5 contiguous districts of 5 precincts so the outnumbered Orange wins 3 seats.

- **Play:** open `index.html` in a browser (single file, no build step). Works on GitHub Pages.
- **Daily island:** seeded from the local date (#1 = 17 Nov 2026). It gets a random coastline, Voronoi precincts relaxed so they come out evenly sized, and a name. Every possible districting (usually 7k–50k of them) is enumerated, and only boards where 0.4–3% of maps are winning are used, so each one is hard but solvable.
- **Score:** *Suspicion* is how spread out your districts are (lower = tidier). Par is the tidiest winning map that exists.
- Sounds are synthesised with Web Audio, and your best daily result is saved in localStorage. "New practice island" gives unlimited random maps.
