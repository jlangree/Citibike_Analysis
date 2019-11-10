# Citibike Data Analysis

## The Data:
Trip data from October 2018 through September 2019 was used. Because of the massive amount of data, only 10% of trips were analyzed, selected by taking every 10th trip record.

## Essential Questions:

* Where are the highest-activity stations located?
* How is customer age related to Citibike usage?
* What is the distribution of individual bike use and where are the most-used bikes ridden?

---

### Bike Station Activity

All of the most used stations are located, unsurprisingly, in Manhattan. This is true across all months in the dataset. More specifically, the most active 20 stations are in Midtown and Lower Manhattan. All stations see significant fluctuations in usage throughout the year, dropping in older months and increasing in warmer ones.


### Customer Age

Not all trip data was used in the analysis on customer age. User age was determined based on user-input birth year. Unfortunately, there is no easy way to verify the accuracy of the data, and it is clear that some of this user-input data is not accurate. For instance, there were trips carried out by customers who claimed to have been born in the late 1800's. Additionally, the most prevalent birth year by far was 1969. Analysis of customer age would predict drastically lower usage by 50-year-olds. Thus, age analysis was only conducted on customer between the ages of 16 (youngest allowed) and 90. Of this data, the bulk of the trips were taken by users aged 24 - 40.

The clearest trend associated with age involved the proportion of trips by service subscribers. Older customers tended to be subscribers, while the youngest customers tended the other way. There is a steep increase in proportionaate subscribership from age 16 through 30, as it increases from roughly 45% to near 90%. Above 30, subscribership continues to increase, albeit at a much slower rate.

Younger users also tended to use bikes for longer durations. Those under 18 had a noticeably higher median trip duration (14-18 mins) compared with adult users (10-12 minutes). Trips by customers whose reported age was over 80 were highly variable in median length, leading to an assumption of inaccurate birth year data.


### Individual Bike Usage

Analyzing bike use is relevant to discovering which bikes might be in need of maintenance. There was a large variance in usage by individual bikes. The distribution was also bimodal, with peaks at around 12 uses and around 100 uses over the entire year. Many bikes were barely used at all, and close to 50 bikes were used over 300 times throughout the year. Bikes that saw little usage had much more variable trip durations compared with those used the most.

The 5 most frequently used bikes in the dataset tended to be ridden in Lower and Midtown Manhattan, occasionally making their way into Brooklyn. This was determined by examining how the mean daily geographic coordinates of each bike changed throughout the year. This phenomenon was visualized on a dynamic map, with trails tracking the daily mean locations of the top 5 used bikes.

---

## Conclusions

* Citibikes are most commonly used for trips originating in Midtown and Lower Manhattan for short trips, between 5 and 15 minutes.
* Younger users tended to be single-use customers whose trips were relatively long compared to older users.
* Bike use is drastically higher in warmer months compared to cooler months