# PyBer_Challenge_Analysis

______________________________________________

## Overview of the analysis: 
______________________________________________

After working as a data analyst at PyBer a ride sharing app company and completing our first big project. Our CEO V. Isualize has assigned me and Omar with a new project. Working with the ride share date we will create a summary DataFrame by city pertaining to the ride-sharing data. We will share our summary for V.Isualize in a multiple line graph to support the data we have compiled into our summary. We will display the total weekly fares for eac city type using the ride share data. With the information dathered in our DataFrame and the story we can convey through our graph, we will summarize the variance in the data by city type. We will explain how the data can be used to make decisions and forecast business strategy by Pyber.

In our approach I started by using the [city_data](https://github.com/Kevin-Cutler/PyBer_Analysis/blob/main/Resources/city_data.csv) and [ride_data](https://github.com/Kevin-Cutler/PyBer_Analysis/blob/main/Resources/ride_data.csv) CSV to review my data source. This is a key step when completing any data analysis because it helps guide the road map for the destination ahead. We must overcome any potential roadblocks in our data that might misguide us in our review. When looking at the data from each files I notice their are no null values, I review the data type of each value in each column. If any of the data is not converted to the correct format this will throw errors in our analysis and impede our process, we must make sure to conirm all data types. To initialize our analysis we must also find out how manay data points there are for each city to prepare ourselves in organizing DataFrames and running our anlysis.

____________________________
  
# Results:
____________________________



### Ride-Sharing Data Among the Different City Types. 
___________________________________

The data captured in my analysis shows that there are more Total Rides in Urban Cities at 1,625. This also shows that their are more 2,405 Total Drivers in Urban Cities due to the demand for rides. The Total Fares in Urban Cities is $39,854.38 due to the higher volume of rides but among Rural and Suburban cities the Avg Fare per Rides for the Urban Cities is the lowest at $24.53 among all the cities. The Avg Fare per Driver in the Urban cities is $16.57 which is the lowest matched up to the Suburban and Rural Cities. Due to the demand of rides in the Urban Cities there is more volume for rides but that volume is shared among more Total Drives and in opposition Rural Cities on avergae attain $38.92 dollars more than Urban Drives based on the data below.


### Total Rides, Total Drivers, Total Fares, Average Fare Per Ride and Driver, and Total Fare by City Type.
_________________________________________

<img width="380" alt="Pyber_Summary" src="https://user-images.githubusercontent.com/88467263/135772109-b4953a4e-a010-4e7c-b9cd-33fa0de9e111.PNG">

<img width="607" alt="Multi_Line_Plot" src="https://user-images.githubusercontent.com/88467263/135772113-733355cf-47ec-434e-87cb-20ace96dce08.PNG">

## Summary: Recommendations for Disparities Among the City Types.

My review of the PyBer Ride-Sharing Data has lead me to believe that riders in Rural ares which can be more spread out are paying higher cost for rides and impacted by a lower driver counts at 78 which is less accomodating that the Suburban and Urban Cities. The drivers in the Urban Cities are in competition with more drivers to aquire business but recieve a smaller proportion of the funds due to the lower average fare but higher Total Driver count.

1. In my first recommendation to the CEO I believe we should look at avg distance of trips among drivers and the avg fares per ride among drivers by city. I believe this will help with a few alternatives I have in re-vamping the ride share sturcture. I believe that using the data in this anaylsis may help by determining a zoning structure for drivers where most needed. This will create a more balanced zone for drivers to service riders based on the area where theyre most needed and the frequent need for drivers in that area. This will help introduce my next recommendations which is to adjust the price per ride to benefit customers and evenly price Rural, Urban, and Suburban Cities.

2. With the anaylsis I have completed with review of the ride-share data I believe there is an opportunity to enhance user experience. The Rural cities may have less consumer trips due to the higher prices. From the data we can see that customers in Rural areas are paying more on average than the Urban and Suburban Cities. After review of data we should create a more equal price range for riders across all cities, we can average out the price for all cities to increase our influence in Rural and Suburban areas. Adjusting prices and designating drivers by zones can help increase business across cities. 

3. Finally in review of the Ride-Sharing data we can see from the graph that there are increased demand in all cities around the end of Februray into March and also in April. I believe we can designate research among consumers and determine what increases user experience during these months. If we can capatilize and create improvent each month while also leveraging feedback or focus groups with drivers, this can help determine what changes they notice during the more active and less active months. 
