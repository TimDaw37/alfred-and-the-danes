# Alfred and the Danes, 865–899

Animated campaign map of the Danish wars in England, from the arrival of the Great Army in 865 to Alfred's death in 899.

Each step is keyed to its annal in the Anglo-Saxon Chronicle and, where relevant, to Asser's *Life of King Alfred*. Disputed sites (Ashdown, Meretun, Cynuit, Egbert's Stone, Iley, Ethandun) are shown with their alternative identifications; selecting a candidate redraws the routes and, for the 878 Edington march, the leg distances.

Live: https://timdaw37.github.io/alfred-and-the-danes/

Link to a step with its hash, e.g. `#step-878f` (Ethandun).

## Data

- Relief, higher-ground tint, low-ground mask and coastline: OS Terrain 50. Contains OS data © Crown copyright and database right 2026.
- Rivers: OS Open Rivers. Contains OS data © Crown copyright and database right 2026.
- Roman roads: Itiner-e, static version 2024 (de Soto et al.), Zenodo record 17122148.
- Coastline outside OS coverage: Natural Earth (public domain).
- Burhs: Burghal Hidage; positions approximate.

## Files

- `index.html` — page and map code (D3 v7 from cdnjs)
- `js/data.js` — sites, candidate identifications, steps, views, burhs, treaty line
- `js/geo.js` — coastline, rivers, Roman roads, raster metadata
- `img/` — hillshade, elevation tint, land and low-ground masks at three scales
