**A Spatial Analysis of Houston Blackouts and the Communities it Affected**

This is a spatial analysis of the Houston blackout that results from the February 2021 storms. Here, I investigate how communities of different socioeconomic status were impacted by the blackouts across the city. The `sf` and `stars` packages were used to perform vector and raster calculations, and data sets were wrangled and joined to combine socioeconomic data with satellite raster data to county shape files. Identified blackout homes were then spatially joined to census block groups to get socioeconomic data associated with the homes. Maps were created using the `ggplot` and `ggspatial` packages to communicate how blackouts impacted communities of varying socioeconomic status across the city as a result of the storms. 

>  In most cases, all desired data will not be in one format or data type which makes spatial analysis challenging. This work flow demonstrates how to transform and join vector, raster, and tabular data so that we can draw conclusions and make maps from a variety of data sets.

**Note:** the data associated with this analysis is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view?usp=sharing). Unzip the folder and all the contents and store in your directory as follows. 


*Project Structure*
```         
houston_blackout
│   README.md
│   Rmd/html/Proj files    
│
└───data
    │   gis_osm_buildings_a_free_1.gpkg
    │   gis_osm_roads_free_1.gpkg
    │
    └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
    |   │   census tract gdb files
    |
    └───VNP46A1
    |   │   VIIRS data files
```
