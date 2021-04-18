# World_Weather_Analysis

## Overview of Project

For this project, I am retrieving and analyzing data for a hypothetical travel company through two application programming interfaces (APIs). I used Jupyter Notebook, Pandas library, CityPy, SciPy, Python requests, OpenWeather and Google APIs, CSV files, and JSON traversals.

To complete this task, I used Jupyter Notebook and CityPy to collect a list of nearby cities from 2,000 randomly generated latitude and longitude coordinates from around the world. 

Next, I performed requests on the OpenWeather API to retreive weather data from these cities in JavaScript Object Notation (JSON) format. This weather data was then added to a Pandas DataFrame in Jupyter Notebook. A statistical analysis was conducted with the SciPy library, and matplotlib was used to create a series of scatter plots that visually and statistically tested the relationship between latitude and a variety of weather parameters, such as max temperature, humidity, cloudiness, and wind speed. An example plot of city latitude vs max temperatue is shown below, as well as linear regressions for the same data for the northern and southern hemispheres.

![Latitude v. Max Temp](https://github.com/tysonseang/World_Weather_Analysis/blob/main/weather_data/Fig1.png)

![Northern Hemisphere](https://github.com/tysonseang/World_Weather_Analysis/blob/main/weather_data/Northern_Hemisphere_Temp_Lat.png)

![Southern Hemisphere](https://github.com/tysonseang/World_Weather_Analysis/blob/main/weather_data/Southern_Hemisphere_Temp_Lat.png)

I then wrote a script that asks users to provide input statements for their desired mininum and maximum temperatures to provide a list of eligible cities for their next vacation. Using Google API integrations, I provided a list of the closest hotels within 5,000 meters of these locations. This hotel and weather data was then added to a marker layer and plotted on Google Maps as shown in the screenshot below.

![Vacation Map](https://github.com/tysonseang/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

Next, as an example, I selected four cities in India to create a hypothetical vacation itenerary. 

![Travel Map](https://github.com/tysonseang/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)

The trip would start in Madras, and pass through Sirsi, Bhalki, and Kavali before returning to the starting city. These locations were then added to a directions layer to plot driving directions on Google Maps.

![Travel Directions Map](https://github.com/tysonseang/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)