# Phenology-based sample generation for supervised crop type classification
Crop type mapping is relevant to a wide range of food security applications. Supervised classification methods commonly generate these data from satellite image time-series. Yet, their successful implementation is hindered by the lack of training samples. Solutions like transfer learning, development of temporal-spectral signatures of the target classes, re-utilization of existing inventories, or crowdsourcing initiatives are commonly applied to generate samples for thematically coarser classifications. These methods are rarely used for generating crop types samples. In this study, we leverage the phenology information of existing data inventories using Time-Weighted Dynamic Time Warping (TWDTW) to address the problem of automatic crop sample generation in two target areas. Resulting labeled samples are refined using proximity measures obtained from Random Forests (RF). Sentinel-2 time-series are used to obtain phenology information from two study areas. The proposed methodology achieved promising results for classes with a reduced inter-classes similarity such as sugar beets (user’s accuracy, UA, of 98% and producer’s accuracy, PA, of 100%) or grains (UA of 98% and PA of 90%). The crops with a high inter-classes similarity yielded less satisfactory results. Potatoes, for example, obtained a high PA of 95%, but a UA of only 36% because of the spectral-temporal similarity with maize. The methodology works well for areas with balanced crop samples. Yet, it favors prevalent classes in areas with imbalanced crops at the expense of a low accuracy for the minority crops. Despite these shortcomings, the proposed methodology offers a viable option to generate crop samples in regions with few ground labels.

This study has been published in the International Journal of Applied Earth Observation and Geoinformation and can be accessed from here:
Please cite the paper as follows:
