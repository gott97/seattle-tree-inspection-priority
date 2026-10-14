# Data sources and attribution

The analysis uses publicly available City of Seattle geospatial data. Dataset names, service schemas, and update schedules may change; verify the current item metadata before rerunning the workflow.

## Source categories

| Source | Publisher | Role in the analysis |
|---|---|---|
| [Seattle Parks and Recreation Tree View](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/arcgis/rest/services/SPR_Tree_View/FeatureServer/0) | City of Seattle | Tree locations and available species, site, and diameter attributes |
| [Seattle Streets](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/arcgis/rest/services/Seattle_Streets_1/FeatureServer/0) | City of Seattle / Seattle Department of Transportation | Street network and arterial classifications |
| [Sidewalks](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/arcgis/rest/services/Sidewalks_CDL/FeatureServer/0) | City of Seattle / Seattle Department of Transportation | Pedestrian exposure context |
| [Seattle Parks and Recreation Trails](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/arcgis/rest/services/SPR_Trails/FeatureServer/0) | City of Seattle | Recreational-access context |
| [Seattle Schools](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/arcgis/rest/services/Seattle_Schools/FeatureServer/8) | City of Seattle | School-proximity context |
| [Race and Social Equity Composite Index](https://services.arcgis.com/ZOyb2t4B0UYuYNYH/ArcGIS/rest/services/Race_and_Social_Equity_Composite_Index_Current/FeatureServer/0) | City of Seattle | Neighborhood-level equity context |
| Basemap and reference layers | Esri and contributing data providers | Web-map orientation and reference context |

## Access

- [Seattle GeoData open-data portal](https://data-seattlecitygis.opendata.arcgis.com/)
- [City of Seattle Open Data](https://data.seattle.gov/)

The service endpoints above are the URLs used by `01_download_data.ipynb`. Record the access date and review the current item license before publishing a new release because City service schemas and availability can change.

## Attribution statement

> Tree inventory, transportation, infrastructure, environmental, and Racial and Social Equity Index data were obtained from the City of Seattle and Seattle Open Data. Basemap and reference content were provided by Esri and contributing data providers. Analysis, modeling, maps, dashboard, visuals, and narrative were created by Ava Gotthard.

## Redistribution

This repository does not redistribute the complete source datasets. Each source remains subject to the license and terms shown on its authoritative item page. Derived outputs should retain appropriate source attribution and should not be represented as official City of Seattle products.

