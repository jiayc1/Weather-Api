# Weather-Api

Website Link: https://jiayc1.github.io/Weather-Api/
## Acceptance Criteria

![Alt text](img/search.png?raw=true "search")

GIVEN a weather dashboard with form inputs
1. WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
- When you add type a city to the search bar, it should load the current day weather forecast of the city and the next five day forecast. 

2. WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index

- The weather conditions should we shown with the city name, the day date, temperature, humidity, wind speed, uv index, and the icon. 


3. WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
 
- There is a uv index that shows whether the uv index is healthy or moderate, or danger based on color. Green means healthy, yellow means moderate, and red means danger for uv rays. 

4. WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, and the humidity

- There is a 5 day forecast displayed with the day. I decided to use moment Js to display the day rather than the date because I do not like the way it look. There is also an icon that shows the temperature along with the description describing the weather, wind speed, the temperature and the humidity. 

5. WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city

- When you click on the city in your search history, you are able to view the current adn future conditions for that city again. In addition there is a clear button that will allow you to clear your history if needed to restart. 

6. WHEN I open the weather dashboard
THEN I am presented with the last searched city forecast

- When you open the weather dashboard you will then also be able to see the last searched city forecast. 

![Alt text](img/multiple.png?raw=true "multiple")

