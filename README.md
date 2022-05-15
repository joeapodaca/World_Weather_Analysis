# World_Weather_Analysis

## Overview
Create an app with input statements to filter the data for traveler’s weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

### Resources
Data Source: WeatherPy_database.csv, WeatherPy_vacation.csv, cities.csv, google maps

Software Python 3.6.1, Jupyter Notebook

## Investigation
To get started an investigation was done to gather weather data from different areas around the world.

City Latitude vs Max temperature

![Max temperature](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/weather_data/Fig1.png)

City Latitude vs Humidity

![Humidity](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/weather_data/Fig2.png)

City Latitude vs Cloudiness

![Cloudiness](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/weather_data/Fig3.png)

City Latitude vs Wind Speed

![Wind Speed](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/weather_data/Fig4.png)

## Results
The traveler is asked to for their desired minimum and maximum temperature desires. The search returns all the destinations that have their desired temperature.

![Vacation search](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)


The traveler chooses 4 destinations and receives a travel map with the required routes.
![Weather travel map](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)


Markers are added to the map to show the traveler the hotel name, city, country, current weather and max temp.
![Weather travel map with markers](https://github.com/joeapodaca/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)



## Summary
This travler chose to stay in the US.  Happy travels!
