# Bikesharing
Module 14: NY Citibike with Tableau

## Overview
The goal of this week's challenge is to leverage the NYC Citibike data and create charts and dashboards to support a business case for a bike sharing enterprise in Des Moines.
An investor is willing to provide funding for the project, so the student needs to analyze the data from NYC and draw insights and recommendations for the new bike sharing business in Des Moines.

## Results
Based on the analysis developed on the NYC Citibike data from August, 2019, below are the highlights:

* Assuming that the demographics from Citibike NYC will be similar to the business in Des Moines, majority of revenues will come from subscribers, not short term renters, and from males. The marketing campaign should focus first on this targeted audience.

![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics.png)

* Des Moines bike sharing business will need to establish maintenance operations during low demand period (from noon to 5:00 a.m.)

    ![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics%20(1).png)

* Bike traffic changes during weekends, peak hours start later in the day (from 10:00 a.m. to 6:00 p.m.), majority of riders are males.

    ![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics%20(2).png)

* Based on the sample, most of the rides are short and no longer than 20 minutes. Stations should be close to each other in Des Moines since majority of rides are short lenght

    ![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics%20(3).png)

* Gender does not influence the trip duration 

    ![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics%20(4).png)

* For Des Moines bike sharing business it would be important to focus on a local customer base that would be willing to commute to work with a bike (shorter distances) since majority of rides happens with subscribers during weekdays

    ![ScreenShot](https://github.com/liviamiyabara/bikesharing/blob/main/Resources/Bike%20sharing%20analytics%20(5).png)

## Summary

As highlighed above, majority of revenues from bike sharing business comes from local male subscribers that use the bikes to commute to work. The trip lenght normally is no longer than 20 minutes, so it is important to have a good network of stations that are closed to each other and located near main residential and office areas. 

The bike sharing business will require maintenance operations and according to the data, the best time to do that is in the lowest demand period, from noon to 5:00 a.m.. During weekends, the peak hours change and start later in the day (after 9:00 am), so maintenance hours for the weekends could happen after 6:00 a.m. 

Regarding additional visualizations, one suggestion will be to create a chart with all the stations and compare the number of rides and number of bikes in each one, to better understand the usage and capacity of each station: [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_Worksheet_5/D_Stationusage?publish=yes). Another idea would be to create a calculated field based on the Birth year and create tiers based on age, comparing those segments with the gender, User type and total number of trips can give additional insights on the demographics and who should be the targeted customers.   


## Deliverables

### Deliverable 1
Change Trip Duration to a Datetime Format: [File can be found here](https://github.com/liviamiyabara/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb.ipynb)

Please note that csv output file was not uploaded to git hub due to the large size of it.

### Deliverable 2
Create Visualizations for the Trip Analysis. 
Below are the links for each one of the created visualizations. Please note that Worksheets were published as Dashboards due to better chart vizualization (selection of Desktop size).

* Checkout Time for Users: [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_Checkouttimesforusers_2019_08/D_Checkouttimesforusers?publish=yes)

* Checkout Times by Gender: [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_Checkouttimesbygender_2019_08/D_Checkouttimesbygender?publish=yes)

* Trips by Weekday for Each Hour: [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_TrisbyWeekdayperHour_2019_08/D_TripsbyWeekdayperHour?publish=yes)

* Trips by Gender (Weekday per Hour): [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_TripsbyGenderWeekdayperHour_2019_08/D_TripsbyGenderWeekdayperHour?publish=yes)

* Trips by Gender by Weekday [link to dashboard](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_UserTripsbyGenderbyWeekday_2019_08/D_UserTripsbyGenderbyWeekday?publish=yes)

### Deliverable 3
Create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis.

* Tableau story with NYC Citibike analysis [link to story](https://public.tableau.com/profile/livia.miyabara#!/vizhome/Citibike_Worksheet_5/Bikesharinganalytics?publish=yes)