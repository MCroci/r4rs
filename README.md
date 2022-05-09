# Remote Sensing with R
**Contributors:** *Michele Croci*

.. .. work in progress .. ..

We highly recommend using [RStudio](https://www.rstudio.com/). Here is a list of some R packages for analyzing remote sensing data

```r
library(RStoolbox)
library(landsat)
library(hsdar)
library(rasterVis) # for visualization
```

### Open a Sentinel-2 images
```r
r <- raster("2020-01-01.tif")
```
### Image information and statistics
```r
r
## class : RasterLayer
## dimensions : 1245, 1497, 1863765 (nrow, ncol, ncell)
## resolution : 30, 30 (x, y)
## extent : 594090, 639000, 4190190, 4227540 (xmin, xmax, ymin, ymax)
## crs : +proj=utm +zone=10 +datum=WGS84 +units=m +no_defs +ellps=WGS84
˓+towgs84=0,0,0
## source : c:/github/rspatial/rspatial-web/source/rs/_R/data/rs/LC08_044034_20170614_B2.tif
## names : LC08_044034_20170614_B2
## values : 0.0748399, 0.7177562 (min, max)
```







## Follow me:
[<img align="left" alt="Croci93 | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]
[<img align="left" alt="Croci93 | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="Croci93 | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]


[twitter]: https://twitter.com/croci93
[linkedin]: https://www.linkedin.com/in/michele-croci-265abb133/
