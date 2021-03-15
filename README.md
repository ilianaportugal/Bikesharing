# Bikesharing

## Overview
The purpose of this analysis is to help investors interested in launching a bikesharing program in Des Moines understand user behavior. In this analysis, we are looking at New York bikesharing data for the month of August. I used Python to perform data transformation and Tableau to create visualizations that highlight trends in the data. View the Tableau dashboard by clicking the link below. 

[link to dashboard](https://public.tableau.com/profile/iliana5134#!/vizhome/BikesharingChallenge/BikesharingChallenge)


## Results

### Checkout Times for Users

<img src="Images/Checkout Times for Users.png" width="1000">

The "Checkout Times for Users" chart tells us that most users have a trip duration of about 5 hours. The average trip duration is likely between 5-7 hours. The curve is right skewed, meaning the mode is higher than the mean. After 5 hours, the amount of trips slopes down. This visual can aid us in product design and pricing. Investors need to ensure their bike is comfortable for all day use. The price of the bikesharing program should take into account trip duration, we should ask ourselves the question "what will our users be willing to pay for 5 hours of use?".

### Checkout Times by Gender

<img src="Images/Checkout Times by Gender.png" width="1200">

The "Checkout Times by Gender" chart shows us that there is a large difference in the trip duration curve for men compared to women. The trip duration curve is flatter for women, meaning less women participate in the bikesharing program than men. As trip duration increases past 5 hours, we see the difference in total riders by gender decrease. Both curves for men and women experience fewer riders as trip duration increases. From this chart we obtain valuable information about the gender of our target market, most bikesharing users are male. In our marketing efforts and product design the gender of our user should be heavily considered. 

### Trips by Weekday

<img src="Images/Trips by Weekday.png" width="600">

The "Trips by Weekday" chart shows us that there is an increase in trip activity during the weekday between 7am-9am and 4pm-7pm. On the weekends, there is a steady amount of activity during the day from 10am-6pm. From this data we can tell that users are using the bikesharing program to commute to work and as a weekend activity.

### Trips by Gender

<img src="Images/Trips by Gender.png" width="1000">

From the heatmap "Trips by Gender", we can tell that most users are male, they take more trips than females and unknown. The heatmap for male and female users follow the same trends we saw in the 'Trips by Weekday' visualization. 

### Trips by Gender by Weekday

<img src="Images/Trips by Gender by Weekday.png" width="400">

Subscribers are more likely than customers to share their gender. We see higher trip activity for male and female subscribers on Monday, Tuesday, Thursday and Friday. Overall, we see that male subscribers have the highest trip count.

### Starting and Ending Locations

<img src="Images/Start_End Locations.png" width="1000">

In the "Starting and Ending Locations Map", both starting and ending locations are concentrated in the same areas, these could be tourist areas. This data helps us determine what type of locations users are more likely to start and end their trips in. With further research we can learn more about the characteristics of these locations: urban vs rural, high population vs low population, etc.

### BikeID Trip Counts

<img src="Images/Bike Repairs.png" width="800">

The "Bike Repairs" chart tells us which bikes (based on bike ID) have been used for the most trips. Although this chart is specific to New York users, we can replicate this chart with user Data in Des Moines to help us determine which bikes will need repairs sooner.  


## Summary

Investing in a bike-sharing program could prove to be extremely beneficial, as the total number of rides for the month of August was 2,344,224. The above visualizations offer valuable information to help investors understand how riders will use the bikesharing program. We have learned rider trends that can help investors optimize user experience such as average trip duration and peak bike-sharing hours. 
