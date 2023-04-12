# churn_taxi

**Tasks**

- Check if there are differences in customer churn rates in different cities (churn, city)
- Is there a difference in activity in the first 30 days from the date of registration between drivers from different cities? (city, trips_in_first_30_days)
- Can churn be related to activity in the first 30 days after registration? (churn, trips_in_first_30_days)

**Data description**

- city – city
- phone – the main device used by the driver
- signup_date – account registration date (YYYYMMDD)
- last_trip_date – date of last trip (YYYYMMDD)
- avg_dist – average distance (in miles) per trip in the first 30 days after registration
- avg_rating_by_driver – average rating of trips by the driver
- avg_rating_of_driver – average rating of driver's trips
- surge_pct – the percentage of trips made with a multiplier > 1 (it seems when there is a lot of workload, etc.)
- avg_surge – average spike multiplier over all trips by this driver
- trips_in_first_30_days – number of trips made by the driver in the first 30 days after registration
- luxury_car_user – TRUE if the user used a premium car in the first 30 days
- weekday_pct – percentage of user trips made on weekdays
