- `Title`: US Congressional Districts 2023
- `Abstract`: Alabama congressional districts for the 2024 election. 
- `Spatial Coverage`: Alabama OSM:[161950](https://www.openstreetmap.org/relation/161950)
- `Spatial Resolution`: congressional districts
- `Spatial Reference System`: EPSG: 3857, NAD 1984 Web Mercator projection
- `Temporal Coverage`: districts approved in 2023 for use in 2024.
- `Temporal Resolution`: annual election (2020)
- `Lineage`: Loaded into QGIS as ArcGIS feaure service layer and saved in geopackage format. Extraneous data fields were removed and the `FIX GEOMETRIES` tool was used to correct geometry errors.
- `Distribution`: Alabama State GIS [via ESRI feature service](https://services7.arcgis.com/jF2q3LPxL7PETdYk/arcgis/rest/services/2023_Court_Ordered_Congressional_Plan/FeatureServer/)
- `Constraints`: Public Domain data free for use and redistribution.
- `Data Quality`: State any planned quality assessment
- `Variables`: For each variable, enter the following information. If you have two or more variables per data source, you may want to present this information in table form (shown below)
  - `Label`: variable name as used in the data or code
  - `Alias`: intuitive natural language name
  - `Definition`: Short description or definition of the variable. Include measurement units in description.
  - `Type`: data type, e.g. character string, integer, real
  - `Accuracy`: e.g. uncertainty of measurements
  - `Domain`: Expected range of Maximum and Minimum of numerical data, or codes or categories of nominal data, or reference to a standard codebook
  - `Missing Data Value(s)`: Values used to represent missing data and frequency of missing data observations
  - `Missing Data Frequency`: Frequency of missing data observations: not yet known for data to be collected

| Label | Alias | Definition | Type | Accuracy | Domain | Missing Data Value(s) | Missing Data Frequency |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| DISTRICT | ... | US Congressional District Number | ... | ... | ... | ... | ... |
| POPULATION | ... | total population (2020 census) | ... | ... | ... | ... | ... |
| WHITE | ... | total white population (2020 census) | ... | ... | ... | ... | ... |
| BLACK | ... | total Black or African American population (2020 census) | ... | ... | ... | ... | ... |