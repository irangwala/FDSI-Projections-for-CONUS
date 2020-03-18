# FDSI-Projections-for-CONUS
This is a NCAR Command Language (NCL version 6.6.2 required) script to produce an annual time series of Forest Stress Drought Index (FDSI based on Williams et al., 2013) between 1950-2099 using monthly projections of precipitation and vapor pressure deficit from MACAv2-metdata. Only input to the script required include (i) identification of the GCM run (https://climate.northwestknowledge.net/MACA/GCMs.php), and (ii) the latitude and longitude boundaries of the region. MACA data is accessed by the script via OpENDAP. Output includes a time series table in .txt and plot in .png.

Acknowledgement: This work is supported by the North Central Climate Adaptation Science Center at the University of Colorado, Boulder. MACAv2-METDATA are obtained from http://www.climatologylab.org/maca.html.

Reference: Park Williams, A., Allen, C., Macalady, A. et al. Temperature as a potent driver of regional forest drought stress and tree mortality. Nature Clim Change 3, 292–297 (2013). https://doi.org/10.1038/nclimate1693
