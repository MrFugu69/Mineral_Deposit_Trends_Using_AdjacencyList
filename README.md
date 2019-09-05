# Project01: 
Physical Geology plays an important role in Mining/Exploration which indicate trends within local geography which is what Data Scientist would like to exploit. In this work I will investigate trends in mineralization. During exploration: primary and secondary mineralization can be found and may have viable economic impact. 

# Purpose:
When searching for minerals, metals or fossil fuels indicators of local geology have a strong influence on perceived outlook of the area. You have to act like a detective and evaluate the land for specific characteristics. This is a valuable tool which can be exploited with data analytics. From an introductory course in Physical Geology, my professor explained that specific rock or mineral types are found when looking for precious metals, minerals or fossil fuels. This was very insightful on many levels; I decided now to prove that if per se I was interested in mining a specific element, what other elements may I find and are any of them economically important. 

# Data Collection: 
The main dataset came from the [USGS](https://mrdata.usgs.gov/mrds/), while other aspects of data collection used web-scraping. 

# Feature Engineering:
Will include getting rid of Regex, empty/null values and symbols.

# Transformation
I will need to disregard some of the columns of data because it is non-essential and I don't know what it means. 
I have to figure out what attributes I would like to collect and determine if I need to create a long format or just keep it 
wide. At a later point I may need to standardize these data for computation "log-transform,linearization, etc".

# Visualization: 
Matplotlib and Bokeh

# Idea of what my data look like for some of the attributes:

| Site Name                | Latitude     | Longitude      | Country            | State      | Commodity_01     | Commodity_02     | Commodity_03     | Ore                                   | Gangue                         | Hrock type     |
|----------------------    |----------    |------------    |----------------    |--------    |--------------    |--------------    |--------------    |-----------------------------------    |----------------------------    |------------    |
| Lookout Prospect         | 55.05612     | -132.14344     | United States      | Alaska     | Copper           | Gold,Silver      | Nan              | Chalcopyrite,  Covellite,  Pyrite     | Quartz,  Sericite              | Schist         |
| Lucky  Find Prospect     | 55.5275      | -132.685       | United  States     | Alaska     | Copper           | Gold             | Nan              | Chalcopyrite, Pyrite                  | Calcite,  Quartz, Siderite     | Diabase        |
| Mccullough Prospect      | 55.9775      | -132.999       | United  States     | Alaska     | Copper           | Nan              | Zinc, Gold       | Chalcopyrite ,Pyrite,  Sphalerite     | Quartz                         | Siltstone      |


[Demo of Project Mineral Deposits of the world ](https://mybinder.org/v2/gh/MrFugu69/ProjectClass01_MineralDeposits/blob/master/Project_practice.ipynb)
