# CLIP - Fire Bubbles Cluster

## Background on this CLIP
This repository contains a Jupyter notebook that analyzes the Fire_CCI Burned Area data for European countries. The data represents the area of land that has been burned due to wildfires, and these measurements are taken from the MODIS instrument. It creates a bubble plot visualization that enables the viewer to interpret fire location and intensity over time.

## Data Sources

The CLIP uses the following datasets:

- [ESA Fire CCI: MODIS Fire_cci Burned Area Pixel product, version 5.1](https://catalogue.ceda.ac.uk/uuid/58f00d8814064b79a0c49662ad3af537), 
  Cate dataset identifier: `esacci.FIRE.mon.L4.BA.MODIS.Terra.MODIS_TERRA.v5-1.grid`.
- [cate.ds.data.countries/countries-110m.geojson](https://github.com/CCI-Tools/cate/blob/master/cate/ds/data/countries/countries-110m.geojson) 
  country polygons provided as public domain from [Natural Earth](https://www.naturalearthdata.com/).

## Data Preparation
For this clip the same dataset as the fire bubbles poster clip was used but converted into a json file. It is located in the data folder.

## Creating Visualizations
The clip uses an observable notebook for visualization. It can be accessed online under https://observablehq.com/@a-tack/burned_area_europe .
The code can also be viewed in the scripts folder of this repository.

## CREDITS & LICENSE
- Idea by: [Ubilabs](https://www.ubilabs.com/)
- Processing Scripts by: [Brockmann Consult](https://www.brockmann-consult.de/)
- Visualization by: [Ubilabs](https://www.ubilabs.com/)

The code in this repository is published under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
