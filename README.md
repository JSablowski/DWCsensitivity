# Global sensitivity analysis of a pure steam dropwise condensation heat transfer model
#### [![DOI](https://zenodo.org/badge/308324086.svg)](https://zenodo.org/badge/latestdoi/308324086)

This package includes the dataset presented in the research article "Global sensitivity analysis of a pure steam dropwise condensation heat transfer model" by Jakob Sablowski, Simon Unz and Michael Beckmann.  

The raw data used to produce the figures in the article can be found as csv-files in the /data folder.

## Reproducing figures

Download all files and run the jupyter notebook Sensitivity_DWCmod_plot.ipynb to reproduce all figures from the files in /data/pickle, which is the same dataset that is used in the research article. Figures will be stored to the /output folder.

## Generating a new dataset

Download all files and run the jupyter notebook Sensitivity_DWCmod_calc.ipynb to rerun the sensitivity analysis using the model /DWCmod/DWC_models.py. This will generate a new dataset and save it as csv-files to the folder /data and as pkl-files to /data/pickle. For more information on the dropwise condensation heat transfer model please confer: https://doi.org/10.5281/zenodo.2561203.

## Requirements

The following non-standard python packages are required:
* matplotlib
* numpy 
* scipy
* coolprop
* SALib
* pandas
* seaborn


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
