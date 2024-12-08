# Seattle Weather Prediction Model
1. Description: This data shows the rain record in Seattle, Washington, and St. Louis, Missouri, from 2017 to 2022. Below are the data sources.
2. Data: This data set showcases the daily precipitation measured in Seattle and St. Louis from January 1, 2017, to December 31, 2022. The data sets were downloaded from the National Centers for Environmental Information NOAA Climate https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND.
3. The data sets seattle_rain.csv and stl_rain.csv can be accessed from the Github repository for DATA 3320 in the weather folder.

  Seattle Rain: https://github.com/brian-fischer/DATA-3320/blob/87e2c1a561ab4364364cfe2fd5d1e6578c147153/weather/seattle_rain.csv\
  
  STL Rain: https://github.com/brian-fischer/DATA-3320/blob/87e2c1a561ab4364364cfe2fd5d1e6578c147153/weather/stl_rain.csv

4. Data Preparation: This is the process of identifying missing values and imputing data, thus creating a clean dataset version. The method includes joining datasets to identify missing values; an algorithm imputes data using the average precipitation of the days in the years. The dataset is also put in a tidy format for better readability.

5. Data Analysis: This is the process of analyzing the cleaned data to answer whether Seattle rains more than St. Louis. Three sub-questions were posted to help provide a more detailed lens into the data. The three questions are:

     1. How many days a year does it rain in Seattle and St. Louis?
     2. What is the frequency distribution of daily precipitation in Seattle and St. Louis?
     3. How has the average monthly precipitation in Seattle and St. Louis changed?

From the three questions, we can conclude that Seattle experiences more rain than St. Louis. We can also notice a seasonal pattern: Seattle rains more in the Fall and Winter months, whereas St. Louis rains more evenly throughout the year. In addition, St. Louis also experiences more dry days than Seattle. Even though St. Louis's rainy days are more evenly distributed, Seattle still has more rainy days; therefor,e Seattle rains more than St. Louis.
