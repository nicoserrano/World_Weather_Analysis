# World_Weather_Analysis
#### Weather analysis and travel recommendation with maps and directions of +600 cities around the World.  


## Overview 
The goal of this project was to retrieve weather data using OpenWeather API to then help PlanMyTrip Co. create a customer travel destination map with more than 600 cities. Moreover, I used the Google Maps API to come up with one hotel recommendation for each city. And lastly, I created a travel itinerary map where I chose 4 neighboor cities to come up with a full travel and directions guide. 

## Resources
- Data sources:
  - WeatherPy_Database.csv
  - WeatherPy_vacation.csv
- Software:
  - Python 6.3.1
  - Jupyter Notebook
  - Pandas, citipy, scipy, requests, gmaps, and numpy libraries and dependencies
  - OpenWeather and Google Maps APIs

## Results

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/83378141/123011452-6a780780-d38e-11eb-9463-80d66ba87d19.png)

The code retrieved weather data for more than 600 hundred cities around the World. A map was created will all these cities displaying their location, country, current weather description, and max temperature. After that, the customer was able to input their temperature preferences which would then filter the dataframe to a couple houndred cities. With this filtered dataframe of cities I found the nearest hotel using Google Maps API to serve as a travel recommendation to our customers.

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/83378141/123013109-9052db80-d391-11eb-9e0d-ea551b9048ad.png)

![WeatherPy_travel_map](https://user-images.githubusercontent.com/83378141/123013150-ab255000-d391-11eb-8301-548b831361b6.png)


Finally, our customers were also given a suggested trip with an itinerary and driving directions to all four cities. 



