---
layout: default
title: Chicago Park Accessibility Analysis
---

# Integrating Municipal and Crowdsourced Data to Create a Unified Park Feature Layer
**Author:** Image Bhattarai  

## Project Output
Below is the map showing the integrated park feature layer for Chicago.

![Chicago Park Map](./output/output_)

---

## Technical Methodology
* **Geodetic Frameworks:** Re-projected OSM data from `GCS_WGS_1984` to `NAD_1983_2011_StatePlane_Illinois_East`.
* **Standardization:** Utilized **Arcade Expressions** to resolve 12-digit Census ID mismatches.
* **Spatial Integration:** Applied the **CLOSEST** spatial join operator to ensure 100% attribute coverage across the unified layer.
* **Quality Control:** Validated vector integrity using **Topology Rules**.

---
