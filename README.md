# hot_spot_classifier
Classification test of GEE data out put for detecting change hot spots

#### requirements
- pycaret 1.0
- rasterio
- pandas


This project uses pycaret to train and infer machine learning models for geospatial data. 

It contains of 2 stages

**1. data training including:**
- best model selection
- model tuning
- model saving (pickle)

**2. model inference including:**
- model loading (pickle)
- input data loading (GeoTiff)
- model inference
- output data saving (class prediction + class probabilities)
