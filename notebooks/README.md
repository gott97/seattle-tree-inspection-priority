# Notebook workflow

Copy the six final ArcGIS Pro notebooks into this directory and retain a numerical prefix so the intended execution order is clear.

Recommended presentation:

| Order | Suggested filename | Purpose |
|---:|---|---|
| 1 | `01_download_data.ipynb` | Download the six public REST layers and prepare the project geodatabase |
| 2 | `02_qaqc.ipynb` | Clean and standardize the tree inventory, prepare DBH fields, derive maturity, and create simulated planning variables |
| 3 | `03_spatial_analysis.ipynb` | Calculate exposure indicators and attach Racial and Social Equity Index context |
| 4 | `04_priority_model.ipynb` | Apply the nine weights, calculate the index, assign classes, and select the top 5 percent |
| 5 | `05_reporting.ipynb` | Produce validation summaries, operational metrics, tables, and portfolio figures |
| 6 | `06_publish_agol.ipynb` | Package the final feature classes and publish or update ArcGIS Online layers |

The public copies use `SEATTLE_TREE_PROJECT_ROOT` when that environment variable is set. Otherwise, they use the current working directory, moving up one level when executed from the repository's `notebooks` directory.

Before publishing them:

- set `SEATTLE_TREE_PROJECT_ROOT` or run the notebooks from the repository root;
- remove saved credentials, tokens, usernames, and private service URLs;
- retain useful outputs such as record counts, validation tables, and compact charts;
- clear large exploratory outputs that make notebooks difficult to review;
- add a short purpose, inputs, outputs, and assumptions section at the top of each notebook;
- restart the kernel and run all cells in order where feasible.

