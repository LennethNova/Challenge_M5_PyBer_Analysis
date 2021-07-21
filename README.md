# Challenge_M5_PyBer_Analysis
challenge

# PyBer with Matplotlib

## Overview of Project
Based on the given data, there is a need to analize the information in order to obtain the visualizations to understand what can be done to show the differences in ride-sharing data among different city types (rural, suburban and urban), this will help so possible changes can be made in order to generate improvements that could lead to better incomes.

### This project includes:
- Total rides
- Total drivers
- Total fares
- Average fare per ride
- Average fare per driver
- Total fare by city type
- Weekly fares per city type

### Purpose
Summarize the data in order to get the differences by city type so it can be used for decision-making at Pyber. 

## Analysis and Challenges
To make this challenge there is a need to know the code that will be used in order to accomplish the task; it is also important to know how to make DataFrames in the correct way and assign the corresponding index when making one. The use of groupby, sum, pivot, loc, resample and making graphs is also an important knowledge to apply in this project.

![Merged](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/merge_01.PNG)
![Group](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/merge_02_by%20type.PNG)

### Analysis of outcomes based on total rides
As seen on the image below, under the total rides column, the *City Type* with the most rides is **Urban**, while the one with the least total rides is **Rural**. As shown, the "Urban" has the highest number of rides with 1,625; then "Suburban with 625 and, in the end, "Rural" with 125 total rides, making it the one with the lowest number of rides.

![Total Rides](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/summary_01.PNG)

### Analysis of outcomes based on total drivers
As shown in the image, in the total drivers column, the *City Type* with the most drivers is the **Urban** with a total number of 2,405, in second place is the **Suburban** with 490 and, in third place is the **Rural** with 78 drivers in total. 

![Total Drivers](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/summary_01.PNG)

### Analysis of outcomes based on total fares
![Total Fares](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/total_fares.png)

By observing the image, the one *City Type* with the biggest income is **Urban**, and the lowest is **Rural**. The total fares for each *City Type* is *Urban* in first place with an income of *$39,854.38*, the second place is for *Suburban* with *$19,356.33* and, the las place goes for *Rural* with a total fare income of *$4,327.93*. By adding all, it gives a total fare of **$63,538.64**.

### Analysis of outcomes based on average fare per ride
The image shows, in the corresponding column, that the one with the highest average fare per ride is **Rural**, while the lowest is **Urban**. Paying attention to the image, it can be seen that *rural* has an average fare per ride of $34.62, while *suburban* has an average of $30.97 and *urban* has an average fare per ride of $24.53, making it the lowest from the others.

![Average fare per ride](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/summary_01.PNG)

### Analysis of outcomes based on average fare per driver
The *City Type* with the highest average fare per driver is the **Rural** one with an average of $55.49, in second place comes the **Suburban** with an average of $39.50 and in last place comes the **Urban** *City Type* with an average fare per driver of $16.57. This is as shown under the average fare per driver column.

[Total average fare per driver](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/summary_01.PNG)

### Analysis of outcomes based on total fare by city type
By watching the line graph for the total fare by *City Type* it can be seen that the one with the highest total fare is **Urban**, followed by **Suburban** and, in the end **Rural**. In the case of ***Urban*** there seems to be an increase of fares during April and February but also,there are ups and downs during March, while in January there seems to be a slow growth on the total fares. Talking about ***Suburban*** it seems to e a good start in January but there is an increase fare during February that colapses during March but with a slow growth following a decrease at the beginning of April and then an increse again later. ***Rural*** presents a relatively increase at the end of March and at the beginning of April and also, during a little part of February, but during a part of March is relatively low, despite this, during the beginning of January presents a decrease and some ups and downs, it also seems that April starts well but then it lowers again during the month.

![Total fare by city type](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

### Analysis of outcomes based on weekly fares per city type
Using the same graph as before, it seems that one of the worst weeks for the total fare in the case of Urban and Suburban City Types is the beginning of January, but fortunately it increses during the same week; while in Rural, the fare decreses during the end of the first week, making it the one with a significant decrease. The highest week of the fares for *Urban* are the increase in the third week from February and the increase during the end of the first week of March, while the lowest is at the beginning of January. For *Suburban* The highest is during the end of the second week and the start of the third week and the lowest is during the start of January, followed by the end of the first week of April, and it's lowest fare is during the start of the first week of January followed by the end of the first week of April. Now, for the *Rural*, it can be seen that the highest peak is during the las week of March and the start of April, while it's lowest is during the end of the first week of January.

![Weekly fares per city type](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

### Challenges and Difficulties Encountered
One of the first difficulties encountered while making the challenge was the index code at the beginning and using the pivot in order to organize the dates. Also, there was a need to add in the graph part, some additional code that was commented in order to recognize the weeks for a better analysis.

![index](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/resample_per_week.PNG)
![dates](https://github.com/LennethNova/Challenge_M5_PyBer_Analysis/blob/main/analysis/pivot_01.PNG)

## Results
***Recommendations:***
- There seems to be a higher income generated from the *urban* part, but at the same time there are more drivers there, it would be interesting to gather information regarding the zones that have a higher use for the service in order to determine if the number of drivers there, are the adequate amount or, if there is a need to increase or decrease the number. This is so the drivers could also get a benefit from the possible income.
- The *suburban* part seems to be the most balanced one, with a better average fare per driver thanks to the amount of rides and the amount of drivers. It would be also helpful to gather data in order to know the hours with higher demand of service in order to provide a better experience for the users and a chance for drivers to increase their income.
- For the *rural* area, it would be useful to also check the areas and hours that have a higher rate in service so the drivers could be prepared when they are needed. It would also be useful to check the average distances that the drivers use to travel in order to get the real income and also check their gasoline expenses to also compare it to what they really earn.
- The focus should be making less drivers for the *urban* part since they are too many, or distribute them in a better way so their income can increase; check the *rural* population and distances in order to provide a better service and income for the drivers; and for the *suburban* type, try to not add more drivers and gather the data in order to assign them to a better spot so the service can fulfull the costumer's needs.
