# Overview
This is the first project of SDC term 2.

In this project you will utilize a kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower than the tolerance outlined in the project rubric. 

The input data is mixed with lidar and radar data. For lidar data, it will be easier. But for Radar data, it needs to convert the polar coordinates to Cartesian coordinates.

[image0]: rmse.png "rmse"

# How to compile

From the root of the repo:

* mkdir build && cd build
* cmake .. && make
* ./ExtendedKF

# Accuracy

![alt text][image0]


