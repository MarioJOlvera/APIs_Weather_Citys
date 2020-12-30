# APIs Weather & Citys

Part I - Weather Py
Will be created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, will be used a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

As a first requirement is to create a series of scatter plots to showcase the following relationships:

  - Temperature (F) vs. Latitude
  - Humidity (%) vs. Latitude
  - Cloudiness (%) vs. Latitude
  - Wind Speed (mph) vs. Latitude
  
As a second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

  - Northern Hemisphere - Temperature (F) vs. Latitude
  - Southern Hemisphere - Temperature (F) vs. Latitude
  - Northern Hemisphere - Humidity (%) vs. Latitude
  - Southern Hemisphere - Humidity (%) vs. Latitude
  - Northern Hemisphere - Cloudiness (%) vs. Latitude
  - Southern Hemisphere - Cloudiness (%) vs. Latitude
  - Northern Hemisphere - Wind Speed (mph) vs. Latitude
  - Southern Hemisphere - Wind Speed (mph) vs. Latitude

Part II - City Py 

Now let's go to work with weather data to plan future vacations. Using jupyter-gmaps and the Google Places API for this part of the assignment.

  - Create a heat map that displays the humidity for every city from the part I of the homework.

  - Narrow down the DataFrame to find your ideal weather condition. For example:
        * A max temperature lower than 80 degrees but higher than 70.
        * Wind speed less than 10 mph.
        * Zero cloudiness.
        * Drop any rows that don't contain all three conditions. You want to be sure the weather is ideal.

https://tec.bootcampcontent.com/Tecnologico-de-Monterrey-Coding-Boot-Camp/tdm-mxc-data-pt-03-2020-u-c/raw/master/02-Homework/06-Python-APIs/Instructions/Images/heatmap.png



