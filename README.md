# python-api-challenge_reja


# Background # 

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?


## Files ##

Downloaded the following files to get started:

Module 6 Challenge [files](https://courses.bootcampspot.com/courses/3819/assignments/56678?module_item_id=999527)

## Instructions ##

This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Part 1: WeatherPy ##

In this deliverable, created a Python script to visualize the weather of over 500 cities of varying distances from the equator. Used the **citipy** Python **libraryLinks** to an external site., the OpenWeatherMap APILinks to an external site., and created a representative model of weather across cities.

For this part, I used the **WeatherPy.ipynb** Jupyter notebook provided in the starter code ZIP file. The starter code guided me through the process of using my Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

### Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude ###

To fulfill the first requirement, I used the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, created a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature

- Latitude vs. Humidity

- Latitude vs. Cloudiness

- Latitude vs. Wind Speed

### Requirement 2: Compute Linear Regression for Each Relationship ###

To fulfill the second requirement, computed the linear regression for each relationship. Separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

Next, created a series of scatter plots. Also, created the following plots:

- Northern Hemisphere: Temperature vs. Latitude

- Southern Hemisphere: Temperature vs. Latitude

- Northern Hemisphere: Humidity vs. Latitude

- Southern Hemisphere: Humidity vs. Latitude

- Northern Hemisphere: Cloudiness vs. Latitude

- Southern Hemisphere: Cloudiness vs. Latitude

- Northern Hemisphere: Wind Speed vs. Latitude

- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explained what the linear regression is modeling. Described any relationships that I noticed and any other findings that uncovered.


