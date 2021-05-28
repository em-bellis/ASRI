# ASRI2021
 
Welcome to the GitHub repository for the Spatial Data in R session for the Arkansas Summer Research Institute. The goal of this session is to provide an introduction to commonly used spatial data types and R packages for visualizing geospatial data. While becoming an expert in these skills will take more time and practice than this 1 hour session, I hope that you will gain confidence with some of the tools and an awareness of additional resources to continue your learning.  For those looking to go further, I highly recommend some of the free and open source learning materials available through [Data Carpentry](https://datacarpentry.org/lessons/#geospatial-curriculum) and some of the tutorials available through [rspatial.org](https://rspatial.org).

The general plan for today is:

1. brief orientation to Rmarkdown
2. spatial data types (raster & vector)
3. map-making with the `tmap` package

## Prior to the session: 
1. **Download and install R and R Studio**.  Follow the instructions [here](https://datacarpentry.org/R-ecology-lesson/#Install_R_and_RStudio). 
*Even if you already have R, it is recommended to ensure you are working in R version 4.0 or later. You can check by running the command `version` in the R console.*

2. **Install some of the required R packages**. This can be done directly within the R Studio environment through the 'Packages' tab of the bottom left panel or running the following:
```
> install.packages(c("rgdal", "raster", "sp", "sf", "tmap","tmaptools"), dependencies = T)
```
