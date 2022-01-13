# Analysis of Bike-sharing in NYC

## Overview
This project was undertaken with the intention to develop a dashboard on Tableau to visualize how ride-sharing works in NYC. A Tableau story containing four story points for analysis was developed and published on the Tableau server. The story utilizes data from the month of August downloaded from the citibike page. August was considered since it a popular summer month, which might contribute to higher bike usage. The story can be accessed via the below link:

[NYC Citibike Usage Story](https://public.tableau.com/app/profile/dhanushree/viz/CitiBikeUsage_Challenge/Story1?publish=yes)

The dashboard can be used to understand:
- The hourly distribution of bike rentals
- Bike rentals by user type
- Bike rentals by gender
- Average trip duration by birth year
- Popular starting locations
- Bike checkouts for all riders and genders
- Trips taken by hour, day of the week for all riders and genders
- Trips taken by day of the week, user type for all genders
- Bike utilization for each bike by number of rides and trip duration

## Results
The dashboard has been visualized using four story points:

**Overview of NYC Citi Bike Usage**

![Overview](https://github.com/Dhanushree27/Bikesharing/blob/main/images/NYC%20Citbike%20Usage.PNG)

This story showed us  that bike rentals are higher in the evening, between 4pm to 7pm, with a peak at 5pm. In the morning hours, a peak was seen at 8am. It was also observed that 81.07% of the riders are subscribers. In terms of male to female ratio, the percentage of total rides was 65.28% to 25.10%. From the average trip duration by birth year, it was observed that it is becoming increasingingly popular among the younger generation. The map showed that bike rentals are more popular in the midtown area. 
The dashboard also has the provision for interactive analysis on the below points:
- Any hour of the day can be selected to view how the other statistics change based on selection
- Likewise, the user can click on subscriber or customer segments of the chart to see the change in usage for each user type
- Similary, the user can click on any of the gender segments to view the corresponding change
- The user can adjust the slider on the map to see distribution in other areas on the map

**Bike checkouts for all riders and genders**

![Bike checkouts](https://github.com/Dhanushree27/Bikesharing/blob/main/images/Bike%20Checkouts.PNG)

This story provides graphical representations of bike checkout duration by the minute for each hour of the day. It provides an overall view for all riders as well as a gender based classification. From the data, it was seen that bike usage in minimal in the early hours of the morning, which makes it an ideal time to carry out repairs.
The story also has the provision to filter and compare for different hours of the day. The user can also filter based on gender, if required.

**Bike rentals by hour and day of the week**

![Trip Duration](https://github.com/Dhanushree27/Bikesharing/blob/main/images/Trip%20Distribution.PNG)

This story provides the user with multiple heatmaps. The heatmap of bike rentals by the day of the week and hour of the day demonstrated that bike rentals are popular during peak hours on the weekdays, whereas it is popular during the afternoon on weekends. A similar distribution can be seen on the classification by gender, with an insight that bike rentals are more popular among men. Additionally, it was seen that there is some usage by men during the early hours of the morning on weekends. The heatmap for bike rentals by user type and gender showed that bike rentals are most popular among male subscribers. The highest rentals are on Thursday. The user can filter on gender and usertype, if required

**Utilization per Bike**

![Utilization](https://github.com/Dhanushree27/Bikesharing/blob/main/images/Bike%20Utilization.PNG)

The last story point tells the story of the utilization for each bike by the number of rides as well as the total duration of usage. This can be utilized to identify which bikes were used the most and might need repair. The dashboard is interactive and can be used to observe the total duration of usage based on the number of rides and vice versa. The user can select one or multiple bikes and the corresponding data will be filtered on the other chart.

## Summary

The dashboard tells the story of citibike usage during the month of August in New York City. The dashboard also has provisions for interactiions as well as exploratory analysis which will be useful when drilling down to details. The overview provides a summary and corresponding sheets provide a more detailed analysis.
From the analysis, the below insights were derived:
- Bike rentals are higher during peak hours, especially on weekdays. On weekends, usage is higher during afternoon hours
- Bike rentals are higher among male subscribers
- Bike rentals are popular in midtown area in NYC, followed by downtown
- Bike rentals are becoming increasingly popular among the younger generation

**Suggestions for other visualizations**
Using the interactions provided in the overview dashboard, users can visualize:
a. Influence of age and gender on bike rental. From the resulting chart, it can be seen that a higher number of younger women are renting bikes
b. Influence of age on user types
c. Relationshiop between hour of the day and starting locations

In addition to the above, the below visualizations can also be created:
- Classify trip duration into bins and see the number of rides taken for each bin.
- Peak hour for each location by filtering the hour with the maximum count. This can be represented on a map with a color coding for the hour



