### tx_shorelines

Early code to look at Texas shoreline data.

Data is from https://cmgds.marine.usgs.gov/data-releases/datarelease/10.5066-P1WFZXDM/

`shoreline_stats.ipynb` - First set of code to read and process shorelines...not very well organized...lots of analyses tacked on to the bottom.

`preprocess_shorelines.ipynb` - Refactored version that does pre-processing and saves the output so later analysis can be separated.  

`loess_analysis_v1.ipynb` - First attempt at seasonal analysis  

`export_TX_to_DSAS.ipynb` - Reads preprocessed shorelines and generates `.geojson` files that DSAS can read.  

`explore_DSAS_geojason.ipynb` - Reads some example `.geojson` files exported from DSAS to use in prompts that generated `export...`  

### Other files

`TX_transect_tidally_corrects.asv` - Source data from USGS data release.  

`place_names_with_latlon.csv` - Location of selected place names for labelling figures.   

`ibtracs.NA.list.v04r01.csv` - Tropical cyclone database for North America.

