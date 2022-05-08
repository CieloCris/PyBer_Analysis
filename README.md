# PyBer Analysis

## Overview

In this project, we worked for PyBer and our boss V. Isualize assigned us the task of creating and analyzing a summary DataFrame about the ride-sharing data by city type (Urban, Suburban, and Rural). Our boss also gave us the purpose of creating a Multiple Line Graph that showed the weekly total fares by type of city.

So, our **purpose** was to analyze the differences in Pyber ride-sharing data according to the city type, we also had the goal to compare the rides' fares in Urban, Suburban, and Rural cities. Our analysis can help our boss and the company to make better decisions.

For our analysis, we used Jupyter Notebook, Pandas Library, and Matplotlib Library. Our data source was two csv files: city_data.csv, and
ride_data.csv

To achieve our purpose, we first created the DataFrame using different pandas methods and functions, such as merge, groupby, count, sum, pivot, among others. After that, we used Matplotlib to create the multiple-line graph. 

## Results 

As we can see in the DataFrame, the Urban City Type has more rides and drivers than the Suburban and Rural City Type. Despite that, the average fare per ride and the fare per driver in Urban cities are lower than in Rural and Suburban cities.

#### Ride-sharing data by city type
![Alt text](/Resources/dataframe1.png "imagen1")

We can also deduce that Rural cities have fewer rides and drivers, but the average fare per ride and the average fare per driver are higher because rural areas are less populated than other City Types, which also implies fewer PyBer drivers and rides. We can conclude that in the Rural City Type there is less demand for rides, although to verify this idea we have to analyze other elements, such as distance, time, and weather conditions in the cities.

The following figure shows a multilinear graph that helps us to visualize and analyze the total fares for weeks from January to April 2019 in each City Type (Urban, Suburban, and Rural).

#### Total weekly fares for each city type
![Alt text](/Resources/PyBer_fare_summary.png "imagen2")

In this plot, we can observe that Urban City Types had the highest total fares for the weeks from January to April of 2019. On the contrary, the Rural City Types had the lower fares.
We can also see that the third week of February has the highest total fares of each City Type. 

## Summary

This analysis shows that Urban cities provide higher revenues to PyBer even though have the lowest average fare per ride and driver. We can say that the rural cities have higher costs because there are fewer drivers and rides in those places. The time and distance of the ride can be elements related to the increase in fares in rural areas.

 ### Recommendations:
- We need to know more about the necessities of the rural population areas to increase ride-sharing and drivers in that city type.
- Reduce the cost of rides in the Suburban and Rural cities to increase the number of users.
- Urban areas have the best performance for the company. That is why it's important to keep investing in this city type. For example and as a strategy, we can offer incentives to keep loyal customers using PyBer.
- Our analysis has some limitations, the suggestion is to extend the analysis. For instance, this study requires more data to analyze, such as distance traveled, demographic data of the population, and weather conditions of the city.
