# Code & Workflows

This page tracks runnable assets that support our analysis of restoration-driven species interactions. Link to notebooks, scripts, and key results so teammates and partners can reproduce our steps.

## Notebooks
### `code/fired_time_hull_panel.ipynb`
- **Purpose:** Prototype workflow for comparing interaction network density between restored and reference wetland reaches.
- **Inputs:**
  - `data/cwmp_restoration_sites.geojson`
  - `data/pollinator_interactions.csv`
- **Run it:** Launch in JupyterLab (CyVerse or local) and execute cells top-to-bottom. Requires `pandas`, `geopandas`, `networkx`, `matplotlib`.
- **Outputs:** Generates `assets/results/network_density_panel.png` and summary tables saved to `outputs/network_summary.csv`.

### `code/prism_quicklook.py`
- **Purpose:** Pulls PRISM precipitation summaries for restored catchments to explore hydrologic context for species interactions.
- **Usage:**
  ```bash
  python code/prism_quicklook.py --site-inventory data/cwmp_restoration_sites.geojson --start 2020-01-01 --end 2024-12-31
  ```
- **Notes:** Writes daily precipitation aggregates to `outputs/prism_precipitation.csv`. Optional `--plot` flag saves a quicklook figure to `assets/results/prism_trend.png`.

### `code/single_hull_demo.py`
- **Purpose:** Minimal example that calculates the convex hull of field observations; used for testing spatial joins and geometry utilities.
- **Run it:**
  ```bash
  python code/single_hull_demo.py --observations data/sample_observations.geojson
  ```
- **Outputs:** Saves `outputs/single_hull.geojson` and prints hull area statistics.

## Documentation & strategy notes
- `code/data_processing.md` — checklist for pulling, staging, and processing spatial + community-science datasets.
- `code/data_analysis.md` — outlines analytical questions and methods still in progress.
- `code/visualizations.md` — storyboard for visuals we want to produce for the final share-out.

Add new scripts or notebooks here as they come online so mentors and reviewers know what to test.
