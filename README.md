# Geospatial Mapping (via Python)

## WRI Aqueduct 3.0 Water Risk Dataset 

[Source](https://www.wri.org/data/aqueduct-global-maps-30-data)

#### 1. The Codes

The programming language used is Python. Essential libraries/functions used are:

| Library  | Description |
|-------------|-----|
|`geopandas`| to read .gpkg datasets. (containing water risk datasets with polygon geomteries column of countries/states of the world)|  
|`pandas`| to read .csv files and for cleaning NaN values.|  
|`matplotlib`| for plotting geo-datasets|  
|`folium`| for creating chloropleth maps (interactive maps)|  
|`numpy`| |  

#### 2. Creating Stationary Water Risk Atlas 

* Using `geopandas` & `matplotlib`.

* Run `Indian_map_bws.ipynb`, it will read data from `data_ind.gpkg` and make Indian Map Baseline Water Risk Data as an output. (refer `Annual_aqueduct2019.ipynb` for creating `data_ind.gpkg` from large aqueduct file downloaded from WRI)

* Run `egypt_map_bws.ipynb`, it will read data from `data_egy.gpkg` and make Egypt Map Baseline Water Risk Data as an output. (refer `Annual_aqueduct2019.ipynb` for creating `data_egy.gpkg` from large aqueduct file downloaded from WRI)

* Run `world_map_bws copy.ipynb`, it will read data from WRI Aqueduct data downloaded and make World Map Baseline Water Risk Data as an output.


#### 3. Creating Interactive Water Risk Atlas 

* Using `geopandas`, `pandas` & `folium`.

* Run `interactive_map_india_bws.ipynb`, it will read data from WRI Aqueduct data downloaded and make Interactive World Map & labelled states in all countries, with Indian Baseline Water Risk Data plotted on top of it as an output `interactive_map_india_bws.html`.




