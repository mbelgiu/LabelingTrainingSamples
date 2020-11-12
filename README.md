# Phenology-based sample generation for supervised crop type classification
Crop type mapping is relevant to a wide range of food security applications. Supervised classification methods commonly generate these data from satellite image time-series. Yet, their successful implementation is hindered by the lack of training samples. Solutions like transfer learning, development of temporal-spectral signatures of the target classes, re-utilization of existing inventories, or crowdsourcing initiatives are commonly applied to generate samples for thematically coarser classifications. These methods are rarely used for generating crop types samples. In this study, we leverage the phenology information of existing data inventories using Time-Weighted Dynamic Time Warping (TWDTW) to address the problem of automatic crop sample generation in two target areas. Resulting labeled samples are refined using proximity measures obtained from Random Forests (RF). Sentinel-2 time-series are used to obtain phenology information for target crops.
The methodology works well for areas with balanced crop samples. Yet, it favors prevalent classes in areas with imbalanced crops at the expense of a low accuracy for the minority crops. 

The code required for refining labeled samples using Random Forests in available in the R_code folder together with raster and samples data for testing purposes.

This study has been published in the International Journal of Applied Earth Observation and Geoinformation and can be accessed from here: https://www.sciencedirect.com/science/article/pii/S0303243420309077

Please cite the paper as follows: Belgiu, M., Bijker, W., Csillik, O., & Stein, A. (2021). Phenology-based sample generation for supervised crop type classification. International Journal of Applied Earth Observation and Geoinformation, 95, 102264

