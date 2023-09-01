# little picture - burned area in europe - bubblegraph

## Background on this little picture
_burned area in europe – an animated bubblegraph_

Monitoring wildfires from space is crucial for understanding their impact on climate, including the release of greenhouse gases &amp; aerosols that influence the Earth system.
This data-driven Little Picture uses satellite data to illustrate the annual pattern of burned area for European countries between 2001-2020. The size of each circle represents the burned area for the individual countries of Europe.

https://climate.esa.int/en/little-pictures-gallery/burned-area-bubbles/

## Data Sources

The CLIP uses the following datasets:

- [ESA Fire CCI: MODIS Fire_cci Burned Area Pixel product, version 5.1](https://catalogue.ceda.ac.uk/uuid/58f00d8814064b79a0c49662ad3af537), 
  Cate dataset identifier: `esacci.FIRE.mon.L4.BA.MODIS.Terra.MODIS_TERRA.v5-1.grid`.
- [cate.ds.data.countries/countries-110m.geojson](https://github.com/CCI-Tools/cate/blob/master/cate/ds/data/countries/countries-110m.geojson) 
  country polygons provided as public domain from [Natural Earth](https://www.naturalearthdata.com/).

## Data Preparation
For this clip the same dataset as the fire bubbles poster clip was used but converted into a json file. It is located in the data folder.

## Creating Visualisations
The clip uses an observable notebook for visualization. It can be accessed online under https://observablehq.com/@a-tack/burned_area_europe .
The code can also be viewed in the scripts folder of this repository.

## CREDITS & LICENSE
- Idea by: [Ubilabs](https://www.ubilabs.com/)
- Processing Scripts by: [Brockmann Consult](https://www.brockmann-consult.de/)
- Visualisation by: [Ubilabs](https://www.ubilabs.com/)

The code in this repository is published under [CC BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/)
