# Work in progress — 3D bureau

Statische three.js-pagina, geschikt voor GitHub Pages.

## Publiceren
1. Zet `index.html` en `three-d-stage.js` in de root van een repository.
2. Ga naar **Settings → Pages**, kies *Deploy from a branch*, branch `main`, map `/ (root)`.
3. De pagina staat daarna op `https://<gebruiker>.github.io/<repo>/`.

three.js wordt via een import map van unpkg geladen; er is geen build-stap nodig.
