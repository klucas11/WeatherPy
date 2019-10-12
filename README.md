# WeatherPy
This project answers the fundamental question: “What’s the weather like as we approach the equator?”.

To answer this question, I used a Python library called [citipy]( https://pypi.org/project/citipy/) and [The OpenWeatherMap API]( https://openweathermap.org/api) to create a script to visualize the weather in 500+ cities around the world of varying distance from the equator. My objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

### How To Run
* In the api_keys.py file, add your personal API key from OpenWeatherMap
* Run the WeatherPy.ipynb file from start to finish

### What To Expect
* During the API call in the WeatherPy.ipynb, you should see a print of the Data retrieved. The print should say:
“Processing _RecordNumber_ | _CityName_". If the city being called is not found, it will print "City not found. Skipping..."
* The data will be stored in a DataFrame and exported as a CSV
*	The data will then be plotted on four separate scatter plots showcasing the relationships mentioned above
*	The scatterplots will be saved as a .png file to your computer

### See the final Analysis
I used the dataset and image files in this repository to create a visualization dashboard website. Check out that repository [here]( https://github.com/klucas11/Web-Visualization-Dashboard-Latitude-) and see the final webpage with my analysis [here]( https://klucas11.github.io/Web-Visualization-Dashboard-Latitude-/).
