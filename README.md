# Bike_Sharing_Demand_Prediction
This repository harnesses the power of R programming to delve into real-world datasets and analyze how weather affects bike-sharing demand in urban areas. The project entails data collection, wrangling, exploratory data analysis, and predictive modeling techniques.

# Overview
The project entails:
- Collecting and understanding data from multiple sources.
- Performing data wrangling and preparation with regular expressions and Tidyverse.
- Conducting exploratory data analysis with SQL and visualization using Tidyverse and ggplot2.
- Modeling the data with linear regressions using Tidymodels.

# Understanding the Source Data
## Seoul Bike Sharing Demand Data Set
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall) and the number of bikes rented per hour and date. This dataset will be used to build a linear regression model of the number of bikes rented each hour based on the weather.
Attribute Information:
- Date: year-month-day
- Rented Bike count: Count of bikes rented at each hour
- Hour: Hour of the day
- Temperature: Temperature in Celsius
- Humidity: unit is %
- Windspeed: unit is m/s
- Visibility: unit 10m
- Dew point temperature: Celsius
- Solar radiation: MJ/m2
- Rainfall: mm
- Snowfall: cm
- Seasons: Winter, Spring, Summer, Autumn
- Holiday: Holiday/No holiday
- Functional Day: NoFunc (Non-Functional Hours), Fun(Functional hours)

## Open Weather API Data
The Open Weather API provides current and forecasted weather data for any location, including over 200,000 cities. Data collected includes temperature, humidity, wind speed, visibility, and more.

## Global Bike Sharing Systems Dataset
This dataset lists active bicycle-sharing systems around the world, allowing users to pick up and drop off bicycles at any of the automated stations within the network.

## World Cities Data
Contains information such as name, latitude, and longitude about major cities around the world.

# Instructions for Running the Project
- Clone this repository to your local machine.
- Install the required packages.
- Follow the instructions provided in the project documentation to collect and process the necessary data.
- Run the Jupyter notebooks in the notebooks directory to perform data analysis and modeling.

## Citation
- Sathishkumar V E, Jangwoo Park, and Yongyun Cho. Using data mining techniques for bike sharing demand prediction in metropolitan city. Computer Communications, Vol.153, pp.353-366, March 2020.
- Sathishkumar V E and Yongyun Cho. A rule-based model for Seoul Bike sharing demand prediction using weather data European Journal of Remote Sensing, pp. 1-18, Feb 2020.
# Acknowledgments
Special thanks to IBM  and Couresra for providing the course materials and datasets necessary for completing this project.
