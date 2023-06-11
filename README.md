# London-Bike-share-Analysis

Santander Cycles, also known as the London bike share scheme, is a popular public bicycle sharing system established by Santander Cycles in London. It offers a convenient self-service model where individuals can access bicycles from docking stations without requiring external assistance.

This system allows people in need of bicycles to easily locate and obtain one from any available docking station throughout the city. Users have the flexibility to rent a bike by making a payment through various methods such as credit cards or mobile apps. Once the payment is made, they can unlock a bicycle and begin their ride.

One of the key features of Santander Cycles is its emphasis on self-service and independence. Users can collect a bike from one docking station and return it to any other station near their destination, providing a flexible and efficient way to travel. This makes it a popular choice for short trips, commuting, or exploring the city at one's own pace.

The scheme contributes to reducing traffic congestion, promoting environmentally friendly transportation, and encouraging an active and healthy lifestyle. With Santander Cycles, individuals have easy access to bicycles whenever they need them, without relying on external assistance or adhering to fixed schedules.

In summary, Santander Cycles has become an integral part of London's transportation landscape, offering a user-friendly and sustainable means of commuting and sightseeing throughout the city.


## Problem Statement
To analyze the effectiveness of the Bike sharing system, the stakeholders are looking to answer questions such as
- What is the total bike share for the period?
- How does weather affect bike usage?
- Which season have the highest bike shares?
- How does bike share vary by time of day?
- How do factors such as humidity, temperature and wind speed affect the bike share count?
- Are more bikes ridden during the holiday or non-holidays?
- Are more bikes ridden during the weekday or weekend?


## Data Sources
the dataset was from Kaggle  
https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset


## Data Processing
- Checked for duplicates
- Checked for missing values
- Use the trim function to delete extra spaces
- Separated the timestamp column into date and time columns
- Created conditional columns on the weather, is_holiday, season and is_weekend columns using information from the Metadata 
- Renamed all columns appropriately
- Changed all data types to the prefared type for easy analysis


## Analysis
### What is the total bike share for the period?
A total of 19,905,972 ride shares for the dataset period of Jan 4th 2015 - Jan 3rd 2017

### How does weather affect bike usage?
Plotting the total bike shares against weather type on a column chart
The most bikes are shared when the weather is clear  followed by scattered and broken clouds 
less bikes are shared during unfavourable weather conditions rain, thunderstorms or snowstorms.


### Which season have the highest bike shares?
Looking at the values on a donut chart
summer season has the highest bike shares follwed closely in the fall the spring season and winter having the list bike shares


### How does bike share vary by time of day?
Bike shares are more around 8.00 AM and 5.00 PM which are work rush hour times.
People tend to share more bikes going to work and during close of work.


### How do factors such as humidity, temperature and wind speed affect the bike share count?
Humidity and temperature are inversely proportional. Therefore, when temperature reduces, humidity increases and thus the air becomes drier. 
Less rides are taken during this period. Conversely, as the temperature increases the count of bike shares also increases.
Less bike shares occur when there is an incrase in wind speed.


### Are more bikes ridden during the holiday or non-holidays?
Non-holidays accounted for 98.52% of total bike share for the given period with a total of 9,610,474 rides. The count of Holiday rides was 295,498 which accounted for 1.48%. This is because holidays are usually periods of rest and most persons would have need to commute to work.


### Are more bikes shared during the weekday or weekend?
Rides on weekends account  for a quarter (4,857,756 rides) of the total rideshare.
these shows that bikes are shared mostly for work activities.


## Recommendation 
- Given periods of peaks and decline, the bike can be docked and undocked for major refurbishments and care during winter months.
- Rountine maintenance can be carried out during weekends or holiday periods.
- More bikes can be made available for summer months which has the highest peak of ride shares.
- The rush hour bike share traffic can be well managed by knowing the peak times during the day.
- Better financial planning can be done around off seasons and period of bad weather conditions where low bike shares are recorded.








