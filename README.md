# BootCamp-Mod-5-PyBer_Analysis
Performing analysis on Pyber's ride sharing data to provide visualizations to identify ways of encouraging more usage of their services.

## Overview of Project

### Purpose
The purpose of this analysis is to use Python visualizations to determine trends in the cities where Pyber is available. Then using the trends, provide information for Pyber executives to determine how they can improve both access and affordability to ride sharing services.

## Analysis and Challenges
### Data
- Two sources of data were provided:
  * City data, which includes the cites where Pyber is available, how many drivers are in each city, and whether each city is urban, suburban, or rural.
  * Ride data, which includes the rides in each city during the months of January through May of 2019.

### Initial Analysis
- First, both sets of data were reviewed in python to make sure there were not any NaN values in the data and to determine initial values within the data:
  * The data types of each column of data
  * The three types of cities (Urban, Suburban, Rural)
  * The number of each type of city
   - 66 Urban Cities
   - 36 Suburban Cities
   - 18 Rural Cities

- Then, since both data sets include the cities, the sets were merged into one DataFrame.

- With the data merges, other analysis can be determined:
  * The number of rides taken in each city.
  * The average fare for each city type.

- A bubble plot was created for each city type showing the relationship between the average fare and the number of rides. All bubble plots showed little to no correlation.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Average_Fare_per_rides_Urban.png" width="301.6" height="205.6"/>&nbsp;<img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Average_Fare_per_rides_Suburban.png" width="301.6" height="205.6"/>&nbsp;<img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Average_Fare_per_rides_Rural.png" width="301.6" height="205.6"/></p>

- However, after combining the bubble plots into one chart, a correlation between average fares being highest in rural areas and least in urban areas. From the size of the bubbles, it can be seen that the average number of rides was highest in urban areas and least in rural areas.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Average_Fare_per_rides_All.png"/></p>

- The correlation between the number of rides and the type of city is further shown by the statistics:

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Boxplot_All_rides.png" width="278.5" height="178.5"/>&nbsp;&nbsp;&nbsp;<img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Boxplot_All_fare.png" width="278.5" height="178.5"/>&nbsp;&nbsp;&nbsp;<img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Boxplot_All_drivers.png" width="278.5" height="178.5"/></p>

- The total fares for all cities were determined and the percents of fares per city types were used to create a pie chart.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Piechart_Fare.png" width="320" height="296"/></p>

- The total number of rides for all cities were determined and the percents of the total number of rides per city types were used to create a pie chart.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Piechart_rides.png" width="320" height="296"/></p>

The total number of drivers for all cities were determined and the percents of the number of drivers per city types were used to create a pie chart.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Piechart_drivers.png" width="320" height="296"/></p>

#### Summary Table
- Then, a summary of the merged DataFrame 

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/Summary.png" width="666" height="138"/></p>

### Summary Plot
- Finally, a line plot of all city types was graphed together to show the fare values over the months of January to May in 2019.

<p align="center"><img src="https://github.com/M-Outlaw/BootCamp-Mod-5-PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png"/></p>

## Results
### Total Rides
- Suburban cities had 5 times as many rides as rural cities.
- Urban cities had 2.6 times as many rides as suburban cities.
- Urban cities had 13 times as many rides as rural cities

### Total Drivers
- Suburban cities had a little over 6 times as many drivers as rural cities.
- Urban cities had almost 5 times as many drivers as suburban cities.
- Urban cities had almost 31 times as many drivers as rural cities

### Total Fares
- Suburban cities had about 4.5 times the total amount of fares as rural cities.
- Urban cities had about 2 times the total amount of fares as suburban cities.
- Urban cities had about 9 times the total amount of fares as rural cities

### Average Fare per Ride
- The average fare per ride for suburban cities were about 90% of the cost of the average fares per ride for rural cities.
- The average fare per ride for urban cities were about 80% of the cost of the average fares per ride for suburban cities.
- The average fare per ride for urban cities were about 70% of the cost of the average fares per ride for rural cities.

### Average Fare per Driver
- The average fare per driver for suburban cities were about 70% of the cost of the average fares per ride for rural cities.
- The average fare per driver for urban cities were about 40% of the cost of the average fares per ride for suburban cities.
- The average fare per driver for urban cities were about 30% of the cost of the average fares per ride for rural cities.

### Recommendation
- There is a large difference in all of the components between rural areas and urban areas with suburban areas between the two.
- There are 3 recommendations to try to bring the rural and suburban areas up to the great stats seen in the urban areas.
  1) While urban areas inherently have a larger population, more shops and restaurants, and promotes more ride sharing, making the ride sharing more accessible by employing more drivers in rural and suburban areas could increase the number of rides. When less drivers are available, people tend to not rely on the service because it is harder to get a ride when they need it. Hiring more drivers would reduce wait times in getting the ride.
  2) Providing more advertising, especially in rural areas, would also be helpful, because in rural areas people may be less familiar with ride share services or that their city has one.
  3) Reducing the fare price for rural and suburban areas would also encourage people to use these services. In urban areas, where it is harder to find parking, ride sharing can be charged a premium. A reduced price for less populous areas would promote more buisiness. 
