# (Dataset Exploration Title)
## by Istam Kulliev


## Introduction
Ford GoBike is a regional public bicycle sharing system in USA.

Ford GoBike, like other bike share systems, consists of a fleet of specially designed, sturdy and durable bikes that are locked into a network of docking stations throughout the city.

The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips. The bikes are available for use 24 hours/day, 7 days/week, 365 days/year and riders have access to all bikes in the network when they become a member or purchase a pass.

## Dataset

In this investigation, I want to look at to the customer behaviour characteristics. 

I focused on time, age, gender, duration and user type to analyze and understand the usage of bike.

Dataset Overview
The forgobike trip data are more 1,83 thousands rides and 16 variables that happend 2019 in february.

The database is clean. Their number decreased from about 183,000 to 175,000.

Quality issues

Start time and end time are objects not a timestamps

user type, gender and bike_share_for_all_trip can be set to category

bike id, start_station_id, end_station_id can be set to object
## Summary of Findings

The initial combined data included approximately 174,295 individual travel records with 16 columns. Variables can be divided into three major categories:

1 Travel duration: a) continuity_sec., b) start time; c) expiration time.

2. Station information:
-start_station_id, -start_station_name, -start_station_latitude, -start_station_longitude, -end_station_id, -end_station_name, -end_station_latitude, -end_station_longitude.

3. Information about members:
-velosiped_id, -user_type, -a'zo_birth_year, -member_gender, -bike_share_for_all_trip

Features / variables that help research and analysis:

Travel information: duration_minute, start_date, start_hourofday, start_dayof week, start_month
member: member_age
The following analysis was performed in the database analysis. Type of users reviewed.

Based on the Member_gender analysis, key customers and members were surveyed. As a result, it was determined that the main customers were men.

It was also analyzed on the basis of duration_sec which categories of customers have cycled for a long time. In addition, an analysis of the age of the clients was performed.


## Key Insights for Presentation

Based on the analysis, the correlation coefficients indicate that there may be a correlation between the following pairs: (start_station_id, end_station_id), (start_station_latitude, start_station_longitude) and (end_station_latitude, end_station_longitude). However, there is no evidence in the database to support this.
