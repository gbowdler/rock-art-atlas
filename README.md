# World Rock Art Atlas

An interactive reference map of rock art sites around the world. It started after seeing Aboriginal rock art in Australia in the early 2000s, and grew into a way of exploring how motifs such as hand stencils, animal figures and hunting scenes recur across continents.

## What it does

- World map with real coastlines; tap a continent to zoom in
- Pinch, scroll or drag to pan and zoom within a continent
- Filter sites by motif: hand stencils, animals, human and spirit figures, hunting and ritual, geometric and abstract
- Each site has a region, a dating range, a short description, photo links and citations
- Sources and notes sit behind a "Sources & notes" button

## How to use it

It is a single self-contained file with no build step and no external dependencies. Open `index.html` in a browser, or view it through GitHub Pages once published.

## Data notes

- Dating for rock art is often contested and revised. Ages are given as reported ranges, not settled fact, and should be checked against the primary literature before relying on them.
- Photo links point to external galleries. Where only replica or facsimile photos exist (for example Lascaux or Altamira), the entry says so.
- The Dowth and Kerry entries were cross-checked against the National Monuments Service Prehistoric Art open dataset (Government of Ireland, CC BY 4.0, exported 2023). Only the record counts and a regional position were used. The Kerry marker is deliberately regional because many panels are fragile and on open land.
- The Franco-Cantabrian entries (Ekain, Santimamiñe, Cussac, Rouffignac, Trois-Frères) were chosen with help from Intxaurbe, I. (2026), *GIS dataset of Pleistocene and Early Holocene rock art, portable art and archaeological sites*, v1.2, Zenodo, [doi:10.5281/zenodo.18912270](https://doi.org/10.5281/zenodo.18912270) (CC BY 4.0). Only names and approximate positions were used. Pins are deliberately rounded because several caves are closed or fragile.
- Coastlines come from Natural Earth (110m, public domain), so they are accurate at world-map scale but not survey-grade.

## Licence

This project uses two licences, one for the code and one for the content:

- **Code** (the map, zoom and filter behaviour): MIT, see [LICENSE](LICENSE)
- **Content** (site descriptions, dating summaries, notes and this README): CC BY 4.0, see [LICENSE-CONTENT.md](LICENSE-CONTENT.md). Please credit "World Rock Art Atlas by gbowdler" with a link to this repository.

Third-party material is not covered by either licence. Photos, galleries and papers that the atlas links to stay with their owners, and the Natural Earth coastlines are public domain.
