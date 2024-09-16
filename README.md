# Python API Challenge: WeatherPy and VacationPy

Welcome to the Python API Challenge! This repository is designed to apply knowledge of Python, APIs, and data visualization to analyze and visualize weather data.

![Image](https://miro.medium.com/v2/resize:fit:2000/format:webp/1*-0ZQ6_92FRf09oY53TzeYw.gif)

The following files are present inside the WeatherPy folder:

     WeatherPy.ipynb
     VacationPy.ipynb

## WeatherPy
This section, analyzes weather data from various cities to understand how weather variables relate to latitude.

### Visualize Weather Data:

Retrieve weather data using the OpenWeatherMap API for cities from the WeatherPy.ipynb notebook.

### Create scatter plots for:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed

### Compute Linear Regression:

Perform linear regression for each plot.
Separate plots into Northern Hemisphere (≥ 0° latitude) and Southern Hemisphere (< 0° latitude).
Include linear regression lines, formulas, and R² values in your plots.

## VacationPy
This section, uses weather data to find ideal vacation locations and map them.

### Map Visualization:
The size of each point should represent the city's humidity.

### Filter Cities:
Filter city_data_df to find cities with:
Max temperature between 21°C and 27°C
Wind speed < 4.5 m/s
Zero cloudiness

### Find Hotels:
Create a DataFrame hotel_df with cities that meet the criteria.
Use the Geoapify API to find the nearest hotel within 10,000 meters of each city.
Include hotel names and countries in the hover message on your map.

