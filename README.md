# Bike Sharing (CitiBike)

## Overview 

For this project, I was tasked with creating a proposal for potential investors, regarding the possibility of setting up a bike-sharing program in Des Moines, IA. By using bike-sharing data taken from an already established NY bike-sharing program, I created multiple data visualizations, using Tableau, to illustrate why I think a bike-sharing program would be successful. Tableau is a visual analytics program that transforms the way we all normally think of data, from various tables or multiple rows of numeric data points, into data that can be visualized and easily understood, by anyone. Tableau can take in massive datasets and allow the user to create multiple graphs/charts/maps/tables, and then be able to combine them all into what's known in Tableau as a 'story'. Creating a 'Story' in Tableau is just like it sounds, using the data to create data visualizations, and using those data visualizations to tell a story about the data. 

## Resources 
* Tableau
* Visual Studio Code 
* Pandas
* Data: [Citi Bike Sharing Dataset](https://github.com/Lucky777b/bikesharing/blob/main/Resources/201908-citibike-tripdata.csv.zip)

## Results 

To view the entire 'Bike Trip Analysis: CitiBike NYC' Story created on Tableau Public, please click link: 
[Bike Trip Analysis](https://public.tableau.com/app/profile/bethany.murillo/viz/BikeTripAnalysis_16626830048660/Story1)


Page 1) Overall Data Specs 

![Page 1](https://github.com/Lucky777b/bikesharing/blob/main/Resources/overall_data.png)

This page shows overall data specifications of the citibike data as a whole. There is a 'Customer Pie Chart', which represents how many more subscribers there are comparatively to how many customers use the bike sharing program. A 'Gender Pie Chart' is also included, to show a visual breakdown of how many 'Male', 'Female', or 'Unknown' users were found in the ride sharing data. There is a column for 'Unknown' because those users did not want to specify which gender they were, but it was still included in the data. At the bottom, there is a small table, which provides a numeric breakdown of users by 'Gender'. There is also an overall count of the total ride count for all users counted within the dataset. 


Page 2) Checkout Times For Users 

![Checkout Times for Users](https://github.com/Lucky777b/bikesharing/blob/main/Resources/Checkout_times_for_users.png)

This visualization illustrates the range of time that users checkout bikes, which is about 5-40 minutes on average. The highest peak sits around 10-15 min, and then decreases in users the higher the trip duration, and effectively hitting zero users checking out bikes before the first full hour. This shows that most users do not rent the bike for longer than an hour, but mostly use the bike to ride around in short increments.

Page 3) Checkout Times By Gender 

![Checkout Times by Gender](https://github.com/Lucky777b/bikesharing/blob/main/Resources/Checkout_times_by_gender.png)

This visualization illustrates the time of each user's tripduration, but is subdivided further by gender. The results show that male users predominantly use citibikes over female users, by about 65-70%. There is an unknown gender category, but it is such a small amount of users, that it does not effect the overall takeaway from this visualization.

Page 4) Trips By Weekday For Each Hour

![Trips by Weekday For Each Hour](https://github.com/Lucky777b/bikesharing/blob/main/Resources/Trips_by_weekday_for_each_hour.png)

This is a treemap that uses a color range, to show the frequency of users renting CitiBikes, by the day of the week, and the hour of each day. The darker the purple color, the higher the user count for that day and time. The lighter the purple color, the lower the user count for that day and time. 

Based on these results, the busiest times of day are between 7-10 am (Monday through Friday), and 5-7pm (Monday, Tuesday, Thursday, and Friday). 

Page 5) Trips By Gender(Weekday Per Hour) 

![Trips by Gender Weekday per hour](https://github.com/Lucky777b/bikesharing/blob/main/Resources/Trips_by_gender_weekdayPerHour.png)

This treemap shows the days and times(by the hour) that the majority of users use CitiBikes, but unlike the previous treemap, this one is divided by gender. Even though the amount of male users is much higher than the amount of female citibike users, both maps show that male and female users tend to use CitiBike between 7-10am (Monday through Friday), and 5-7pm (Monday, Tuesday, Thursday, and Friday)

Page 6) User Trips By Gender By Weekday 

![User Trips by Gender by Weekday](https://github.com/Lucky777b/bikesharing/blob/main/Resources/User_trips_by_gender_by_weekday.png)

This visualization breaks down the number of bike trips taken by each gender for each day of the week, and by each UserType (Customer or Subscriber). The result shows that Male Subscribers use CitiBike more than male customers, and more than female subscribers and customers, and have the highest trip counts on Monday, Tuesday, Thursday, and Friday. 

Page 7) Count of CitiBikes By Start Location ID

![Start Location ID Map](https://github.com/Lucky777b/bikesharing/blob/main/Resources/count_citibikes_start_locationID.png)

This map visualization provides insight as to where the majority of the users start their ride, which is determined by the count of how many bikes are counted at their 'Start Location ID'. The darker green represents a higher count, and illustrates where most users are starting their bike ride, while the brighter yellow color represents the areas where less bike rides are being started. 

Page 8) Count of CitiBikes By End Location ID

![End location ID Map](https://github.com/Lucky777b/bikesharing/blob/main/Resources/count_citibikes_end_locationID.png)

This map visualization was created to show where most users end their bike ride, which is also found to be higher inside the city. The brighter yellow colored dots show that there is a lower 'End Location ID' count the farther away from the city you go. 

The maps showing the count of the bike ride start location ID and the count of the bike ride end location ID, could have higher numbers within the city itself, because there might be more tourists in that area, and they might not need to travel as far in between locations within the city. These maps also make sense as to why most user's trip duration is about 5-15 minutes per ride, because the start location ID counts are found heavily within the same areas as the end location ID counts.


## Summary 

Based on the bikesharing data visualizations, there are a few things to take note of in regards to how the bikesharing program is being used, and what is important to consider when thinking of setting up this type of program in a new location. By looking at the 'User Trips by Gender by Weekday', 'Trips by Gender(Weekday per hour)', and 'Trips by Weekday for Each Hour', it can be concluded that male subscribers predominanently use the bikesharing program over female or unknown subscribers and customers. A couple reasons for this could be that males are more comfortable riding a bike in the city than females, who might feel safer riding in a car than on a bike. Another reason could be that there are more males than females working in that part of NYC, whether it be the type of jobs that are available in that area that attract a higher amount of male vs female applicants. It is also apparent that subscribers tend to use the bike sharing program much more often than customers, which means that the subscription plan is successful in encouraging those users to use the bike sharing program more often, that a customer who probably has to pay more per ride versus a subscriber.

The times that the bike sharing program is being utilized the most seem to be during higher traffic times, or before and after work times, which makes sense when one also considers the amount of time used per ride on average. Due to heavy traffic in NYC, it would make sense that one might turn to a bike sharing program to get to and from work every day, as opposed to driving, because the amount of time driving to work in a car could take much longer than just riding a bike the same distance. It also might be easier to use the bike sharing program because you wouldn't have to worry about finding a place to park your car each day, or pay for a monthly parking spot inside a parking garage, which could costly in comparison to being a subscriber for the bike sharing program. 

By looking at the 'Count of CitiBikes by Start Location ID' and 'Count of CitiBikes by End Location ID', it can be concluded that the usage is much higher in the middle of the city, and decreases the further away or out of the city, which can also support the reasoning that there might be heavier traffic in the areas where citibike count is the highest, and the traffic might be lighter in areas where the citibike count is lower. The start and ending location ID maps seem to show similar data, which could further support the 'Checkout Times by Gender' and 'Checkout Times for Users' charts, because the amount of time a user rents a bike ranges between 5-40min, but majority of users rent the bikes from about 5-15min, which means they aren't traveling very far. The fact that travel times are short provides support as to why the darker areas of the location ID maps are roughly in the same areas for both maps, for start and ending location.

A future analysis that might be helpful would be to create a visualization based on age, to see what age groups might be using the service more often than another age group. This could be helpful when thinking of how to market the bike sharing program in another area, for example, Des Moines, IA. If one age group uses the bike sharing program more than others, then it would be useful to know that, because then the company can determine which age groups might need to marketed to more, so then the company could try to bring in a wider variety of users for all age groups. 

Another analysis that could be helpful in bringing in more customers, would be to see whether the users that are not using the bike sharing program as much as in the less populated areas of NYC are using it for leisure or for daily commutes. By understanding whether the bike sharing program is used more for daily commute or for leisure, it could help the company determine whether they should adjust the pricing structure for daily commuters or leisurely commuters, for example, pay a fixed amount for a certain amount of rides per month versus having to fully subscribe at a fixed monthly cost. By providing such an option, it could influence those who do not need to use the program on a daily basis, to still use the bike sharing program because they can utilize the same benefits as a subscriber but won't have to continue paying a monthly fee, which could be a deterrent for those who do not need to rent a bike on a daily basis. 

