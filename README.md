# World_Weather_Analysis

## Overview of the analysis

This analysis was conducted to help Jack create the PlanMyTrip App, which helps travelers plan their potential vacations. The three major components generated were: 

1) A comprehensive weather data for a randomly generated list of world cities
2) A customer travel destinations map that shows the aforementioned cities as marked on a world map as well as a hotel in each one.
3) A travel itinerary map that shows the route of a round trip between four cities within the same country.


## Results

### Plan

The API services of OpenWeatherMap and Google Maps were utilized to collect and visualize data for the above components. Code was written in Python on Jupyter Notebook.

### Weather Data Table

The weather for a subset of the above cities, namely cities that were within a range of temperatures that travelers provided, was pulled from the OpenWeatherMap API and, using pandas, was placed into a helpful dataframe as well as a CSV file.

### Destinations Map

These same 762 cities were then plotted on a map of the Earth using Google Maps API, along with information concerning each city's country code, current weather conditions including maximum temperature, and a hotel to stay at. The resulting map can be [seen here](https://github.com/josephrodini/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG).

### Itinerary Map

Finally, two maps of a hypothetical road trip was created, again using Google Maps API. The cities chosen were in the midwest United States. The first map showed a [driving route from city to city](https://github.com/josephrodini/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG), while the second showed [a hotel and weather conditions for each city](https://github.com/josephrodini/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png). 

## Summary

The project overall was a success, with many features developed to help travelers plan vacations.

### Limitations

Errors were reported both when generating a list of random cities and finding a hotel within the cities that were found. This means that the overall report is somewhat incomplete.