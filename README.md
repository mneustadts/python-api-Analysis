Python API Homework - What's the Weather Like?

Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"
Now, we know what you may be thinking: "Duh. It gets hotter..."
But, if pressed, how would you prove it?
Part I - WeatherPy
In this example, you'll be creating a Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. To accomplish this, you'll use a simple Python library called Citipy, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.
Your first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Your second requirement is to run a linear regression on each relationship, but first you must separate them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). This means you'll plot the following, complete with a regression line and y = mx + b equation:

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

After each pair of plots (i.e., northern and southern hemispheres) explain what the linear regression is modeling, comment on any relationships you notice, and include any other analysis you may have.
Optional: Since you're creating multiple linear regression plots, you could do this in a function. To optimize your code, write a function that creates the linear regression plots based on parameters you provide. Again, this step is optional.
Your final notebook must:

Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude.
Obtain the weather from each city using the OpenWeatherMap API.
Include a print log of each city as it's being processed, with the city number and city name.
Save a CSV of all retrieved data and a PNG image for each scatter plot.

Analysis: There seems to only be a correlation to Latitude as it relates to Temperature. Cloudiness, Windspeed, and Humidity have loose relationships at best to the latitude variable.
As far as the relationship between Northern and Southern Hemispheres, It does not seem to be a large difference statisically between the two in any of the categories that we analyzed. 
