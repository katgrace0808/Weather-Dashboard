# [Weather Dashboard] (https://katgrace0808.github.io/Weather-Dashboard/)

Weather dashboard for users to find weather conditions for where they intend to travel (or just for places that they dream of going).

## Description

This is a weather dashboard that supplies the weather for a location entere by the end user.  When you enter the application,
you are presented with a search bar.  A user will enter a city name and click the search button.  Once clicked, the searched 
city will populate on the screen with the current date, along with the current temperature, humidity, wind speed, and UV Index.  
The UV Index will present as a color to indicate if it is in an acceptable range (green), a warning range (yellow) or danger range (red).
As well, an icon is presented to reflect the weather.

Below that, the next five day forecast is called, showing the date, temperature, and humidity, as well as an icon depicting the weather.  

When the page is refreshed, the user's last search is saved to a button.

## Development of the Application

This was a fun activity, though frustrating at times.  I initially created the application using bootstrap and no dynamically created elements.  
I then created a separate html and javascript page with dynamically created elements, and it was much nicer to be able to have a shorter 
code to work with, and it was satisfying to see what I created present on the html page in Inspect.  

I am still having issues with local storage, though it does call it back.  I also was unable to get my event listener to work for the stored
city.  