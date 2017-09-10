# hurricane-prediction
Jupyter notebooks with tools to analyze and predict the paths of hurricanes

This uses a topography dataset as well as a historical
hurricane dataset. The idea is to use topography
data alongside historical hurricane information (paths and airspeeds)
to train an agent capable of predicting future location and
max airspeed given the current data on a hurricane.


## Datasets:
1. [NOAA 2-Minute Gridded Global Relief Data](https://www.ngdc.noaa.gov/mgg/global/etopo2.html)
2. [NOAA Hurricanes and Typhoons, 1851-2014](https://www.kaggle.com/noaa/hurricane-database)

## Requirements:
python 3.6.0
h5py (2.7.0)
numpy (1.13.1)
matplotlib (2.0.2)

## Instructions:
1. extract datasets.7z into the folder ./datasets
2. run notebooks
