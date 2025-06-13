# ClimateChangeDeforestationPaper

This repository accompanies the manuscript  
"How climate change and deforestation interact in the transformation of the Amazon rainforest"
(Franco et al., submitted to *Nature Communications).

It contains:
- Scripts for downloading data from Google Earth Engine (GEE)
- Python scripts for processing, analyzing, and visualizing the data
- EInput and output datasets (compressed as ZIP files)

---
Author: Marco Aurélio de Menezes Franco
Contact: marco.franco@usp.br
---

## Main Python Packages

The main Python libraries used are:

- `numpy`, `pandas`, `datetime`, `glob`, `math`, `os`
- `matplotlib` (`pyplot`, `cm`, `mplot3d`, `gridspec`, `ticker`)
- `seaborn`
- `PIL` (Python Imaging Library)
- `scipy` (`signal`, `stats`, `optimize`)
- `statsmodels`
- `sklearn` (`linear_model`, `cluster`)
- `pylab`

Everything runs on Python 3.x, tested in Jupyter Notebooks and compatible with Google Colab.

---

##Data

Due to file size, raw data is stored as a .zip file. 

- **GEE scripts** provide exact code for downloading:
  - Forest cover (MapBiomas)
  - ERA5 reanalysis (temperature, precipitation)
  - GPM precipitation

**- All raw and processed data files are provided as `.zip` in the `data/` folder.**

**Process and analyze data**
   - Open the Python scripts or run them in a Jupyter Notebook.
   - All scripts have comments (still being improved).
   - Can be executed locally or in Google Colab.

**This file is still being improved.**
