#  Communicate Data Findings
## by (Ajogi Paul Iye)


## Dataset

This dataset is for the month of Februrary 2019,comprises information regarding 183412 cases of rides made in a bike sharing system around the greater San Francisco Bay Area. The data housed 16 attributes(variables) inclusive of duration,start and end time for the trips. The dataset can be downloaded from here https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv


## Preliminary Wrangling

Null values for the variables - member_birth_year, member_gender, start_station_id, start_station_name, end_station_id and end_station_name were dropped since there was no means of acquiring the data. Converted data type of member_birth_year to integer;also start and end times data type was changed to datetime . Furthermore, user_type, member_gender and bike_share_for_all_trip was equally converted to categorical. New columns for day of the week and time of the day was created as it was of great importance for the project. Finally, duration_sec was converted to minutes while member_birth_year was changed to user age.


## Summary of Findings
In the process of exploration, I discovered that around 8mins is about the average duration for all trips while most rendevous takes place on Thursdays and Tuesdays.

Another intriguing thing I found is that most of the cycling activities takes place in the afternoons and evenings as greater than 90% of all rides were taken by Subscribers while the Male gender account for 70% of all cycling activities

The Male Subscribers with age range of (20 to 40)years old that do not use the bike_share_for_all_trip services generates more revenue for the company.

The "Other" gender group whom are Subscriber type that exploit the bike_share_for_all_trip services generates the least revenue.

The Customer type with least numbers spend an average of around 20 minutes cycling the bike while the Subsciber type users with the most numbers spend an average of around 10 minutes .

## Key Insights for Presentation

Categorical variables total count spreading

Categorical variables cycling duration

## Reference
Video.Udacity-data.com(2020),'Ford Gobike System Data'.[Online]Available from:https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv (Accessed: 24th September 2022)