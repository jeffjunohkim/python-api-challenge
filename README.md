# python-api-challenge

# Summary of WeatherPy and VacationPy

## Overview

Both `WeatherPy.ipynb` and `VacationPy.ipynb` are Jupyter Notebooks that perform weather data analysis and visualization. They utilize various Python libraries to collect, process, and visualize weather data for cities around the world. Additionally, they use the Geoapify API to find nearby hotels and create interactive maps using Folium.

## Common Features

- **Data Collection**: Retrieve weather data for multiple cities worldwide using the OpenWeatherMap API.
- **Data Cleaning**: Process and clean the collected data to ensure accuracy and completeness.
- **Hotel Search**: Use the Geoapify API to find nearby hotels for each city.
- **Data Visualization**: Create interactive maps with markers for each city, showing weather conditions and hotel information.
- **Interactivity**: Include hover functionality to display additional information for each city on the map.

## Specifics of WeatherPy

### Key Outputs
1. **Weather Data Collection**: Collect weather data such as temperature, humidity, wind speed, and cloudiness for a wide range of cities.
2. **Data Filtering**: Filter cities based on ideal weather conditions defined by the user, resulting in a subset of cities that meet these criteria.
3. **Hotel Data Collection**: For each filtered city, find the nearest hotel within a specified radius and store the hotel's name and location.
4. **Data Visualization**: Create an interactive map using Folium. Each city is marked with a colored dot, where the color is unique to the city and the size of the dot represents the humidity level. Hovering over a dot displays detailed information including the city's name, country, latitude, longitude, humidity, and the nearest hotel's name.

### Goals
- Identify cities with ideal weather conditions.
- Find suitable accommodations (hotels) near these cities.
- Visualize the results on an interactive map for easy reference and analysis.

## Specifics of VacationPy

### Key Outputs
1. **Weather Data Collection**: Similar to WeatherPy, it collects weather data for multiple cities worldwide.
2. **Data Filtering**: Focus on filtering cities based on ideal vacation weather conditions (e.g., pleasant temperature range, low wind speed, minimal cloudiness).
3. **Hotel Data Collection**: Use the Geoapify API to find the nearest hotels for the cities that meet the vacation weather criteria.
4. **Data Visualization**: Create an interactive map with Folium. Each city is marked with a colored dot, where the dot size is based on humidity and the color is unique to each city. The map includes detailed popups and tooltips with information about the city, weather conditions, and nearby hotels.

### Goals
- Help users plan vacations by identifying cities with optimal weather conditions.
- Provide information on nearby hotels to facilitate travel planning.
- Offer a visual tool (interactive map) for users to explore potential vacation destinations and accommodations.

## Requirements

Both notebooks require the following Python libraries:
- pandas
- numpy
- requests
- hvplot
- geoviews
- folium

API keys from:
- OpenWeatherMap for weather data.
- Geoapify for finding nearby hotels.


## Conclusion

Both `WeatherPy` and `VacationPy` provide powerful tools for analyzing weather data and planning trips. They offer detailed visualizations and interactive maps to help users make informed decisions based on weather conditions and available accommodations. Whether you're looking for the best weather for a trip or planning a vacation with specific weather preferences, these notebooks provide the necessary insights and tools to assist you.

## Code Source
1. Learning Assistant
2. GitHub location: git@github.com:jeffjunohkim/python-api-challenge.git