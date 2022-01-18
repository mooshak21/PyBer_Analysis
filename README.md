# Pyber_Analysis

## Overview
The purpose of this analysis is to dive into the Pyber ride share data. Here we are completing a ridesharing summary using our Python skills of groupby dataframes on a certain aspect of the data columns (type/date). The overall goal is to create a multiple line graph to show the total weekly fares for each city type for the date range Jan 1, 2019 - April 28, 2019.

---

## Results
1. Urban cities had the most rides (1625) and drivers (2405) with the highest total fares ($39,854)
2. Suburban cities had the second most rides (625) and drivers (490) with second highest total fares ($19,356)
3. Rural cities had he least amount of rides (125) and drivers (78) with the least total fares ($4,327)
4. In order from least to greatest, the average fares per ride were urban, suburban, then rural
5. In order from least to greatest, the average fares per driver were urban, suburban, then rural

### Summary DataFrame
![](https://github.com/mooshak21/Pyber_Analysis/blob/main/analysis/fig2.png)

### Total Fares by City Type Plot
![](https://github.com/mooshak21/Pyber_Analysis/blob/main/analysis/Total_Fare_by_City_Type.png)

---

## Summary
There are some recommendations for updates to the ride-sharing program that could help result in more riders in certain areas:

1. One thing they could change is to change the cost of rides for people in rural areas because they have the least amount of riders for their city type. 
2. Another suggestion is to get more drivers in rural areas. Based on urban data, there are significantly more drivers than total rides which resulted in much more revenue. In rural areas we only have 78 drivers to the 125 total rides. If they increased the number of drivers, there might be a correlated increase in total rides and total revenue. 
3. Lastly, the average fare per ride for rural areas is the highest of the three city types. To combat this they should try to market their service more to people in these areas. Because rural areas probably require longer trips since destinations are further away, people probably don't think of using a ride-share service. Marketing and advertising for these types of people would greatly benefit the amount of riders and would probably attract more drivers in the area which would in turn lower the average fare. 