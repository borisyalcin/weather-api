# Weather Analysis
## Objective
* The objective of this project is to gather, analyze, and visualize weather data from various global locations to understand the relationships between key weather parameters. By leveraging the Open Weather API, we aim to explore how temperature, humidity, cloudiness, and latitude vary across different geographical locations, with a specific focus on comparing the northern and southern hemispheres.

## Data Collection
### API Used: 
Open Weather API
### Parameters Collected:
Temperature
Latitude
Humidity
Cloudiness
Geographical Location (hemisphere determination)
Tools and Libraries
### Python: 
Core programming language used for the project.
### Pandas: 
For data manipulation and analysis.
### NumPy: 
For numerical computations and array operations.
### Matplotlib: 
For data visualization and plotting.

## Methodology
### Data Gathering:

* Utilized the Open Weather API to collect weather data for various cities globally.
* Extracted key parameters such as temperature, latitude, humidity, and cloudiness.

### Data Processing:

* Employed Pandas to clean and structure the data.
* Used NumPy for efficient numerical operations and handling missing values.
* Determined the hemisphere (northern or southern) based on the latitude value.

### Data Analysis:

* Conducted exploratory data analysis (EDA) to understand the distribution and relationships between the variables.
* Compared weather parameters across the northern and southern hemispheres.
* Analyzed the correlation between latitude and temperature to study how temperature varies with distance from the equator.
* Investigated the relationship between humidity and cloudiness.

### Data Visualization:

* Created various plots using Matplotlib to visualize the data trends and relationships:
* Scatter plots to show the relationship between temperature and latitude.
* Bar charts to compare average humidity and cloudiness across different hemispheres.
* Line plots to depict temperature variations for selected cities.

### Key Findings
Temperature vs. Latitude: Observed a clear trend where temperatures generally decrease as one moves from the equator towards the poles.
Humidity Analysis: Noted distinct humidity patterns in the northern and southern hemispheres, potentially influenced by seasonal variations and geographical factors.
Cloudiness Patterns: Identified regions with consistently high or low cloudiness, offering insights into local climate conditions.

### Conclusion

#### MAX TEMPERATURE Vs. LATITUDE
When we look at the plot bar, we can realize that the trand located closer to the equator (lat=0) gets increased temperature. However there are some exceptions if we check the cities are not located on the equator. On both Southern and Northern Hemispehere have some cities havin higher temperature than the cities are located on 0 latitude. That basically means distance from the equator is not only reason for high temperature.

![01_MaxTemp_Latitude](https://github.com/borisyalcin/weather-api/assets/155834534/c0079626-474c-4197-b4db-b62f4067a7c1)

#### CLOUDINESS Vs. LATITUDE
When we look at the scatter plot below, it is almost imposible to see any correlation between cloudiness and latitude. Simply, we can assume that the amount of cloudiness is independent from that comparision.

![03_Cloudiness_Latitude](https://github.com/borisyalcin/weather-api/assets/155834534/e6f90f62-4d3b-429c-b161-b584ea376519)

#### HUMIDITY Vs. LATITUDE
When we check the figure below, we can say that the cities which having highest humidity are located between lat 20 and 60. Even though, latitude from 0 to 20 has the cities having the lowest humidty. According to our comparision, distance from equator might have some effect on the value of humidity.

![02_Humidity_Latitude](https://github.com/borisyalcin/weather-api/assets/155834534/4054573a-29c8-4fd0-936e-523a5b75bef5)

### Future Work
* Expanded Data Collection: Incorporate additional weather parameters like wind speed, precipitation, and atmospheric pressure.
* Temporal Analysis: Analyze weather patterns over time to study seasonal and long-term climatic changes.
* Machine Learning Models: Develop predictive models to forecast weather conditions based on historical data.
