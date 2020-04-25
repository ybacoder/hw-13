# Tableau Homework

## Introduction

* For this assignment, [Citi Bike Data](https://www.citibikenyc.com/system-data) will be evaluated to illustrate key findings.

* The data selected for analysis was from 1Q 2020. The .csv data files (January, February, and March) were joined by union in Tableau.

## Results

* Access the [Tableau Viz here](https://public.tableau.com/profile/yacub.bholat#!/vizhome/hw-13-Citi-Bike-Analytics/Citi-Bike-Analytics)!

## Key Findings

### User Types and Activity

<div align="center">
    <img src="01_User_Type_Analysis.jpg">
</div>

* The majority of users are male.
* Subscribers use the bikes substantially more than customers.
* A large number of people canceled their subscription in March, possibly because of stay-at-home orders due to coronavirus.
* Customers use the bikes throughout the day and mostly in the afternoon.
* Subscribers use their bikes mostly in the morning (i.e., commuting to work) and evening (i.e., commuting home).

### Bikes Most Traveled and Stations Visited

<div align="center">
    <img src="02_Start_End_Station_Matrix.jpg">
</div>

* This is a screenshot of a chart and matrix that illustrates the most used bike IDs along with their start and end stations. Distance traveled was approximated using the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula) and the latitude and longitude of the start and end stations for each trip.
* Trip duration on a particular bike does not necessarily correlate with total distance traveled
* This may mean that some bikes are used on expressway-type roads while others are used in heavy stop-and-go areas.
* Specific bike IDs can be selected on the [Tableau Viz page](https://public.tableau.com/profile/yacub.bholat#!/vizhome/hw-13-Citi-Bike-Analytics/Citi-Bike-Analytics) to identify which start and end stations they have been used at.

### Start and End Stations Color-coded by Trip Distance

<div align="center">
    <img src="03_Distance_Traveled_by_Station.jpg">
</div>

* This is a screenshot of a map to present to City Officials. It geographically shows the stations and also illustrates by color which stations are associated with the longest trips (by distance). Distance traveled was approximated using the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula) and the latitude and longitude of the start and end stations for each trip.
* Specific start or end stations can be selected on the [Tableau Viz page](https://public.tableau.com/profile/yacub.bholat#!/vizhome/hw-13-Citi-Bike-Analytics/Citi-Bike-Analytics) to identify where bikers are travelling from and where are they traveling to.