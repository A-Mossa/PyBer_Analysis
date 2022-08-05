# Pyber Analysis

## Overview of PyBer Analysis
In my second week as a data analyst at PyBer, a leading ride-sharing app, I've been assigned with the analysis of all the rideshare data from January to early May of 2019 and create a compelling visualization for the CEO, V. Isualize. Alongside my manager, Omar, a thourough analysis that is comprehensive and correct was carried out. Some of the points of analysis were :
1. Calculate the Total number of rides. 
2. Get a complete list of City types.
3. Obtain a definitive count of drivers per city type.
4. Calculate the total number of fares.
5. Determine the average fare per city type.
6. Determine the action needed based on the relation between different factors.

## Rideshare Data Analysis Results:
The analysis concluded the following outcomes:
- It's been concluded that there are three types of cities : Urban , Suburban, and Rural.
- Total rides in that time period were 2375 distributed : 1625 rides in urban cities, 625 in suburban cities , and last 125 rides in rural cities.
- Total Number of drivers in the specified period were 2973 and they were divided between Urban , Suburban and Rural cities respectively : 2405, 490 ,and 78.
- Total fares in USD$ between January and April 2019 was 63,538.64 and distributed between city types as follows :
  - Urabn cities with a total of $39.854.38
  - Suburban cities with a total of $19,356.33
  - Rural cities with a total of $4,327.93
 ![CityTypePivot](https://github.com/A-Mossa/PyBer_Analysis/blob/main/Citytype.png)
- The Average Fare per Ride for each city type was :
  - The highest were the rural cities with an average fare per ride of $34.62
  - At second place were the suburban cities with an average fare per ride of $30.97
  - The lowest averages were the urban cities with an average fare per ride of $24.53.
That wasn't unexpected, because there are more drivers in urban settings with the most amount of total rides.
- The Average Fare per Driver for each city type was :
  - The highest were the rural cities with an average fare per driver of $55.49
  - then comes the suburban cities with an average fare per ride of $39.50
  - Last but not least urban cities with an average of $16.57
![FareByCityType](https://github.com/A-Mossa/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Election-Audit Summary
The code utilized this audit is sufficient to carry out the same analysis of results to almost any similar situation with minor tweaks.
given the next project posses a similar database, the code can be slightly refactored to accomodate difference and changes if the desired outcome is of the same nature as this audit.

![Code_screenshot](https://github.com/A-Mossa/Election-Analysis/blob/main/PyPollCode.png)

For example, if in the future should the stake holders wish to include additional attributes, then more variables would be created and code would be slightly modified to govern the interaction between said variables.
