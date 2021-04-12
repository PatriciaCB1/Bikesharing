# Bikesharing

## Overview Of The Analysis 
A startup is starting a bike share busines in Des Moines.  In order to better understand the business model, and attract investors, the company is looking to conduct research on Citi Bike bike share in NYC.  We have used Citi Bike data that has been released to the public for our analysis. 

[link to dashboard] (https://public.tableau.com/profile/patricia.chapin#!/vizhome/NYCCitibikeAnalysis_16181776093310/CitibikeAnalysis?publish=yes)



## Resources
- Data Sources:  DT201908-citibike-tripdata.csv, 201908-citibike-tripdata.csv (https://www.citibikenyc.com/system-data)
- Software:  Anaconda 4.9.2, Jupyter Notebook 6.0.3 , Python 3.7.6, Tableau Public
- Using:  Pandas


## Results 

### For our analysis we looked at the following: 

- Checkout Times for Users
- Checkout Times by Gender
- Trips by Weekday Per Hour
- Trips by Gender by Hour / Weekday
- User Trips by Gender by Weekday only
- Gender Breakdown of all trips 
- August Peak Riding Hours by Gender
- Customer Type (Subscribers/ Non-Subscribers)

![Image 1](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.08.02%20PM.png)

![Image 2](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.08.21%20PM.png)

![Image 3](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.08.42%20PM.png)

![Image 4](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.08.59%20PM.png)

![Image 5](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.09.12%20PM.png)

![Image 6](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.09.23%20PM.png)

![Image 7](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.09.35%20PM.png)

![Image 8](https://github.com/PatriciaCB1/Bikesharing/blob/main/Images/Screen%20Shot%202021-04-11%20at%209.09.50%20PM.png)


- The majority of bikes are taken on shorter trips - with a typical duration of 5 mins (146,752)  In NYC the city is more compact likely with closer destinations.  In Des Moines we would likely see longer trip durations as locations are more spread out.
- The most common trip duration for males is 5 mins, for females 6 mins and for gender unknown 11 mins.  In order to understand this distribution better, we must better understand the gender distribution across all trips.
- Of 2,344,224 total trips in August 2018, Males took 1,530,272 trips (65%), Females 588,431 (25%) and Gender Unknown 225,521 (10%).  The majority of trips were taken by Males.
- The most popular times by volume of trips is between 5-7pm on Mondays, Tuesdays and Thursdays.  8-9am on all days is also a popular ride time.  Saturday and Sunday in general show good distribution between the hours of 10am and 8pm with Saturday being the busiest day overall across all hours.  The spikes between 8-9am and 5-7pm are likely due to people using the bikes for commuting.  We would want to confirm this through primary survey data though.
- When we revisit gender we can see that for Female and Male annual subscribers the busiest days for trips are Thursdays and Fridays.  It is clear when we filter our data that we are missing gender data (gender label Unknown) for non-subscribers.  The most popular days for non-subscribers (gender Unknown) are Saturdays and Sundays.  This is likely because they are either tourists or more casual riders who do not use the bikes for commuting.
- Subscribers took 1,900,359 trips in August 2018.  Non-subscribers accounted for 443,865 trips in August 2018.  This is an important piece of analysis as there are clearly more subscribers taking trips than casual riders.  NYC has a lot of tourism, which Des Moines does not, so the fact that the majority of trips are from subscribers tells us that the success of our venture is not at the mercy of visitors / casual riders.  


### Recommendations For Further Analysis

In order to fully assess viability of a bike share business in Des Moines, would recommend we run the following to enhance our analysis:
- Run analysis for all months to check seasonality (especially in colder months)
- Conduct quantitative survey research to better understand the gender disparity (why males over index / females underindex on bike share)
- Conduct survey research to understand trip occassion (commute, joyride, sightseeing, casual)
- Further analysis by rider age
- Quantitative survey research to understand reasons why people do not use bike share (i.e. could females be more saftey conscious in NYC)
- Research the market in Des Moines in depth to determine suitability
