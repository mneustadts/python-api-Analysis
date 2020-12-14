# Python API project - Weather

## Summary
In this project I was tasked with creating a Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. To accomplish this, I used a simple Python library called Citipy, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

### Firstly I created a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

### Secondly I ran a linear regression on each relationship
(first I separated them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).)

I plotted the following:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

Analysis: There seems to only be a correlation to Latitude as it relates to Temperature. Cloudiness, Windspeed, and Humidity have loose relationships at best to the latitude variable. As far as the relationship between Northern and Southern Hemispheres, It does not seem to be a large difference statisically between the two in any of the categories that I analyzed.
