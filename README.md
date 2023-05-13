# London-Bike-share-Analysis

Santander Cycles, also known as the London bike share scheme, is a popular public bicycle sharing system established by Santander Cycles in London. It offers a convenient self-service model where individuals can access bicycles from docking stations without requiring external assistance.

This system allows people in need of bicycles to easily locate and obtain one from any available docking station throughout the city. Users have the flexibility to rent a bike by making a payment through various methods such as credit cards or mobile apps. Once the payment is made, they can unlock a bicycle and begin their ride.

One of the key features of Santander Cycles is its emphasis on self-service and independence. Users can collect a bike from one docking station and return it to any other station near their destination, providing a flexible and efficient way to travel. This makes it a popular choice for short trips, commuting, or exploring the city at one's own pace.

The scheme contributes to reducing traffic congestion, promoting environmentally friendly transportation, and encouraging an active and healthy lifestyle. With Santander Cycles, individuals have easy access to bicycles whenever they need them, without relying on external assistance or adhering to fixed schedules.

In summary, Santander Cycles has become an integral part of London's transportation landscape, offering a user-friendly and sustainable means of commuting and sightseeing throughout the city.


## Problem Statement
To analyze the effectiveness of the Bike sharing system, the stakeholders are looking to answer questions such as
- How does weather affect bike usage?
- what season have the highest bike shares?
- What time of the day affects bike share?
- How do factors such as humidity, temperature and wind speed affect the bike share count?
- Are more bikes ridden during the holiday or non-holidays?
- Are more bikes ridden during the weekday or weekend?


## Data Sources
the dataset was from Kaggle
https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset


## Data Processing
- checked for duplicates
- checked for missing values
- Use the trim function to delete extra spaces
- Separated the timestamp column into date and time columns
- created conditional columns on the weather, is_holiday, season and is_weekend columns using information from the Metadata 
- Renamed all columns appropriately
- changed all data types to the prefared type for easy analysis


## Analysis
### How does weather affect bike usage?
plotting the total bike shares against weather type on a column chart
The most bikes are shared when the weather is clear  followed by scattered and broken clouds 
less bikes are shared during unfavourable weather conditions rain, thunderstorms or snowstorms

![image](https://github.com/DapoAdeola/London-Bike-share-Analysis/assets/130672823/c0f5da5e-7b33-4ed0-93f3-714c16fc0ac0)

