# World Weather Analysis

## Overview

The World Weather Analysis excercise offers a bird's eye view of the various parameters to understand the weather patterns and how these weather patterns can influence a vacation itinerary

### Weather Database

This folder uses Open Weather Map API to pull weather information of 663 different cities around the world. That information consists of:

1. Maximum Temperature
2. Cloudiness
3. Wind Speed
4. Humidity
5. Current Weather Description

These are the parameters which influence the decision making of a traveler based on his or her choice of weather conditions.

### Vacation Search
In this folder the power of jupyter library and Google Maps API is visible as the image below plots the name of the hotel, city, country and temperature based on the criteria of all the cities in the database that have an daily maximum temperature between 75 and 90 degrees farinheit. All this is done using the Google Maps API available on Google Cloud Platform

![image](https://github.com/yashodhan1202/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

### Vacation Itinerary

This folder contains information that is pulled using Google Directions API for 4 cities in Brazil. The image below plots the round trip route from the starting city (Caiaponia, BR) with waitpoints being (1. Joao Pinheiro, 2. Caravelas,  3. Rio Claro all in Brazil) and back to the starting city (Caiaponia, BR)

![image](https://github.com/yashodhan1202/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Also, as with the vacation search folder, there is hotel info at each location.

![image](https://github.com/yashodhan1202/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
