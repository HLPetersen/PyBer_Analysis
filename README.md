# <b> PyBer Analysis </b>

## <u>Overview of Analysis</u>
PyBer is a a Python-based ridesharing app company. There are two datasets that this analysis is based on, city data and ride data. City data contains the number of drivers per city and the city type for 120 cities that use the app. 66 cities are urban, 36 are suburban, and 18 are rural. The ride data provides the city, date, fare, and ride id from 2,375 ride instances from January 1, 2019 to May 8, 2019.  

### Purpose of Analysis   
This is an exploratory analysis of the number of drivers and rides for PyBer based on the city type. The analysis will provide information to support and guide business decicions at the company based on the data. 

## <u>Analysis and Challenges</u>
The original data sets, city data and ride data, have 120 rows and 2,375 rows respectively. The first goal was to merge the data to be able to extract information about the number of drivers, city type, fare, and number of rides. The data was merged on the city column. 

<img width="300" alt="city data" src="https://user-images.githubusercontent.com/116980760/206324927-af551bd2-53df-4b8f-a0cc-1d7958ed81bd.PNG">  <img width="500" alt="ride data" src="https://user-images.githubusercontent.com/116980760/206324948-6f9be2fe-d07c-4499-86dd-438b48194323.PNG">

After combining the data, the next step was totaling the rides and fares; counting drivers; and finding average fares for drivers and rides for each city type. The data then was grouped by week to more easily see the trends.

### Challenges and Difficulties Encountered
When the data was merged, the driver count was duplicated for every ride that was taken in the city. Driver count had to come from the original city data to be accurate.


## <u>Results</u>
<img width="900" alt="Chart" src="https://user-images.githubusercontent.com/116980760/206323375-3c73fd17-2765-4d46-8495-b77d9e168c5e.PNG">

- The average fare per ride and per driver is higheest for rural cities. The next highest averages were for suburban cities, followed by urban cities. 
- The end of Februrary had a spike in total fares followed by a dip the beginning of March. 
- Most profits came from urban cities, but the most profitable rides were those in rural areas. 

![Fares](https://user-images.githubusercontent.com/116980760/206331516-a71dcbe8-e76f-4f16-b612-c6a5267cfdaa.png)

## <u>Recommendations<u>
  - Find out if the spike in February was due to some event. Plan on having as many drivers as possible during that time or during similar events across all city types.
  - Place priority on rural ride requests as they are the most profitable.
  - Try to recruit more drivers in rural and suburban areas as the average fares in these areas are higher.
  
