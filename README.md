## Coverage analysis tool for optical data
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Module using the `sepal_ui` framework and an interactive **Voila** dashboard to create maps of cloud-free observations for major optical satellites as available on Google's Earth Engine Platform.
The framework follows themain ideas from bfasts' countObs and summaryBrick functions as described [here](http://www.loicdutrieux.net/bfastSpatial/#Data_Inventory). 

For B-Fast sepcific requirements [this research article](https://www.researchgate.net/publication/283695325_Error_Sources_in_Deforestation_Detection_Using_BFAST_Monitor_on_Landsat_Time_Series_Across_Three_Tropical_Sites) by Schultz et al. 2013 for further background. 

The app is designed to run inside [sepal](https://sepal.io) 

## Inputs

- AOI

- Start and End date

- Free selection of one or more satellites (Landsat 4-8 (Tier 2 optional), Sentinel-2 SR/TOA)

- selection between Top-of-Atmosphere and Surface Reflectance collections

- available stats: cloud-free pixel count, NDVI median and stdDev

- annual or full time-series stats

## Outputs

- Visualize the different analysis layers
- Export the analysis layers as a multi-band image


