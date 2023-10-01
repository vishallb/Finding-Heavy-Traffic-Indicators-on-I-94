# Finding Heavy Traffic Indicators on I-94

## Introduction

Interstate 94 (I-94) is an east–west Interstate Highway connecting the Great Lakes and northern Great Plains regions of the United States.
The goal of the analysis is to determine the indicators of heavy traffic on I-94.

## Data Source

The [dataset](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume) contains information
about the westbound traffic on the [I-94 Interstate highway.](https://en.wikipedia.org/wiki/Interstate_94)

## Technologies Used

The analysis was performed using **Python** and the following libraries:

- **pandas** for data manipulation
- **numpy** for numerical computation
- **matplotlib** and **seaborn** for data visualization

## Project Goals

The main goal of this project is to determine the indicators of heavy traffic on I-94.

We segregated the data based on the day time and night time, since the night time showed less traffic volume and the goal of our project was to find the indicators of heavy traffic.
We used different time indicators like month, day of the week and time of the day to see how it corresponds with the traffic volume. 
Then, in the end, used weather indicators to check how the traffic volume varies in different weather conditions.

## Conclusion

We analyzed so many columns to find out the traffic indicators on I-94 highway.

* **Majority of the traffic volume falls in the range of 2500-5000**. There are less number of days, when the traffic volume goes over 6000.
* The **traffic volume during the day time is more when compared to night time**.
* The **traffic is usually heavier during warm months (March-October) compared to cold months (November-February)**.
* When compared to the day of the week, the **traffic volume increases during the weekdays and falls significantly as it approaches weekend**.
* When compared to the hour of the day with respect to weekdays and weekend, the traffic volume varies. 
    * **During weekdays, the traffic volume increases in the morning, and drops down as it approaches the evening**.
    * **During weekends, the traffic is constant during the noon to the evening**.
* There is **no correlation between the traffic volume and the weather columns**. Only, on the event of thunderstorm with drizzle, there seems to be a decrease in the volume of traffic.
