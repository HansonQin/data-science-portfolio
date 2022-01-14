# Kriging Prediction Algorithm
This is part of a project to predict the number of aircrafts hidden by cloud covers in satelite imagery, as a consulting project for Orbital Insight.

### Methods Used
* Inferential Statistics
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Pandas, GeoPandas, NumPy, SciPy
* etc. 

## Project Description
This directory contains an algorithm that uses simple Kriging to predict the number of aircrafts within clouds. It achieves this by taking any given
area of interest with clouds and seen detections, converts that area into a grid detailing the number of aircrafts in each grid, and uses Kriging 
to predict the counts for the grids within each cloud.

This project is just one method our consulting group explored to tackle the prediction problem detailed above - other methods tried were using KDEs and Poisson Regression.

Unfortunately, the data used in this project is proprietary and won't be included in this repository.
