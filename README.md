# Air Pollution

This repository provides Luxembourg NO₂ data in Parquet format along with a Jupyter notebook.
The notebook `load_NO2.ipynb` loads the measurements, shows station locations, and interpolates
the average readings into a raster (`no2_luxembourg.tif`) which can be used as an ML input feature.
