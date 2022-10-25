# Module_6_Challenge
Intro and purpose:
'In this class we are learning that the true power of data comes when it is used to inform decisions and answer questions. 
In this project, the task is to take what we've learned about Python requests, APIs, and JSON traversals to answer the question: "What is the weather like as we approach the equator?"

This assignment consists of two .ipynb files WeatherPy and VacationPy, one .cvs file, WeatherPy.csv, and a api_key file. 

The WeatherPy notebook will not run with out an api_key. The user will have to provide their own key and store it in a repo titled 'api_key.py'. Additionally, the VacationPy notebook will not run without a key for google labeled g_key. That key will also need to be stored in the 'api_key' repo.Provided is sample syntax required to import the keys ex(from api_keys import weather_api_key)

WeatherPy is a jupyter notebook that contains data and analysis that will answer the primary question listed above. In addition, the data from WeatherPy is saved as a .cvs file which serves as the starter data for the VacationPy notebook. The csv file contains City, Lat, Lng, and Country data.

The VacationPy notebook takes in WeatherPy.csv City, Lat, Lng, and Country information to allow the assessment of potential vacation spots based on several variables such as temperature, cloudiness, and wind speed. After a series of filters are applied to the data, the remaining lat/lng infomration is used to identify hotels at the potential vacation spots. Once the hotels are identified, there locations are plotted on the map using gmaps. The map also contains a heat map identifying cloudy areas. 


