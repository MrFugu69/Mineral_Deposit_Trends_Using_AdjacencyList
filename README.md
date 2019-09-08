# Project01 Overview: 
Physical Geology plays an important role in *Mining/Exploration* which indicate trends within local geography; *Data Scientists* would like to exploit trends and this is why I chose this exercise. In this work I will investigate trends in mineralization with the use of `Adjacency Lists` from *Graph Theory* <sup>[1](https://en.wikipedia.org/wiki/Adjacency_list#targetText=In%20graph%20theory%20and%20computer,for%20use%20in%20computer%20programs) </sup>.

# Purpose:
During exploration, indicators of local geology have a strong influence on perceived outlook of the area. This experiment provides a look at how `graph theory` can expand to `mining and exploration`. This will provide insight into the primary and secondary minerals found during exploration. While a main mineral/metal of interest will be desired; it is important to take into consideration other economically viable assets which may be available at these sites. 

# Data Collection: 
The main dataset came from the [USGS](https://mrdata.usgs.gov/mrds/), while other aspects of data collection used web-scraping. 

# Dependencies:
`pip install shapely` | `pip install pdf2image`  | `pip install bokeh`

# Visualization: 
Matplotlib and Bokeh

# Idea of what some of the attributes are:

| Site Name                | Latitude     | Longitude      | Country            | State      | Commodity_01     | Commodity_02     | Commodity_03     | Ore                                   | Gangue                         | Hrock type     |
|----------------------    |----------    |------------    |----------------    |--------    |--------------    |--------------    |--------------    |-----------------------------------    |----------------------------    |------------    |
| Lookout Prospect         | 55.05612     | -132.14344     | United States      | Alaska     | Copper           | Gold,Silver      | Nan              | Chalcopyrite,  Covellite,  Pyrite     | Quartz,  Sericite              | Schist         |
| Lucky  Find Prospect     | 55.5275      | -132.685       | United  States     | Alaska     | Copper           | Gold             | Nan              | Chalcopyrite, Pyrite                  | Calcite,  Quartz, Siderite     | Diabase        |
| Mccullough Prospect      | 55.9775      | -132.999       | United  States     | Alaska     | Copper           | Nan              | Zinc, Gold       | Chalcopyrite ,Pyrite,  Sphalerite     | Quartz                         | Siltstone      |


[Demo of Project Mineral Deposits of the world ](https://mybinder.org/v2/gh/MrFugu69/ProjectClass01_MineralDeposits/blob/master/Project_practice.ipynb)
