This is a spatial analysis of the Houston blackout that results from the February 2021 storms. Here, I instigate how communtiies of different socioeconomic status were impacted by the blackouts across the city. The `sf` and `stars` packages were used to perform vector and raster calculations, and maps wer made in `ggplot` using the `ggspatial` package. 

**Note:** the data associated with this analysis is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view?usp=sharing). Unzip the folder and all the contents and store in your directory as follows. 

```         
houston_blackout
│   README.md
│   Rmd/Proj files    
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
