# Python API project - Weather

## Summary
This project dealt with creating a Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. To accomplish this, a simple Python library called Citipy, the OpenWeatherMap API, and a little common sense were used to create a representative model of weather across world cities.

### Data Retrieval
Get a random list of around 500+ cities from the Citipy library. Then using that list on the OpenWeatherMap API to get a dataframe consisting of all the columns of relevant information needed in order to run an analysis. 

![Data_R](./WeatherPy/Figures/Datar.png?raw=true "Data_R")

![Data_R2](./WeatherPy/Figures/Datar2.png?raw=true "Data_R2")

####  Scatter plots showcasing relationships:

* Temperature (F) vs. Latitude

![fig1](./WeatherPy/Figures/fig1.png?raw=true "fig1")

* Humidity (%) vs. Latitude

![fig2](./WeatherPy/Figures/fig2.png?raw=true "fig2")

* Cloudiness (%) vs. Latitude

![fig3](./WeatherPy/Figures/fig4.png?raw=true "fig3")

* Wind Speed (mph) vs. Latitude

![fig4](./WeatherPy/Figures/fig4.png?raw=true "fig4")

#### Linear regression of each relationship:
(first separate them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).)

Plot the following:

* Northern Hemisphere - Temperature (F) vs. Latitude

![fig5](./WeatherPy/Figures/regress1.png?raw=true "fig5")

* Southern Hemisphere - Temperature (F) vs. Latitude

![fig6](./WeatherPy/Figures/regress2.png?raw=true "fig6")

* Northern Hemisphere - Humidity (%) vs. Latitude

![fig7](./WeatherPy/Figures/regress3.png?raw=true "fig7")

* Southern Hemisphere - Humidity (%) vs. Latitude

![fig8](./WeatherPy/Figures/regress4.png?raw=true "fig8")

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![fig9](./WeatherPy/Figures/regress5.png?raw=true "fig9")

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![fig10](./WeatherPy/Figures/regress6.png?raw=true "fig10")

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![fig11](./WeatherPy/Figures/regress7.png?raw=true "fig11")

* Southern Hemisphere - Wind Speed (mph) vs. Latitude

![fig12](./WeatherPy/Figures/regress8.png?raw=true "fig12")

### Analysis:
There seems to only be a correlation to Latitude as it relates to Temperature. Cloudiness, Windspeed, and Humidity have loose relationships at best to the latitude variable.
As far as the relationship between Northern and Southern Hemispheres, It does not seem to be a large difference statisically between the two in any of the categories analyzed. 
