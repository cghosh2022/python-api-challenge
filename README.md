# Python-API-Challenge
## Part 1: WeatherPy
In this deliverable, we created a Python script to visualize the weather of over 500 cities 
of varying distances from the equator. We used the ```citipy Python library```, 
the ```OpenWeatherMap API```, to create a representative model of weather across cities.

We started with generating random geographic coordinates and the nearest city to each latitude
and longitude combination provided.

1: Created Plots to Showcase the Relationship Between Weather Variables and Latitude
We used the OpenWeatherMap API to retrieve weather data from the cities list generated in the 
starter code. Next, we created a series of scatter plots to showcase the following 
relationships:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

2: Computed Linear Regression for Each Relationship
Computed the linear regression for each relationship. 
Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and 
Southern Hemisphere (less than 0 degrees latitude). 

Next, created a series of scatter plots. We included the linear regression line, the 
model's formula, and the r values.

We created the following plots:
* Northern Hemisphere: Temperature vs. Latitude
* Southern Hemisphere: Temperature vs. Latitude
* Northern Hemisphere: Humidity vs. Latitude
* Southern Hemisphere: Humidity vs. Latitude
* Northern Hemisphere: Cloudiness vs. Latitude
* Southern Hemisphere: Cloudiness vs. Latitude
* Northern Hemisphere: Wind Speed vs. Latitude
* Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explained what the linear regression is modeling. Described any 
relationships that was noticed.

## Part 2: VacationPy
We used weather data skills to plan future vacations. 
We used Jupyter notebooks, the geoViews Python library, and the Geoapify API.

We used the Geoapify API and the geoViews Python library and Python to create map visualizations.

1. Created a map that displays a point for every city in the city_data_df DataFrame.
The size of the point should be the humidity in each city.

2. Narrowed down the city_data_df DataFrame to find my ideal weather condition. 

3. Created a new DataFrame called hotel_df to store the city, country, coordinates, and 
humidity.

4. For each city, used the Geoapify API to find the first hotel located within 10,000 meters of 
your coordinates.

5. Added the hotel name and the country as additional information in the hover message for each
city on the map.

