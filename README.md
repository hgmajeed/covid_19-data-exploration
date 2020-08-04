# covid_19-data-exploration
In this project, my focus will be on the exploration side of the analysis. The exploration will be divided into three parts. The first one will explore the countries of the world. The second will examine the relationship between the total number of cases and population density, and the third part, will explore the data for the Arab world countries.

## Dataset
The data were obtained from three sources:
1. [European Centre for Disease Prevention and Control](https://opendata.ecdc.europa.eu/covid19/casedistribution/csv). However, since this is a live data, I had to create an offline version of that data by July 31, 2020, where I decided to stop the analysis and upload to github. The offline file is `raw_data_07_31_20.csv`.
2. `ctrys_pop.csv`. This is the second file where I obtained from [kaggle](www.kaggle.com). 
3. A shape file from [geopandas documentation](https://geopandas.org/mapping.html)

## Python Version
- Python 3.7.3

## Required Libraries
- pandas
- numpy
- geopandas
- matplotlib
- seaborn
- math

## Other Files Provided
- `covid_19_clean_csv`: This file is the result of cleaning the three original files. 
- `world_map.shp`: After cleaning the shape file obtained from geopandas documentation, I had to save it separately to merge it later with `covid_19_clean_csv` in the exploration phase.
- `wrangle_act.ipynb`: This is a python notebook where all the wrangling efforts were achieved.
- `EDA.ipynb`: This is a python notebook where all exploration and analysis took place.
- `EDA_ss.ipynb`: This is a python notebook, same as above, but was slightly modified to create the slide decks.
- `EDA_ss.html`: This is an html file of the slide decks showing the analysis efforts.
