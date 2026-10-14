# Data directory

The full source and derived datasets are not stored in this repository. They are omitted to avoid duplicating authoritative public services, committing large geospatial files, and redistributing third-party content outside its original terms.

## Obtaining the inputs

Download or connect to the datasets documented in [`../docs/data_sources.md`](../docs/data_sources.md). Record the download date and retain the original files unchanged before running the preparation workflow.

A suggested local structure is:

- `data/raw/trees/`
- `data/raw/transportation/`
- `data/raw/trails/`
- `data/raw/sidewalks/`
- `data/raw/waterways/`
- `data/raw/equity/`
- `data/intermediate/`
- `data/processed/`

These folders are ignored by Git. Update the notebook configuration variables to point to the corresponding local locations.

## Sample data

A small representative sample may be added later under `data/sample/` if its source license permits redistribution. A sample should preserve the fields needed to demonstrate the workflow but should not be presented as suitable for reproducing the published citywide results.

