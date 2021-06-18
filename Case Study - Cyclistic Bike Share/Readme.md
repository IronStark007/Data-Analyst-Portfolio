# Case Study - Cyclist Bike-Share

## Introduction

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

Marketing team has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Team are interested in analyzing the Cyclistic historical bike trip data to identify trends.

## Problem
Our part of the problem is to answer: __How do annual members and casual riders use Cyclistic bikes dierently?__

__Business task:__ Find out the behaviour of Casual and Member bike usage to increase the subcription rates in the city

## Datasets
I will use [Cyclistic’s historical trip data](https://divvy-tripdata.s3.amazonaws.com/index.html) to analyze and identify trends. 

_Note: The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study, the datasets are appropriate and will enable you to answer the business questions. The data has been made available by Motivate International Inc. under [this license](https://www.divvybikes.com/data-license-agreement)._

This is public data that I am using to explore how different customer types are using Cyclistic bikes. But note that data-privacy issues prohibit you from using riders’ personally identifiable information. This means that you won’t be able to connect pass purchases to credit card numbers to determine if casual riders live in the Cyclistic service area or if they have purchased multiple single passes.

## Cleaning Process

Since the program has launched from 2016 so to better analyze the trend I am using data from 2016 to 2021 in the preparing phase. The data set is very huge so I have used R for the cleaning and transformation.

You can check all years cleaning process below (pdf format)- 
- [Cleaning of 2016-2017](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Case%20Study%20-%20Cyclistic%20Bike%20Share/Data%20Cleaning/Bike_sharing_clean-2016-17.pdf)
- [Cleaning of 2017-2018](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Case%20Study%20-%20Cyclistic%20Bike%20Share/Data%20Cleaning/Bike_sharing_clean-2017-18-.pdf)
- [Cleaning of 2018-2019](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Case%20Study%20-%20Cyclistic%20Bike%20Share/Data%20Cleaning/Bike_sharing_clean-2018-19-.pdf)
- [Cleaning of 2019-2020](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Case%20Study%20-%20Cyclistic%20Bike%20Share/Data%20Cleaning/Bike_sharing_clean-2019-2020.pdf)
- [Cleaning of 2020-2021](https://github.com/IronStark007/Data-Analyst-Portfolio/blob/master/Case%20Study%20-%20Cyclistic%20Bike%20Share/Data%20Cleaning/Bike_sharing_clean-2020-2021-.pdf)

Or if you want to check Web format of this files - 
- [Cleaning of 2016-2017](https://rpubs.com/IronStark007/782214)
- [Cleaning of 2017-2018](https://rpubs.com/IronStark007/782251)
- [Cleaning of 2018-2019](https://rpubs.com/IronStark007/782256)
- [Cleaning of 2019-2020](https://rpubs.com/IronStark007/782261)
- [Cleaning of 2020-2021](https://rpubs.com/IronStark007/782955)

During process phase I have make new columns namely - 
* __ride_length:__ difference between start time and end time 
* __round_trip:__ if the start station and end station are same or not 
* __year:__ by extracting year from the start date
* __month:__ by extracting month from the start date
* __day_of_week:__ by extracting weekdays from the start date

And aggregate them by median (not mean, since the data contains many outliers).

## Conclusion

After transforming the data, I have analysed and suggested top three recommendations:

Marketing team should/can - 
* introduce __monthly or quarterly passes__ so the people will find it more  affordable so they will attract towards our annual program
* come up with a plan or __program for mid year or tourists passes__ where bike usage increases due to tourists activities
* give __discounts or coupons for weekends__ so people will buy the passes more on weekends thereby relying more on our bikes

You can check my Tableau Dashboard - [Here](https://public.tableau.com/app/profile/ansari.mohammed.ali.nasim/viz/CaseStudy-DivvyBike/Dashboard1)


You can check my Presentation - [Here](https://docs.google.com/presentation/d/1lFHJKADEmFr5k7nHMkYPuCs6T6EQmXsY1LFQYwqIldM/edit?usp=sharing)

## Next Steps

Marketing teams should make a survey focussing on the motivation of using bike for daily work or any other usages so as to better understand the feeling of the customers

They should also consider the migrant population and how they build trust with them. 



