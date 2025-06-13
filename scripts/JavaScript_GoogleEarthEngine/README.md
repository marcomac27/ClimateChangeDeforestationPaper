# GEE Data Extraction Scripts

This folder contains Google Earth Engine (GEE) JavaScript scripts used in the analysis for the manuscript:

"How climate change and deforestation interact in the transformation of the Amazon rainforest"  
(Franco et al., 2025, submitted to *Nature Communications*)

Note: The order of the downloaded areas in the script is not the same as in the manuscript. To match the manuscript's order, use the following mapping:
 `1: 16, 2: 15, 3: 18, 4: 17, 5: 19, 6: 20, 7: 21, 8: 22, 9: 23, 10: 24,`
 `11: 25, 12: 26, 13: 27, 14: 28, 15: 29, 16: 11, 17: 10, 18: 12, 19: 13,`
 `20: 14, 21: 6, 22: 7, 23: 8, 24: 9, 25: 3, 26: 4, 27: 5, 28: 2, 29: 1`

## Files

- `gee_extraction.js`: Extracts forest cover (MapBiomas), ERA5 daily temperature, and GPM monthly precipitation.
- `geometries.js`: Defines 29 rectangular study areas in the Brazilian Amazon used for all analyses.

## Datasets Accessed

- [MapBiomas Collection 6](https://mapbiomas.org/)
- [ERA5 Reanalysis (ECMWF)](https://cds.climate.copernicus.eu/)
- [GPM IMERG Monthly](https://gpm.nasa.gov/data)

## How to Use

1. Open [Google Earth Engine Code Editor](https://code.earthengine.google.com/)
2. Upload the two scripts:
   - `gee_extraction.js`
   - `geometries.js`
3. Modify the line:
   ```javascript
   var geometry = geometry12; // Change to geometry1 to geometry29
