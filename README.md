## python-api-challenge

This project has three major components:
- Generating a random list of 613 cities generated using the citypy library and filtered down to 567 cities based on availability of data in the Open Weather API
- Using the Open Weather API to analyze temparature, humidity, wind speed, and cloudiness data in comparison to the latitude and longitude coordinates of each city
- Using the Geoapify API to analyze hotels found in cities filtered by ideal weather for vacationing (Max temp < 27C and > 21C, 0 Cloudiness, Wind Speed < 4.5m/s)

NOTE:
All weather data is in metric units, and associated csv and image files can be found in output_data folders in each analysis directory
