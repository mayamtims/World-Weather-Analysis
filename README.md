# World-Weather-Analysis

## Purpose
The purpose of this project was to create an interactive map that allows users to input weather criteria to identify travel desinations. Using the OpenWeatherMap API, users are provided location and hotel reccomendations based on their weather preferences.

## Overview 
To create the interactive map, 2,000 longitudes and latitudes were randomly selected using the API. The nearest city to each coordinate was then identified and compiled into a list, and weather data for each location was organized into DataFrames. Finally, the data was then visualized via an interactive map that provides users with a hotel name, city, country and current temperature and weather descriptions for each location. 