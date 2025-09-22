# Data & Access

Document datasets feeding our restoration interaction analyses. Include access notes so partners can reproduce or extend the work.

## Primary datasets
- **Colorado Wetland Monitoring Program (CWMP)** — Treatment history, vegetation structure, and hydrologic metrics for restoration sites. Accessible via CDSS portal; export subsets as GeoJSON for analysis.
- **NEON Acoustic & eDNA records** — Pollinator and amphibian detections near restoration reaches. Access through the [NEON API](https://data.neonscience.org/data-products/explore) using site IDs listed in our `data/` folder manifests.
- **iNaturalist pollinator observations** — Community contributions downloaded via the [iNaturalist export tool](https://www.inaturalist.org/observations/export) with project and taxon filters.

## Processed artifacts
- `data/cwmp_restoration_sites.geojson` — Cleaned polygons with treatment attributes and partner IDs.
- `data/pollinator_interactions.csv` — Aggregated visitation records aligned to restoration phases.
- `outputs/network_summary.csv` — Summary metrics produced by the `fired_time_hull_panel.ipynb` notebook.

## Storage locations
- **Working files:** tracked in GitHub when smaller than 50 MB.
- **Large rasters & raw exports:** upload to the [Group 12 CyVerse folder](https://de.cyverse.org/data/ds/iplant/home/shared/esiil/Innovation_summit/Group_12?type=folder&resourceId=b8511080-95a1-11f0-b0fb-90e2ba675364) using the [persistent storage instructions](instructions/save-to-persistent-storage.md).

## Data governance
- Confirm data-sharing agreements with partners before publishing derived products.
- Attribute community-sourced observations (e.g., iNaturalist) according to platform guidelines.
- Log any restricted datasets in `documentation/group-notes.md` with details on who has access.
