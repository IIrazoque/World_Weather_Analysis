# World_Weather_Analysis

## Objective
Using Google’s API we were to collected world wide coordinates to create the basic travel functions for PlanMyTrip application. 
### Deliverable 1  Weather Data 
Using OpenWeatherMap’s API we were able to generate 2,000 coordinates using the random ( ) module with the uniform function. Since ~70% of planet Earth is water, our true coordinates came down to ~780 true “land” coordinates. City data dataframe shown below

![this is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/city_data_dataframe.PNG)

Extracted current weather conditions to our city dataframe using JSON.

![This is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/Json%20weather%20description.PNG)

### Deliverable 2  Create a Customer Travel Destinations Map
We then used the input statements to retrieve cities and hotel details based of weather preferences (min and max temperature in F). Calling Google API were able to retrieve city, hotel, and max temperature listed on markers for the desire vacation spots. 
And lastly  remove any rows with “null” values. In our case, 5 rows were removed. 

![This is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/remove%20insull%20rows.PNG)

Marker layer map with pop-up Markers  

![This is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/Vacation_Search/WeatherPy_vacation_map.PNG)

### Deliverable 3 Create a Travel Itinerary Map
By activating the Google Directions API we created a basic travel itinerary showing the route between the cities from the customer’s travel destinations. 

![This is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/Vacation_Itinerary/WeatherPy_travel_map.PNG)

And lastly created a marker layer map with a pop-up marker for each city on the itinerary as shown below.

![This is an image]( https://github.com/IIrazoque/World_Weather_Analysis/blob/5e2d8871565688084de3ad737bae34048dae094b/Vacation_Itinerary/WeatherPy_travel_map_marker.PNG)
