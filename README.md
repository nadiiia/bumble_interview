# Bumble interview practical task

## Analysis


**Bumble_interview_US_census_data.ipynb**  contains data EDA, some maps and example of possible geo-expansion.
**Bumble_interview_US_census_data-expanded_clustering.ipynb** is focused on different types of clustering techniques.


## Additional data

 US Census Bureau [TIGER](https://www2.census.gov/geo/tiger/GENZ2018/description.pdf)  [database](https://www2.census.gov/geo/tiger/GENZ2018/shp/cb_2018_us_state_20m.zip) to visualize state boundaries 
 
 Please download this data and save to /data 

## Requirements

Please create new environmet for this lab using  **Python 3.7**
 
Using [Anaconda](https://docs.anaconda.com/anaconda/install/)  please install the following 

```python

#Create new environment

conda create --name myenv python=3.7

#Make sure that you are going to work in newly created environment

conda activate myenv

# Install jupyter lab
conda install jupyterlab -c conda-forge

# Install packages
conda install -c conda-forge geopandas
conda install -c conda-forge matplotlib
conda install -c conda-forge mapclassify
conda install -c conda-forge contextily
conda install -c conda-forge geoplot
conda install -c conda-forge seaborn
conda install -c conda-forge descartes 
conda install -c anaconda openpyxl
conda install -c conda-forge folium
conda install --channel conda-forge pysal
conda install -c conda-forge clusterpy
```

