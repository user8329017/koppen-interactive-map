# Köppen Climate Atlas

An interactive world map of Köppen–Geiger climate zones (1991–2020 normals, 0.1° grid).

- **Click a code in the legend** to isolate that climate on the map (click a group heading to isolate the whole group).
- **Click anywhere on land** to isolate that spot's climate.
- **Search a city** to show every area that shares its climate.

Everything lives in a single `index.html` with the data embedded, so it runs with no build step or server. Open it in a browser, or host it with GitHub Pages.

## Data

- Climate: Beck, H. E. et al. (2023). High-resolution (1 km) Köppen-Geiger maps for 1901–2099 based on constrained CMIP6 projections. *Scientific Data* 10, 724. Resampled to 0.1°.
- Cities: [GeoNames](https://www.geonames.org/) (CC BY 4.0), places with population 30,000 and above.
