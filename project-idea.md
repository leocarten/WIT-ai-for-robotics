# AI For Robotics - Project Idea Rev 1
09.15.25
# Intro - a proof of concept
The idea is to create an autonomous robot that can traverse an unknown environment using SLAM while tracking air temperature and air quality (e.g. humidity, CO2 concentration). IRL this could be useful for large indoor green-houses (e.g. agriculture, cannabis farms), industrial spaces (e.g. science labs, working environments for safety, or clean rooms), and data warehouses (e.g. large server farms).

# What will the robot generate?
The goal would be for the robot to explore its environment and when done should generate a 2D map of its explored terrain with the overlayed data (e.g. air quality + air temp) hosted on a web-server for remote access. 

# High Level Logistics 
This idea is still preliminary and for review but the robot SHALL:
- have an embedded rasp pi for data collection and a light weight web server for hosting (i have a rasp pi4)
- have the ability to traverse its environment using wheels (e.g. a DIY car project that allows rasp pi integration)
- have a UPS battery pack hat (need to reference device compatibility chart)
- use a lidar sensor to implement traversal via SLAM
- use air quality / temp sensors / photon sensors to generate data
- create a data pipeline such that the data collected is relayed to a front-end JS framework to generate an interactive map showing overlaid sensor data and 2D map visualization
