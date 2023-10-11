# SpatialOmicsOverlay - Adapted to allow string and special chars in ROI names

## Overview

The SpatialOmicsOverlay package contains tools for analyzing data on the image from
NanoString GeoMx Digital Spatial Profiler (DSP). It provides functions
to extract image and XML from OME-TIFFs, overlay Regions of Interest (ROIs) onto
the image, and manipulate the image (coloring, orientation, cropping). Output 
figures are ggplot based allowing for easy customization of images to include
spatial images into data visualization. 


### Install the version from THIS REPOSITORY
``` r
if (!requireNamespace("devtools", quietly=TRUE))
    install.packages("devtools")
    
devtools::install_github("natmurad/SpatialOmicsOverlay", 
                         build_vignettes = F)
```

## Citation
Griswold, M.
SpatialOmicsOverlay: Spatial Overlay for Omic Data From Nanostring GeoMx data. 
NanoString Technologies Inc.; Seattle, WA 98109, USA. 2021. 

## License
This project is licensed under the [MIT license](LICENSE).
