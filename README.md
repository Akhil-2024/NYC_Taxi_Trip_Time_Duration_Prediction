# NYC_Taxi_Trip_Time_Duration_Prediction

The source dataset originates from the 2016 NYC Yellow Cab trip records, accessible via Google Cloud Platform's Big Query. Initially released by the NYC Taxi and Limousine Commission (TLC), the dataset was curated and refined for this specific usage. Tasked with utilizing distinct trip features, our objective involves forecasting trip durations.

# Source: 
NYC Taxi and Limousine Commission (TLC) : http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

Kaggle : https://www.kaggle.com/c/nyc-taxi-trip-duration/data

Download Data : https://drive.google.com/file/d/12ltOXYxom8FfXNnK2l5ma7Ro-IqFRiDn/view?usp=sharing



# Details:
File descriptions :

● train.csv - the dataset (contains 1458644 trip records)


# Data fields

id: Unique trip identifier.
vendor_id: Code depicting trip record provider.
pickup_datetime: Date and time of meter engagement.
dropoff_datetime: Date and time of meter disengagement.
passenger_count: Count of passengers (as input by driver).
pickup_longitude: Longitude at meter engagement.
pickup_latitude: Latitude at meter engagement.
dropoff_longitude: Longitude at meter disengagement.
dropoff_latitude: Latitude at meter disengagement.
store_and_fwd_flag: Flag indicating memory storage in case of no server connection (Y=store and forward, N=not).
trip_duration: Trip duration in seconds.



# Objective: 
Analyze these attributes to predict trip durations accurately.
