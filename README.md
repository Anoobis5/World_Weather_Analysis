# World_Weather_Analysis

## Project Overview
For this project we were tasked with helping make a few changes to the PlanMyTrip app. We refactored code to meet the demands of both the client and users. Specifically, we added weather descriptions to our weather data, and applied input statements so that users can filter weather data based on their ideal preferrences. This new user input criteria will help identify potential travel destinations and nearby hotels based on their weather preferences. Our code will produce a list of ideal destinations, where our Beta Testers will choose 4 cities to create a travel itinerary, and create a travel route between the 4 selected cities with a marker layer using Goole Maps Directions API.

### Weather Database: 

We generated a set of 2,000 random latitudes and longitudes, and made an API call for current weather data for the nearby cities.

We made an API call to retrive the following data:
  * Latitude and Longitude
  * Maximum Temperature
  * Percent Humidity
  * Percent Cloudiness
  * Wind Speed
  * Current Weather Description

Our data for the API call is visualized in the DataFrame table below:

![WeatherApi_Data_Pull](https://user-images.githubusercontent.com/84881187/126082683-258eb45f-f8ac-4e9e-96d4-bf94702b141e.PNG)

### Vacation Search:

Once users input their preferred preferences, a map will allow users to identify potential travel destinations and nearby hotels using pop-up markers:

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/84881187/126083228-fd4c3e8a-9b2f-4adb-9fc4-7a6d8ffb1bb7.PNG)
![WeatherPy_vacation_map_markers_info](https://user-images.githubusercontent.com/84881187/126083230-c3084c14-e691-417a-9c99-536f2fe60962.PNG)

### Vacation Itinerary:

Using Google Directions API, a route between the four chosen cities was visualized. For our visualization example, our sample itinerary created a route between four cities in Brazil that met our weather criteria:

![WeatherPy_travel_map_markers_Brazil_2](https://user-images.githubusercontent.com/84881187/126083668-06342052-f91b-41db-a3d1-5a489fd3f6fa.PNG)
![WeatherPy_travel_map](https://user-images.githubusercontent.com/84881187/126083707-ecc3f676-b982-4081-979b-b9418d86729e.PNG)



## Project Summary

Our code allows for users of the PlanMyTrip app to customize their travel experience 1-step further. Our users can now select a travel destination based on weather criterion that meets their ideal Minimum & Maximum preference, and be provided with options of cities to visit, as well as nearby hotels. The maps provide pop-up markers that generate that data to help users guide their decision. Once the users have selected which four cities they would like to visit, an itinerary and route can be created to aid them on their adventure. 

Our code helpsm users decide on their travel destination by weather preference, but there are many other variables we would parse through to help decide the best travel destination. When filtering through weather criteria, the map generated can be very overwhelming with choices. We could refactor the code to include variables that could help narrow down their travel options. One input we could include could be which continent or country they would like to visit. 

Another bit of data worth looking into incorporating for the users of PlanMyTrip, would be the duration or mode of transportation option input. Our data creates an itinerary based on the users driving to each city. It would be helpful for the travelers if they were able to pick which mode of transportation, varying modes of transportation, and how long each trip between cities would be.

The PlanMyTrip app was received very well by Beta Testers. The new changges proposed do indeed help take the app to the next level, and provide valuable information for the users. The PlanMyTrip database has a lot to offer its users, and future feedback will help the app grow. Please consider surveying users on the above suggested features. 




