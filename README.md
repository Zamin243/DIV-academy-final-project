🚍 **Welcome to the Public Transport Delay Analysis** 🚆

🌟 **Introduction** 🌟
This project explores the fascinating world of delays in public transportation, based on a rich dataset that reflects the dynamics of urban transit systems. Our goal is to uncover patterns and key factors behind delays, while helping transportation authorities optimize schedules and improve passenger experience.

🎯 **Problem Statement** 🎯
Delays in public transportation negatively impact daily commuting, reduce economic productivity, and cause passenger dissatisfaction. In this project, we aim to identify the main causes of delays by analyzing factors such as weather conditions, traffic congestion, and special events, and to propose data-driven solutions using Machine Learning (ML) techniques.

📊 **About the Dataset** 📊
The dataset named *‘public_transport_delays.csv’* contains detailed information about public transport trips and includes the following key features:

* **trip_id**: Unique identifier for each trip
* **date**: Date of the trip (e.g., 2023-01-01)
* **time**: Scheduled start time
* **transport_type**: Type of transport (Bus, Tram, Metro, Train)
* **route_id**: Route identifier
* **origin_station & destination_station**: Starting and ending stops
* **scheduled_departure & scheduled_arrival**: Planned departure and arrival times
* **actual_departure_delay_min & actual_arrival_delay_min**: Actual delay (in minutes)
* **weather_condition**: Weather condition (e.g., Clear, Rainy, Snowy)
* **temperature_C, humidity_percent, wind_speed_kmh, precipitation_mm**: Environmental metrics
* **event_type**: Special events (e.g., Concert, Protest, None)
* **event_attendance_est**: Estimated attendance
* **traffic_congestion_index**: Traffic congestion level
* **holiday**: Whether it is a holiday (1 or 0)
* **peak_hour**: Whether it is peak hour (1 or 0)
* **weekday**: Day of the week (0–6, where 0 is Monday)
* **season**: Season (Spring, Summer, Autumn, Winter)
* **delayed**: Whether a delay occurred (1 or 0)

🔍 **Objective** 🔍
Using this dataset, we will analyze delay patterns across different transport types, weather conditions, and external factors (such as events and peak hours). Additionally, we will build Machine Learning models to predict the likelihood of delays. The insights obtained will help transportation planners reduce delays, improve service reliability, and make more effective decisions.

🚀 **Let’s begin this journey to make public transportation more efficient!** 🚀
