# Ford GoBike System Data
## by Aderonmu Adeniyi


## Dataset

 This dataset is for the Ford GoBike System Data for the month of Februry 2019 of over 180,000 bike rentage by people the in region of  San Francisco Bay area. The dataset can be found here [Here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv). 

Here are the list of attribute of the data

- duration_sec	
- start_time	
- end_time	
- start_station_id	
- start_station_name	
- start_station_latitude	
- start_station_longitude	
- end_station_id	
- end_station_name	
- end_station_latitude	
- end_station_longitude	
- bike_id	user_type	
- member_birth_year	
- member_gender	
- bike_share_for_all_trip


To communicate a better insight the duration was convert from min to hours, futhermore weekday and hours of the day were extracted from both start_time and end_time respectively. Lastly from the member_birth the age from the member were gotten so that analysis can be performed to see if there us any correlation between duration and age
## Summary of Findings

From the analysis the data shows that most member used bike to transit to work around 7am-8am and also to return home around 4pm-5pm. Also due to this reason there is more of bike rentage during the weekday than weekend

Secondly, age as no effect on the duration used by the member and the age group that use this bike most are around 20years-40years which also verify out first hypothesis as active workers falls around this age group

Lastly, susbribers are more than customers and customers used this bike as a form reccreatiinal activity than transit to work like suscribers



## Key Insights for Presentation

- I focus on the days  and hour of the days that have most trips
- I focus on the average time for trip  for indiduals we have based on gender and user type and also week days and hours of the day
