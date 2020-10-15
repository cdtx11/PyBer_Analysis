# PyBer_Analysis
Ride Share anlysis with Python, Pandas, and matplotlib

## Overview of Analysis
The purpose of the analysis was to create a summary DataFrame about ride sharing data by city type. Some of the data in this DataFrame included total rides, drivers, fares, and average fares by city or per ride. Based on this dataframe, I also created a line graph visualization to show total weekly fares for each city type. These visualizations make it easy to compare characteristics by city type. 


## Results
### Differences in ride sharing data among different city types:

Looking at the summary dataframe, it is clear that a low supply of drivers in rural cities has affected average fare per ride and per driver. Because there are not many drivers, demand is higher proportionally and this drives up fare prices. Additionally, less total rides means rural cities make up a small portion of total fares. On the other hand, there are many more drivers in urban cities, meaning the average fare per ride and per driver is lower, and total fares is much larger than total fares for rural and suburban cities. As you would expect, suburban cities fall in the middle of rural and urban for all aspects summarized. 

The multiple line chart shows this data over time, and that the data by city type seems to be consistent over time. This means total fare by city types also has Urban cities with the most total fares, suburban with the second most total fares, and rural with the least total fares. This order does not change over the time frame included in this graph. 

From these graphs I would conclude that operating in urban cities is most successful because total fares is highest, and fare per and per driver are least expensive, leading to a positive customer experience.

**PyBer Summary DataFrame**
![](/PyBer_Summary_DF.png)

**Fare by City Type Line Graph** 
![](/analysis/PyBer_fare_summary.png)

## Summary
### 3 Business Recommendations for Addressing Disparities Among the City Types

My first recommendation for addressing disparities among city types would be to add more drivers to rural cities. This should even out supply and demand, brining down average fare per ride and per driver. 

My next recommendation would be to run more advertisements in rural cities in order to attract new customers and increase the total number of rides in rural cities. 

Finally, I would also increase the number of drivers in suburban cities. It seems that urban cities seem to be the most successful with the highest total fares, and lowest average fare per ride and driver. I believe this is due to the fact that there are more drivers than rides. To match the success of urban cities, you should try making total drivers in suburban cities more than or equal to the total rides. 