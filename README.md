# FDSI-Projections-for-CONUS
This repository provides an NCAR Command Language (NCL version 6.6.2 required) script titled "calc_fdsi_opendap_lat-lon.txt" to produce an annual time series of the Forest Stress Drought Index (FDSI based on Williams et al., 2013) for any region in the Contiguous United States between 1950-2099 using monthly projections of precipitation and vapor pressure deficit from MACAv2-metdata. Only inputs to the script required include: (i) identification of the GCM (https://climate.northwestknowledge.net/MACA/GCMs.php) and the emissions scenario (RCP 4.5 or RCP 8.5), and (ii) the latitude and longitude boundaries of the region. The standardization (z-score calculations) is done relative to the climatology of the 1950-2005 time period. MACA data is accessed by the script via OpENDAP. Output includes a time series table in .txt and plot in .png. Example output files are included here: FDSI_timeseries_Rocky Mountain National Park_1951-2099_BNU-ESM_r1i1p1_rcp45_MACAv2-metdata(.png & .txt). 

Historical CONUS-wide Gridded Datasets for FDSI in netCDF:
1. GRIDMET-based FDSI (1980-2021): This calculation uses monthly precipitation and VPD from GRIDMET as drivers; Data Access: https://tinyurl.com/FDSI-GRIDMET
2. nClimGrid-based FDSI (1896-2017): This calculation uses monthly precipitation and maximum daily temperature (not VPD) from nClimGrid as drivers; Data Access: https://tinyurl.com/1d7dmrlk

Application of FDSI: Forest Drought Stress Index (FDSI) to identify extreme drought years and quantify their occurrences

FDSI measures dryness or drought stress across the water year by integrating anomalies in cold season (November – March) precipitation and warm season vapor pressure deficit (August – October of previous year and May – July of current year). The formulation of FDSI incorporates calibration using tree ring data in US west (Williams et al., 2013). This index is particularly appropriate for the western US ecosystems but could also be relevant for other ecosystems where the cold season provides a large majority of annual precipitation.

FDSI is found to be sensitive metric at identifying extreme drought years such as 2002, 2012 and 2018 across Colorado for example. FDSI could also be forward projected in time, using projections of climate drivers, to assess changing severity of yearly droughts and to quantify reoccurrence frequency of an extreme historical drought in a future period.  

Acknowledgement: This work is supported by the North Central Climate Adaptation Science Center at the University of Colorado, Boulder. MACAv2-METDATA are obtained from http://www.climatologylab.org/maca.html.

Reference: Park Williams, A., Allen, C., Macalady, A. et al. Temperature as a potent driver of regional forest drought stress and tree mortality. Nature Clim Change 3, 292–297 (2013). https://doi.org/10.1038/nclimate1693

