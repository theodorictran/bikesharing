# bikesharing
## Overview
In this analysis, I took public New York City bike rental data for the entire month of August 2019. With the dataset, I created several Tableau visualizations which were all used together to create data story to convince potential investors to fund a new bike rental project centered in Des Moines. Python and pandas were used to convert the datatype of the "tripduration" column from integer to datetime for proper usage in Tableau.

## Results
<img width="923" alt="Citi-1" src="https://user-images.githubusercontent.com/91519293/152719560-ebf6d7f7-8aaf-4f77-8faf-fbbefeb96858.png">

The dashboard above has three visualizations to indicate the total number of trips recorded in August 2019 broken down by Gender and User Type, separately. Majority of the customers are bike subscribers and majority of riders are males.

<img width="958" alt="Screen Shot 2022-02-06 at 9 36 40 PM" src="https://user-images.githubusercontent.com/91519293/152720580-fa5c3967-e41c-4979-8788-2d1406003dcd.png">

The visualization above graphs the length of time that bikes are checked out for all riders filtered by three different trip durations: 59 minutes or less, 1 hour to 1 hour and 59 minutes, and 2 hours to 2 hours and 59 minutes. From this graph, it is clear that a large proportion of trips do not exceed an hour with peak majority of trips lasting 5 minutes total. 

<img width="958" alt="Citi-3" src="https://user-images.githubusercontent.com/91519293/152719599-04e3d023-130e-49a4-bde3-07c5faef9ac7.png">

This visualization is similar to the previous visualization, for instead of all riders the trips are broken down by gender.

<img width="515" alt="Citi-4" src="https://user-images.githubusercontent.com/91519293/152719608-35758dc1-f99b-43b7-baf7-768454732a71.png">

Above is a heatmap that plots the trips made by the hour. The most popular time to checkout a bike is between 5 PM and 6 PM as well as 8 AM. Thursday is the day of the week that exhibits the most bike activity.

<img width="996" alt="Citi-5" src="https://user-images.githubusercontent.com/91519293/152719615-089f2ed1-85ac-4b08-9147-c80c65c6914c.png">

The heatmaps above show tripss made by the hour filtered by different genders. 

<img width="995" alt="Citi-6" src="https://user-images.githubusercontent.com/91519293/152719628-f6c49167-30a8-4a81-a68f-3e0a5104eed3.png">

The visualization above is a heatmap that shows the number of bike trips broken down by gender for each day of the week by each user type. Clearly, Subscribers are majority of the users and are mostly male at that. The proportion of customers or non-subscribers are mostly male. 

## Summary
Based on the data story, the bike-sharing product in New York City is very popular. Majority of the customer base is made up of subscribers and males. During the week, a surge of bike activity is made in the morning at 8 AM and in the afternoon between 5 PM and 6 PM. In addition, Thursday seems to be the day of the week that presents the most activity. For future analysis, I would like to see a visualization detailing bike routes using a map and another visualization that takes a deeper dive into the most popular bike checkout times during the week and breaking it down further based on starting station or ending station.

[Link to Dashboard](https://public.tableau.com/app/profile/theodoric.tran2099/viz/Bikesharing_16429844961780/BikeCitiStory)
