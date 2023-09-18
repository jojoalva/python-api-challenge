# python-api-challenge
This challenge looked at whether the weather patterns changed as you got closer to the equator- WeatherPy looked at the following question:
      "What is the weather like as we approach the equator?"
      
 APIs were downloaded from: https://openweathermap.org/api

I generated a series of scatter plots to showcase the following relationships:

    Latitude vs. Temperature
    Latitude vs. Humidity
    Latitude vs. Cloudiness
    Latitude vs. Wind Speed
    
These, along with a .csv file for the next notebook VacationPy, you will find saved in the output_data folder.

I then computed a linear regression graph for the following relationships:
  
    Northern Hemisphere: Temperature vs. Latitude
    Southern Hemisphere: Temperature vs. Latitude
    Northern Hemisphere: Humidity vs. Latitude
    Southern Hemisphere: Humidity vs. Latitude
    Northern Hemisphere: Cloudiness vs. Latitude
    Southern Hemisphere: Cloudiness vs. Latitude
    Northern Hemisphere: Wind Speed vs. Latitude
    Southern Hemisphere: Wind Speed vs. Latitude
    
VacationPy then looked at a subset of these random locations generated from WeatherPy, and using specificed parameters, found hotels to possibly stay at whilst on vacation there.
This was done using the APIs generated from: https://www.geoapify.com/geocoding-api

How to install / use :
Once you have downloaded the repository files, ensure you have saved a new .py file called api_keys in the same location. Ensure you have downloaded your API keys from the above-mentioned websites.
Ensure you save them as a variable in the .py file you have just created to match the variable name in the code!
**If you do not save it as the same variable, your code will not work! You will otherwise have to edit the code to match the variable you've called your api key in your apy_keys.py file.
