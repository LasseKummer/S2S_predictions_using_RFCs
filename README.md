# S2S_predictions_using_RFCs
Code for the paper "Subseasonal to Seasonal Prediction of European Winter Weather Using Random Forests" by Huo et al.

### Purpose
The code provided in this repository employs *random forest classifiers* (RFCs) for purely data-driven subseasonal to seasonal (S2S) predictions of winter temperature and precipitation across different European regions, as described in the paper by Huo et al. In addition, code is provided for the S2S prediction of "North Atlantic-European weather regimes" using RFCs.

### Optimization and final testing of the RFC models
The folders `features` and `targets` contain the input files for the random forest classifiers. Using those CSV files, the scripts in `validation` and `testing` can be run (some file path adjustments will be necessary). 

### Preprocessing and statistical analysis
In order to reproduce the input files for the RFCs, the scripts in the folder `preprocessing` can be used. The necessary data can be downloaded from https://cds.climate.copernicus.eu/datasets/reanalysis-era5-pressure-levels and https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels (ERA5 data via C3S/CDS), https://ftp.cpc.ncep.noaa.gov/cwlinks/norm.daily.nao.index.b500101.current.ascii (NAO index by NOAA) and https://www.bom.gov.au/climate/mjo/#tabs=Monitoring (MJO data by Australian BOM).\
The preprocessing results can also be used for the statistical analysis scripts in `analysis`.
