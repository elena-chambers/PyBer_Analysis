# PyBer_Analysis


## Overview 
Pyber, a rideshare company, has requested ride and city data analysis in order to detect patterns, trends, and outliers. 

An outline of tasks completed:
- Import and merge ride and city data into a Pandas DataFrame.
- Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
- Determine the mean, median, and mode for the following:
  - The total number of rides for each city type.
  - The average fares for each city type.
  - The total number of drivers for each city type.
- Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
  - The number of rides for each city type.
  - The fares for each city type.
  - The number of drivers for each city type.
- Create a pie chart that visualizes each of the following data for each city type:
  - The percent of total fares.
  - The percent of total rides.
  - The percent of total drivers.
- Create a summary DataFrame of the ride-sharing data by city type  
- Create a multi-line graph that shows the total weekly fares for each city type between January 1st 2019 to April 29th 2019.

## Resouces
- Data Souce: city_data.csv, ride_data.csv
- Software: Python 3.8.8, Jupyter Lab 1.4.1

## Results and Analysis
<img width="620" alt="Screen Shot 2021-10-31 at 2 53 06 PM" src="https://user-images.githubusercontent.com/91163155/139599304-61fb8379-fc4f-49ee-912b-a590cfe928d7.png">
This summary dataframe shows that urban cities utalize the rideshare app with more frequence than surban or rural cities, however the cost per ride is substanitally lower. Revenue per urban ride is less than revenue per rural ride, but urban rides account for the majoity of revenue.  

##### Bubble Chart for All Cities
![Fig1](https://user-images.githubusercontent.com/91163155/139599681-05daf68a-e215-478a-bb81-8b181cfc7c2d.png)

The majority of rides in 2019 are in urban cities and have the lowest fare per ride. Conversely, there are fewer rural rides, but have substantially higher fare costs. Sububan cities are in the middle. 

##### Box and Whisker
| Number of Rides by City Type | Fare by City Type | Number of Drivers by City Type |
|- | - | - |
|![Fig2](https://user-images.githubusercontent.com/91163155/139599747-40c45b9e-61fa-4225-9395-ce5ff51cfc43.png) |![Fig3](https://user-images.githubusercontent.com/91163155/139599748-8776259f-e72c-4d6d-8281-9edf06c57767.png) |![Fig4](https://user-images.githubusercontent.com/91163155/139599752-136ce750-22db-44e6-9093-464bb9e0ce51.png)|



| percent of total fares | percent of total rides | percent of total drivers |
|- | - | - |
|![Fig5](https://user-images.githubusercontent.com/91163155/139599929-a73eef1d-d3f3-4d11-8b1d-a2892cdbde68.png) |![Fig6](https://user-images.githubusercontent.com/91163155/139599933-724bb3c5-1a3c-48da-94af-42617138a8ca.png) |![Fig7](https://user-images.githubusercontent.com/91163155/139599937-13f949eb-6ebe-42e4-8c6c-41faaa7a12a2.png)|




![PyBer_fare_summary](https://user-images.githubusercontent.com/91163155/139599959-e2531290-e9ae-4a96-bcdd-e221be3aadae.png)




## Summary
In order to address the disparies seen in rideshare costs between urban rural cities seen in both the number of drivers, rides, and fare prices, I reccommend further analysis that would include distance traveled, so that we can better understand why rural rides cost more than urban rides. For example, if the cost per mile traveled in urban verus cost per mile traveled in rural rides is different, we can find ways to equalize cost while promoting rural rides. Additionally, since urban rides make up most of the revenu, we should look into why there are dips in number of rides in Janurary and focus more investments in continuting the trends we are seeing in March-April. Subruban rides are the middle performers, and investment would be best utalized increasing use in urban areas and increase rides in rural areas that have a larger profit margin.  
