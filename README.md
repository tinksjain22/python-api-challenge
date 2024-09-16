# Python API Challenge: WeatherPy and VacationPy

Welcome to the Python API Challenge! This repository is designed to apply knowledge of Python, APIs, and data visualization to analyze and visualize weather data.

![Nature Climate change](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41558-019-0670-y/MediaObjects/41558_2019_670_Fig1_HTML.png)
[Source](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.nature.com%2Farticles%2Fs41558-019-0670-y&psig=AOvVaw04f9_5XN-RAtQxRH7RKWpS&ust=1726597145858000&source=images&cd=vfe&opi=89978449&ved=0CBcQjhxqFwoTCLD10eaJyIgDFQAAAAAdAAAAABAn)

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

