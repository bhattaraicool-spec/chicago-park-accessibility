# Chicago Park Accessibility Analysis

This project presents an applied GIS workflow for integrating official municipal park data with OpenStreetMap features to create a unified park dataset for Chicago. The goal was to support urban green space accessibility analysis by improving data consistency, resolving mismatches between sources, and preparing a cleaner feature layer for equity-focused mapping.

## Project Overview

Chicago park information was compiled from multiple sources that differed in geometry quality, attribute structure, and spatial coverage. In ArcGIS Pro, these datasets were standardized and merged into a single park feature layer that could be used for analysis and visualization.

## Workflow Highlights

- Reprojected source datasets into a common coordinate system for spatial consistency.
- Integrated municipal park data with OpenStreetMap park features.
- Reconciled attribute differences using tabular joins and field standardization.
- Applied quality control steps to identify gaps, overlaps, and mismatched features.
- Organized outputs in a geodatabase for cleaner data management and reproducibility.
- Produced a final map relating park distribution to median household income.

## Tools Used

- ArcGIS Pro
- Geoprocessing tools for projection, joins, and feature integration
- Arcade expressions for attribute cleanup
- Spatial joins and validation workflows
- Geodatabase design for structured storage

## Why This Project Matters

This project demonstrates more than cartography. It shows practical GIS problem-solving: harmonizing inconsistent data sources, improving feature quality, and preparing analysis-ready data for urban equity applications. The final output supports exploration of how park access and green space distribution vary across neighborhoods.

## Output

The final deliverable is a unified park dataset and map product showing the distribution of Chicago parks in relation to demographic context, with emphasis on accessibility and underserved areas.
