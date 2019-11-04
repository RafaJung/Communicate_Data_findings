
# Project 5 - Communicate Data Findings - Ford Go Bike

## by Rafael Vieira Jung

## The Dataset selected

The dataset i will use on this project is the "Ford GoBike System Data". this dataset includes information about individual rides made in a bike-sharing system covering San Francisco Bay Area. The information about this dataset you can find here: https://www.lyft.com/bikes/bay-wheels/system-data

This Dataset has 4256681 bike trips and 18 coluns of information about that trips.

## Data Cleaning
For make data with less quality issues, i did some waringlings acts to cleaning.

1- Remove columns that had some null and missing values. the columns are: Bike_id Unnamed: 16 bike_share_for_all_trip start_station_id end_station_id

2- Trade the datatype of start and end of travels, beacause they were objects.

3- Create new columns to analyze the consumer behavior of month, weekday and hour.

## Summary  Findings
**Start Hour**

the use of bike trips has its peaks at 8:00 and 17:00. This is probably due to go to work and go back home later. About the duration, it doesn't seens a great correlation, or even a correlation with start hour frequency, since the peak of longer trips are 2 and 3 p.m

**Month**

About the use of bike trip and its duration, i've found a clear results August and September have the most of trips and time of use. This seazonality happens because of the season. It isn't too hot or too cold. And PROBABLY, this two months doesn't rain great ammounts.

**Weekday**

About Weekday, i've found two user behaviors: The first one, is about the number of bike trips: Weekend has the lowest number of trips by far. The second one is in part opossite that, even the weekend has fews bike trips, the rydes are longer than on weekdays, and this trips occurs on a different time, on weekend they happens on evening.

**Gender**

Womens use longer than men. Independent the feature i've ploted, the womens are almost 100 seconds than man. About the hours, weekdays and months, the use by gender it isn't different- women stil 100(on mean) more than men. 

## Key Insights for presentation

For the presentation, i focused only on the independent variable, the duration time, since i've explore the use of bike trips before, i want to focus anad help to answer the questions of which feature influences more on duration of a trip. the Key insights of project are:

**MONTH**

The higher values of mean duration trips occurs on august and september. 

**Start Hour**

The mean duration is higher on 13 p.m to 15 p.m on evening

**Weekdays**
The Mean duration Trip is higher on weekend, and it's higher on evening.

**Gender**
The mean duration is different based on gender. Womans use more than mans. It's close to 100 seconds higher than men. 
