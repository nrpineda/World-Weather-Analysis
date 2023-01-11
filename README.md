# World-Weather-Analysis

## Purpose
We use the weather description data we've retrieved to enhance the PlanMyTrip app. Then, we will have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels within the app.

## Process

We generated a set of 2,000 random coordinates while performing API calls to the OpenWeatherMap. With those we created Pandas DataFrames that we then used to hold the data that we retrieved from the API call. 
With these DataFrames and with the GeoViews libraries we then created several maps with different parameters such as, maximum temperature per city retrieved, cities that are within a country that fall into a minimum temperature of 75 degrees to a maximum of 90 degrees as a parameter; and finally, one map that holds a route in between those preferred cities that follow the desired temperatures for visitors using the PlanMyTrip app. 
We created a Customer Travel Destinations Map, identifying with the data imported into our notebooks, the cities and their nearby hotels with the costumer's preferences.

## Result

Below is a map reflecting a route of four different cities in France that follow our parameters for an ideal vacation!

![WeatherPy_travel_map](https://user-images.githubusercontent.com/111472338/211737228-4fcb914e-c0b4-45c8-a191-f2d85656e4ec.png)
