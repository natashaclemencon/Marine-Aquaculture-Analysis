# Repository for the first homework assignment in EDS 223 

This repository houses data from:
- NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1, which contains annual sea surface temperature averages (SST) from years 2008 to 2012, accessed from .

- General Bathymetric Chart of the Oceans ocean depth data, accessed from https://www.gebco.net/data-products/gridded-bathymetry-data#area. 

- marineregions.org, which houses maritime boundaries, accessed from https://www.marineregions.org/eez.php. 

Author(s): Natasha Clemencon-Charles

This repo has the following structure:
```{r}
EDS223-HW3
├── aquaculture_analysis_files
├── aquaculture_analysis.html
├── aquaculture_analysis.qmd
├── data 4
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
└── README.md
```

The visualizations and html created for this assignment were completed in the aquaculture_analysis.qmd.

The qmd uses the GEBCO, EEZ, and SST datasets to determine the ideal West Coast Exclusive Economic Zones for marine aquaculture. It contains a function that can be used to determine the ideal areas for various types of marine animal species, when provided parameters for min and max depth requirements, and min and max temperature requirements. 

When inputting arguments for oysters, we see that the ideal EEZ is on the central California coast. For red abalone, the ideal zone is on the Washington coast. 
