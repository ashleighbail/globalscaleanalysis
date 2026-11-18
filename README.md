# Global Scale Analysis

This repository contains Google Earth Engine scripts developed during the MB5370 global analysis module. The exercises explore how spatial datasets and JavaScript can support marine habitat mapping and research planning, and are often preferable to ArcGIS for spatial analysis.

Explore the interactive Earth Engine app, maps, results and workflow commentary from this module on my [MB5370 ePortfolio](https://sites.google.com/bail.id.au/mb5370/global-scale-analysis).

### Scripts

| File | Contents |
| --- | --- |
| `deep-ocean-ecosystems` | Maps potential deep-ocean ecosystems as part of the assessable content of this module. |
| `workshop1` | 'Getting started' workshop exercise. |
| `workshop1-2` | 'Filters and computation' workshop exercise. |
| `workshop3` | 'Nightlights in global coastlines' workshop exercise. |
| `workshop4` | Uses the Allen Coral Atlas to calculate mapped Coral/Algae habitat area, as part of the assessable content of this module. |

### Deep-ocean ecosystem mapping

The analysis uses the bedrock band of NOAA’s ETOPO1 global relief model to identify:

- Hadal trenches and troughs: deeper than 6,000 m.
- Abyssal plains: 3,000–6,000 m.
- Continental and island slopes: 250–<3,000 m.
- Potential submarine canyons: deeper than 200 m, with seabed slopes greater than 6°.

Marine Regions Exclusive Economic Zones provide maritime jurisdiction context. Marine and coastal protected areas from the World Database on Protected Areas are grouped by IUCN management category.

### Allen Coral Atlas analysis

The Allen Coral Atlas analysis compares mapped Coral/Algae habitat area within 400 m buffers around ten research locations.

Results represent the area of the combined Coral/Algae class, rather than live coral cover or reef condition. Zero values may reflect habitat distribution, dataset coverage or buffer placement.

### Citations

Allen Coral Atlas (2020). Imagery, maps and monitoring of the world's tropical coral reefs. Zenodo. doi:10.5281/zenodo.3833242

Amante, C. and B. W. Eakins, ETOPO1 1 Arc-Minute Global Relief Model: Procedures, Data Sources and Analysis. NOAA Technical Memorandum NESDIS NGDC-24, 19 pp, March 2009.

Flanders Marine Institute (2023). Maritime Boundaries Geodatabase: Maritime Boundaries and Exclusive Economic Zones (200NM), version 12. Available online at https://www.marineregions.org/. https://doi.org/10.14284/632

Frisk, S. (2016). Assassin’s Creed IV [Map style]. Snazzy Maps. https://snazzymaps.com/style/72543/assassins-creed-iv

International Union for Conservation of Nature. (n.d.). Global ecosystem typology. Retrieved November 17, 2026, from https://global-ecosystems.org/.

Keith, D. A., Ferrer-Paris, J. R., Nicholson, E., & Kingsford, R. T. (Eds.). (2020). IUCN Global Ecosystem Typology 2.0: Descriptive profiles for biomes and ecosystem functional groups. IUCN. https://doi.org/10.2305/IUCN.CH.2020.13.en.

UNEP-WCMC and IUCN (2026), Protected Planet: The World Database on Protected Areas (WDPA) [On-line], November 2026, Cambridge, UK: UNEP-WCMC and IUCN Available at: www.protectedplanet.net.
