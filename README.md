# PyBer_Analysis

## Overview of the analysis:
To make an analysis of PyBer ride sharing data, we created a `pyber_summary_df` to describe the total rides, total drivers, total fares, average fare per ride and average fare per driver for each rural, suburban and urban cities. This allowed us to notice the differences in profits of each city type. We also created a `weekly_timeframe_df` to look at how the total fares for each city type each week from 1/1/2019 - 4/29/2019 and plot this data on the line graph `PyBer_fare_summary.png` found within the analysis folder.


## Results:
Urban cities had the largest number of total rides, total drivers, and total fares followed by suburban cities and then rural cities, respectively. This relationship is inverted when we look at average fare per ride and average fare per driver. Within these two categories, rural cities is the highest average fares per ride and driver, followed by suburban cities and then urban cities. This is understandable because rural areas had much fewer rides and drivers than suburban and urban cities, and the average distance travelled for rural areas would most likely be further than the average distance travelled for suburban or urban cities. This would result in a larger average fare per ride and driver. Although the average fares are higher for rural cities, the total fares are much smaller than the other types of cities. Shown below is our `pyber_summary_df` describing total rides, total drivers, total fares, average fare per ride and average fare per driver for each rural, suburban and urban cities.

<img width="500" alt="pyber summary df" src=".\Resources\pyber_summary_df.png">

## Summary:
Urban cities have the largest number of rides and total fares, but we can see that there are more urban drivers than there are urban rides. Because urban cities have a larger workforce than there is work available, PyBer should build a program to incentivize new customers to use PyBer to help increase their number of total rides within urban cities and take advantage of the number of drivers they have available. 

Rural cities have the highest total rides to total drivers ratio (1.6), and perhaps there is too many rides for the drivers to take on. PyBer can consider using the high average fare per driver ($55.49) to attract more drivers for rural cities to potentially increase the total rides for these cities.

Looking at our Total Fare by City Type line graph shown below, we can see that there is a decrease in total fares for all three city types in the beginning of March. PyBer can consider giving its customers a discount for rides during this week to try to increase the number of rides for that week. The discount would affect the profit for the fare per ride, but potentially increase the total number of rides. A localized test to see if offering a discount for limited time to customers will increase total fares for that time frame could be used to determine if this will be effective. If the test is successful, PyBer can implement this during the weeks where total fares decrease.

<img width="500" alt="total fare by city type" src=".\analysis\PyBer_fare_summary.png">

