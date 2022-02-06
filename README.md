# PyBer Ride-sharing Analysis
## Overview of the analysis
We use Pandas and Matplotlib to compare and analyze ride-sharing data between different city types from PyBer and recommend solution to address disparities among city types to help PyBer improve access and affordability. 
## Results
### Analysis of data for each city types
- Analysis of total rides, total drivers, total fares, average fare per ride and average fare per driver from rural, suburban, and urban city types from PyBer data from January to May in 2019 is shown in table 1. <br/>
Table 1. PyBer Summary<br/>
![pyber_summary](/Analysis/pyber_summary.png)<br/>
   - From the data, urban cities have the highest number of total rides, total drivers, and total fare while the average fare per ride and per driver are the lowest. Rural cities have the lowest number of total rides, total drivers and total fare while the average fare per ride and average fare per driver are the highest.  Data for suburban cities are in the middle. 
   - Considering the population is significantly more dense and concentrated in urban cities than suburban and rural areas, naturally there will be higher demand for rides in urban areas which drives more drivers to go to urban cities. High demand and high supply results in more drivers than rides in urban cities, which is the opposite in rural and suburban areas with less drivers than rides. There are around 1.5 more drivers than rides in urban cities and average fare per driver receive is around 1.5 less than average fare per ride. 
   - For suburban areas, total number of rides and drivers are in similar range (600 vs 500) so the average fare per ride approximately equals to average fare per driver. In the rural area, it is the opposite of urban cities where the demand is low, and supply is lower. There are less drivers than rides so average fare per ride is higher and average fare per driver doubles the average fare per ride.
### Analysis of weekly fare for each city type
- We also analyze the weekly total fare for each city type from January to April in 2019, shown in figure 1. The overall trend of total fare in rural, suburban, and urban cities is generally the same over four months period with minor differences. Total fare increases from January to February and decreases from March to April, particularly in urban cities. The weekly overall total fare is similar to the total fare that fare is significant higher in urban cities than suburban and rural areas and rural cities have the lowest fare. 
![pyber_weekly_fare_summary](/Analysis/PyBer_fare_summary.png)<br/>
Figure 1. PyBer Weekly Fare Summary<br/>
- In conclusion, it is more affordable and accessible for ride-sharing in urban cities than rural cities. And it is more competitive for drivers in urban cities and more competitive for riders in rural cities for ride-sharing service. 
## Summary
Based on the results of the ride-sharing analysis between different city types, we propose three recommendations to address the disparities among city types to increase access and affordability.
### Proposal
1. There are significant less rides in rural and suburban areas compared to urban cities. The low number of drives make rides in rural and suburban less accessible and affordable. We could provide promotions and discounts in rural and suburban areas to motivate riders in these areas.
2. There is higher supply than demand for drivers in urban cities than other types of cities. To increase number of rides and affordability in rural and suburban areas, we should also promote more drivers in rural and suburban cities than urban cities by incentives like discount on gas price or service fees in these areas. 
3. The weekly fare among city types shows a similar general trend for all three city types however there are minor differences. We should analyze weekly or quarterly fare trend over the past few years to find if there is difference between urban, suburban and rural cities so we can promote and allocate riding services based on demand. For example, there may be increased demand for riding during holiday time in rural and suburban areas than urban areas then we can target it. 
