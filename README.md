# Best Travel Destinations
## Summary
This project generates a list of cities to find a list of ten ideal vacation spots. It uses the citipy and gmaps libraries to find and display the city data.

![heatmap](https://github.com/eukestad/python-api-challenge/blob/main/WeatherPy/images/heatmap.png)

## Files in the Repository
The files for the project are in the main WeatherPy folder. The folder contains two folders and two Jupyter Notebooks: 

* WeatherPy - Notebook for performing city analysis to discover relationships between weather and city location

* VacationPy - Notebook for mapping a heat map of humidity and markers for ideal vacation spots

* images - folder to store images from analysis

* output_data - folder to store exported city csv

## Using the Notebooks
To use the notebooks you will need an api key for the OpenWeatherMap API and the Google Places API. Update the api_keys.py file with your keys to run the code.

## Output
The code outputs a series of scatter plots and linear regressions that evaluate the relationships between: 

* Temperature (F) vs. Latitude

* Humidity (%) vs. Latitude

* Cloudiness (%) vs. Latitude

* Wind Speed (mph) vs. Latitude

## Features
The WeatherPy final notebook: 

* Randomly selects at least 500 unique (non-repeat) cities based on latitude and longitude.

* Performs a weather check on each of the cities using a series of successive API calls.

* Includes a print log of each city as it's being processed with the city number and city name.

* Saves a CSV of all retrieved data and a PNG image for each scatter plot.

## Status
_finished_

## Inspiration
This project was assigned as part of the UTSA Data BootCamp.
