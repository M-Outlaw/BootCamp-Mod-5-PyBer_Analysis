# BootCamp-Mod-5-PyBer_Analysis
Performing analysis on Pyber's ride sharing data to provide visualizations to indentify ways of encourging more usage of their services.

## Overview of Project

### Purpose
The purpose of this analysis is to use Python visualizations to determine trends in the cities where Pyber is available. Then using the trends,  provide information for Pyber executives to determine how they can improve both access and affordability to ride sharing services.

## Analysis and Challenges
### Data
- Two sources of data were provided:
  * city data, which includes the cites where Pyber is available, how many drivers are in each city, and whether each city is urban, suburban, or rural.
  * ride data, which includes the rides in each city during the months of January through May of 2019.

### Initial Analysis
- First, both sets of data were reviewed in python to make sure there were not any NaN values in the data and to determine initial values within the data:
  * the data types of each column of data
  * the three types of cities (Urban, Suburban, Rural)
  * the number of each type of city
   - 66 Urban Cities
   - 36 Suburban Cities
   - 18 Rural Cities

- Then, since both data sets include the cities, the sets were merged into one DataFrame.

- With the data merges, other analysis can be determined:
  * The number of rides taken in each city.
  * The average fare for each city type.
  * 

- A bubble plot was created for each city type showing the relationship between the average fare and the number of rides. All bubble plots showed little to no correlation.

<p align="center"><img src="" width="342" height="344"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="" width="342" height="344"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="" width="342" height="344"/></p>

- However, after combining the bubble plots into one chart, a correlation between average fares being highest in rural areas and least in urban areas. From the size of the bubbles, it can be seen that the average number of rides was highest in urban areas and least in rural areas.

<p align="center"><img src="" width="342" height="344"/></p>

- The correlation between the number of rides and the type of city is further shown by the statistics:

<p align="center"><img src="" width="342" height="344"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="" width="342" height="344"/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="" width="342" height="344"/></p>

- The total fares for all cities were determined and the percents of fares per city types were used to create a pie chart.

<p align="center"><img src="" width="342" height="344"/></p>

- The total number of rides for all cities were determined and the percents of the total number of rides per city types were used to create a pie chart.

<p align="center"><img src="" width="342" height="344"/></p>

The total number of drivers for all cities were determined and the percents of the number of drivers per city types were used to create a pie chart.

<p align="center"><img src="" width="342" height="344"/></p>

#### Summary
- Then, a summary of the merged DataFrame 

<p align="center"><img src="" width="342" height="344"/></p>

### Summary Plot
- Finally, a line plot of all city types were graphed together to show the fare values over the months of January to May in 2019.

<p align="center"><img src="" width="342" height="344"/></p>

## Results
### By City

### Recommendation
