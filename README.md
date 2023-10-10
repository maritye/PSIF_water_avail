# PSIF_water_avail
Scripts and data to produce HESS paper Tye et al. 2023 on water availability metrics.

Tye et al. 2023 represents the output of a cross-disciplinary research project that examines water availability and the ability of large scale global Earth system models to support localized decisions. We drew on prior collaborative research (both at NCAR and in the broader community) to identify metrics that are used in water use decisions. The resultant set of precipitation and runoff metrics were then tested in the Community Earth System Model v2 (CESM2) to evaluate whether they are credibly reproduced over the conterminous U.S. We found that CESM2 can capture aspects of precipitation and runoff that are important for water resource management, concluding that there is potential for far greater use of large scale ESMs in long-range water resource decisions.

This repository contains the data sets used to calculate indices such as P95Tot, NWD and 7Q10, and the scripts to calculate those indices and the figures in the publication.

## Data
* Livneh 7 day averaged daily runoff over the CONUS  (1981-2005)  
* CESM2 10 members 7 day averaged daily runoff over CONUS (1981-2005)  
* Livneh 7 day averaged runoff indices by HUC2 regions (1981-2005)  
* CESM2 10 members  7 day averaged runoff indices by HUC2 regions (1981-2005)  
* CESM2 10 members gridded daily precipitation over CONUS (1981-2010)  
* Livneh gridded daily precipitation over CONUS (1981-2010)
* CESM2 10 members annual precipitation indices by HUC2 region (1981-2010)
* Livneh annual precipitation indices by HUC2 region (1981-2010)

## Scripts  
* Script for publication figures 23-10-05_Paper_submission_Figures.ipynb
* Aggregate precipitation data to the HUC 2 regions 22-09-29_CreateHUC_RegionalTS.ipynb
* Aggregate runoff data to the HUC2 regions 23-03-17runoff_huc2.ipynb
