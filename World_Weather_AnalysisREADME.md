# World Weather Analysis

## World Weather Analysis Challenge Overview

### The Company we have been working with has assigned us with the following deliverables:

Deliverable 1: Retrieve Weather Data

Deliverable 2: Create a Customer Travel Destinations Map

Deliverable 3: Create a Travel Itinerary Map

### The purpose of these deliverables is as follows:

The company and beta testers love the World Weather Analysis completed so far. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Deliverable 1: Weather_Database

Generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

A sample of the DataFrame with the Updated Weather Data:

![__](https://github.com/Johnnytoobadman/World_Weather_Analysis/blob/main/Weather_Database/Sample%20Weather_Database%20output.png)

## Deliverable 2: Vacation_Search

Use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

Input statement:

![__](https://github.com/Johnnytoobadman/World_Weather_Analysis/blob/main/Vacation_Search/Use_input%20screenshot.png)

Map of Markers Generated from the initial random sampling and the input criteria:

![__](https://github.com/Johnnytoobadman/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)

## Deliverable 3: Weather_Itinerary

Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary.

Route chosen:

![__](https://github.com/Johnnytoobadman/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)

Route cities with Markers:

![__](https://github.com/Johnnytoobadman/World_Weather_Analysis/blob/main/Vacation_Itinerary/Weatherpy_travel_map_markers.png)
