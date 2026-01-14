# Chicago Park Accessibility Analysis
**Integrating Municipal and Crowdsourced Data**

## Overview
This project focuses on creating a unified park feature layer for Chicago by merging official municipal data with OpenStreetMap (OSM). 

## Technical GIS Workflow
1. **Geodetic Frameworks:** Projected OSM data from `GCS_WGS_1984` to `NAD_1983_2011_StatePlane_Illinois_East`.
2. **Data Integration:** Used **Arcade expressions** to fix 12-digit Census ID mismatches.
3. **Spatial Join:** Applied the `CLOSEST` operator to resolve spatial nulls between disparate datasets.
4. **Quality Control:** Validated data using **Topology Rules** (Must Not Overlap).

## Project Files
* [Download Final Poster] (./poster Dataintegration.pptx)
