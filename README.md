# python-api-challenge

UofA Data Analytics Bootcamp Homework Assignment 06-Python-APIs

### Assignment Description

Retrieve and analyze the current weather at locations around the world. Then determine which cities have the best vacation weather and display on a Google Map with a hotel name to start your vacation planning process.

### Analysis Results Website
<a href="https://nicolelund.github.io/webDesign-weatherAnalysis/index.html" target="_blank">https://nicolelund.github.io/webDesign-weatherAnalysis/index.html</a>

### Folder Descriptions
* "assignment_source_files" contains the original assignment details posted on the course GitLab site.
* "WeatherPy" samples the current weather at 500+ cities around the world and displays various scatter plots and regression analyses on the data.
    * WeatherPy.ipynb: Jupyter notebook for the analysis.
    * api_keys.py: Generic api key storage file.
    * input_data: The archived weather data file provided in the original homework assignment files.
    * output_data: The output files from the most recent run of WeatherPy.ipynb
    * WeatherPy_20210422_results: Results for the case when the user chooses to collect current weather data through calls to the Weather API.
    * WeatherPy_invalid_user_input_results: Results for the case when the user selects an invalid option for if they want to load current weather data or saved weather data.
    * WeatherPy_SampleData_results: Results for the case when the user chooses to read an archived weather data file.

* "VacationPY" reads the output from WeatherPy, identifies cities with ideal weather conditions, finds a hotel in that city and plots the results over a Google heatmap of humidity intensity.
    * VacationPy.ipynb: Jupyter notebook for the analysis.
    * api_keys.py: Generic api key storage file.
    * input_data: The archived weather data file provided in the original homework assignment files.
    * VacationPy_results: Screen captures of the resulting notebook and figures.
    
### Additional Resources
The analysis results webpage source code can be viewed at 

<a href="https://github.com/NicoleLund/webDesign-weatherAnalysis.git" target="_blank">https://github.com/NicoleLund/webDesign-weatherAnalysis.git</a>