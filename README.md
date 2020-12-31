# Python API project - Weather

## Summary
In this project I was tasked with creating a Python script to visualize the weather of 500+ cities across the world, at varying distances from the equator. To accomplish this, I used a simple Python library called Citipy, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

### Data Retrieval
I started by getting a random list of around 500+ cities from the Citipy library. Then using that list I called on the OpenWeatherMap API to get a dataframe consisting of all the columns of relevant information I needed in ordr to run my analysis. 

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
(first I separated them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).)

I plotted the following:

* Northern Hemisphere - Temperature (F) vs. Latitude

![fig5](./WeatherPy/Figures/fig5.png?raw=true "fig5")

* Southern Hemisphere - Temperature (F) vs. Latitude

![fig6](./WeatherPy/Figures/fig6.png?raw=true "fig6")

* Northern Hemisphere - Humidity (%) vs. Latitude

![fig7](./WeatherPy/Figures/fig7.png?raw=true "fig7")

* Southern Hemisphere - Humidity (%) vs. Latitude

![fig8](./WeatherPy/Figures/fig8.png?raw=true "fig8")

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![fig9](./WeatherPy/Figures/fig9.png?raw=true "fig9")

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![fig10](./WeatherPy/Figures/fig10.png?raw=true "fig10")

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![fig11](./WeatherPy/Figures/fig11.png?raw=true "fig11")

* Southern Hemisphere - Wind Speed (mph) vs. Latitude

![fig12](./WeatherPy/Figures/fig12.png?raw=true "fig12")

### Analysis:
There seems to only be a correlation to Latitude as it relates to Temperature. Cloudiness, Windspeed, and Humidity have loose relationships at best to the latitude variable.
As far as the relationship between Northern and Southern Hemispheres, It does not seem to be a large difference statisically between the two in any of the categories that I analyzed. 
