# PyBer Ride-Sharing Analysis

## Overview
PyBer's CEO has requested an analysis for ride-sharing data to help the company improve access to ridesharing services and determine affordability to underserved neighborhoods. Our analysis will create visualizations of our ride-share data aggregated by city type - Rural, Suburban and Urban and viewed over time. The visualizations will assist in understanding the relationship between drivers, riders and type of city.  I'll also provide my three recommendations for the business based on this data analysis.

## Results

### City Type Summary Data

We first aggregated data by each city type - Urban, Suburban, and Rural - to view number of rides, number of drivers and total fare amounts.  We also calculated the average price of a fare and average fare by driver the city type.  You can see this data in the following chart: 

![City Type Totals](/analysis/City_Type_Totals_Averages_DF.png)

In this chart, we can see that 
- Rural and Suburban average fare per ride is greater than Urban drivers by $10 and $6 respectively
- Rural and suburban drivers make more per trip but there are significantly fewer trips made in both categories when compared to urban rides
  - Urban drivers had 13 times more trips than Rural drivers 
  - Urban drivers had 3 times as many as suburban drivers
- Urban drivers make significantly less per driver than rural and suburban drivers when we take the total fare divided by the total number of drivers
- Rural has the highest average fare per ride at $35 followed by suburban at $31 and then Urban at $25
- The urban driver count exceeds the number of rides available indicating some drivers didn't earn a fare

### Total Weekly Fares by City Type

We charted out the total fare amounts each week by city type over a 4-month period in 2019.  Viewing the data over time, we can evaluate if there are significant changes in the amounts earned every week as well as how each city type compares with the others.  Below is the chart rendered to show Fares over Time for each City Type:  

![Fare Summary](/analysis/PyBer_fare_summary.png)

From this chart, we can see that all three city types have relatively consistent fares earned each week in their category - urban has the highest fares each week, followed by suburban and then rural.  There are no overlaps in our lines and the min/max fares in each city type do not show huge swings. There is a slight overall upward trend of total fares in the Urban category with no dips in the 4-month period as low as the minimum which occurred in the first week in January.

## Summary

Based on this data analysis, I would recommend investigating the following three business changes:

1. Decrease the per fare price in rural communities to improve affordability
2. Decrease the number of Total Drivers in Urban areas to reduce the number of drivers that earned no fares
3. Possibly increase the number of Drivers in Rural areas - A further investigation of ride requests abandoned would be helpful to determining if this is necessary.  If the existing number of drivers fully served the requests, this might not be necessary.  If ride requests went unfulfilled, then the increase would be prudent.
