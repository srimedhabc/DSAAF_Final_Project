Introduction:
Urban traffic has always been a hindrance for people who commute on a regular basis for their daily activities, including work, school, etc. After Covid, the use of personal vehicles increased in an unprecedented way. The economic crisis led to the rise in cost of public and private transport. There is a need for a cheaper and quicker transportation options which can be used for daily commute purposes. This is where the NYC Citi Bike stands in the industry; filling the gaps caused by the urban transport and associated traffic.

CitiBike is an e-bike service located around the NYC & New Jersey border, which provides a cheaper and environmental friendly transport option for daily commuters as well as tourists. The system consists of bicycles supported by batteries and a DC motor to improve mobility and reduce the effort by the rider.

Goal:
Based on the data collected by CitiBike during the year 2022, we want to strategically optimize the e-bike fleet deployment and station management to maximize ridership and revenue. The analysis will take into account the interplay between rider preferences and station utilization patterns across different member types, ensuring an equitable distribution of e-bikes throughout the service area.

About the Data:
CityBike trip history data is publicly available through the link, https://citibikenyc.com/system-data. We have selected 2022 year's data for the analysis. The dataset contains the following attributes,

ride_id: It is unique identifier to distinguish trips.
rideable_type: It indicates the type of bycycle used. There are 3 types of bikes electric_bike, classic_bike, docked_bike.
started_at: It indicates the trip start datetime.
ended_at: It indicates the trip end datetime.
start_station_name: It indicates the name of the station from where the ride started.
start_station_id: A unique identifier to indicate the start station.
end_station_name: It indicates the name of the station where the ride ended.
end_station_id: A unique identifier to indicate the end station.
member_casual: It indicates whether the rider is a casual user or has a membership with Citi Bike.
