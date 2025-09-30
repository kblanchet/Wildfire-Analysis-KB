**Wildfire Landslide Risk Analysis — Palisades**



**Overview**



This repository contains the workflow and results for a wildfire‑related landslide risk analysis in the Pacific Palisades fire area.

The project integrates burn severity, slope, and watershed boundaries to produce a weighted risk surface and interpret susceptibility across sub‑basins.



**Contents**

\- Wildfire\_LandslideRisk.pdf — Final report with maps, captions, and interpretation.

\- notebooks/ — Jupyter Notebook(s) documenting the reproducible workflow.

\- data/ — References to input datasets.

\- docs/ — Supporting figures or exported outputs.



**Interactive Map**

Explore the results in ArcGIS Online:



**Instant App (Sidebar)**

This app displays the weighted risk raster with sub‑basin overlays and sidebar interpretation.



**Methods Summary**

\- Inputs:

\- Burn severity raster (post‑fire)

\- Slope raster (derived from DEM)

\- Fire perimeter (authoritative REST service, see below)

\- Sub‑basin boundaries

\- Processing:

\- Normalized rasters to 0–1 scale

\- Applied weights to combine burn severity and slope

\- Generated final risk surface raster

\- Overlaid sub‑basins for watershed‑level interpretation

\- Outputs:

\- Weighted risk raster (0 = low, 1 = high)

\- Sub‑basin overlays highlighting areas of highest susceptibility

\- Interactive Instant App for exploration



**Data Sources**

\- USGS DEM

\- USFS Burn Severity Data

\- Watershed/Sub‑basin Boundaries

\- Fire Perimeter: Palisades and Eaton Dissolved Fire Perimeters as of 2025‑01‑21.

Hosted by Los Angeles County Fire Department via ArcGIS Online.

Accessed at: https://services.arcgis.com/RmCCgQtiZLDCtblq/arcgis/rest/services/Palisades\_and\_Eaton\_Dissolved\_Fire\_Perimeters\_as\_of\_20250121/FeatureServer



**Notebook Access**



You can view the full analysis notebook here: 

https://github.com/kblanchet/Wildfire-Analysis-KB/blob/main/Notebooks/Wildfire-Analysis-Palisades.ipynb

