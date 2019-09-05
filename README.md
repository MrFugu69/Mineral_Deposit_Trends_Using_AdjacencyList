# Project01: 
Physical Geology plays an important role in Mining/Exploration work, indicating trends within local geography. Such trends are what Data Scientist would like to exploit. In this work we will investigate trends in mineralization establishing that minerals/metals can exhibit secondary minerals which may have economic importance. Typically, this has a two fold benefit.

# Data Collection: 
I did not use web-crawling or scraping. I found the dataset from a government site. At this point my programming skill are juvenile but in the future I would like to put something together with crawling or scraping to make my own dataset since this is what you do in the "real world" if you have a question you want to answer. 

1.) 
# Sole Contributor: Logan Register

2.) 
# Data Cleanup: 
about 2-2.5 weeks from Jan. 25th

3.) 
# Feature Engineering:
Will include getting rid of Regex, empty/null values and symbols.

4.)  #
# Transformation
I will need to disregard some of the columns of data because it is non-essential and I don't know what it means. 
I have to figure out what attributes I would like to collect and determine if I need to create a long format or just keep it 
wide. At a later point I may need to standardize these data for computation "log-transform,linearization, etc".

# Statistics
I am not sure what testing I will do, I may think about clustering, but I am not entirely sure because I have not concretely decided what I want to learn about these data. 

# Visualization: 
I can use seaborn, matplotlib or bokeh: really i am not sure. It will depend if I do rendering with html or not


# Idea of what my data look like for some of the attributes:

| Site Name                | Latitude     | Longitude      | Country            | State      | Commodity_01     | Commodity_02     | Commodity_03     | Ore                                   | Gangue                         | Hrock type     |
|----------------------    |----------    |------------    |----------------    |--------    |--------------    |--------------    |--------------    |-----------------------------------    |----------------------------    |------------    |
| Lookout Prospect         | 55.05612     | -132.14344     | United States      | Alaska     | Copper           | Gold,Silver      | Nan              | Chalcopyrite,  Covellite,  Pyrite     | Quartz,  Sericite              | Schist         |
| Lucky  Find Prospect     | 55.5275      | -132.685       | United  States     | Alaska     | Copper           | Gold             | Nan              | Chalcopyrite, Pyrite                  | Calcite,  Quartz, Siderite     | Diabase        |
| Mccullough Prospect      | 55.9775      | -132.999       | United  States     | Alaska     | Copper           | Nan              | Zinc, Gold       | Chalcopyrite ,Pyrite,  Sphalerite     | Quartz                         | Siltstone      |


[Demo of Project Mineral Deposits of the world ](https://mybinder.org/v2/gh/MrFugu69/ProjectClass01_MineralDeposits/blob/master/Project_practice.ipynb)
