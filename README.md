# SDS_assignement


## **Environmental and spatial predictors of bird diversity across the United States: a route-based spatial analysis**


This is a code for the final assignement of [Spatial Data Science for Social Geography course](https://martinfleischmann.net/sds/)

A route-based analysis of bird species richness across the contiguous United States, using The North American Breeding Bird Survey (BBS) data - routes as the observational units and combination of environmental (NDVI) and spatial (elevation, LONG, LAT) predictors.


### Questions
- How vegetation quality/density/heterogeneity (NDVI) preditcs bird diversity across United States?
- How spatial predictors alone explains the patterns of speceis richness in North American birds?


### Tasks to cover

1. Prepare and explore the data -  clean BBS routes, extract NDVI for routes geometry and get elevation data with earth engine
2. Evaluate global and local spatial autocorrelation in species richness and model residuals
3. Build the OLS model and compare it with GWR model


### Data sources

BBS data (2018): https://www.sciencebase.gov/catalog/item/52b1dfa8e4b0d9b325230cd9

BBS routes geometry: https://earthworks.stanford.edu/catalog/stanford-vy474dv5024

NDVI (June 2018): https://neo.gsfc.nasa.gov/view.php?datasetId=MOD_NDVI_M&year=2018

elevation: https://earthengine.google.com/

US boundaries: https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html
