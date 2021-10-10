# (Dataset Exploration Title)
## by (Moheb Maher)

## N.B.

> - It is crucial to run the exploration template, the exported file will be used for the slide deck analysis.

## Dataset

> - Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area.
> - It was established as Bay Area Bike Share in August 2013.
> - As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose.
> - In June 2017 the system was officially re-launched as Ford GoBike in a partnership with Ford Motor Company.
> - The system was renamed to Bay Wheels in June 2019.
> - The system is expected to expand to 7,000 bicycles around 540 stations in San Francisco, Oakland, Berkeley, Emeryville, and San Jose.

> - The data is available for download here: https://s3.amazonaws.com/fordgobike-data/index.html
> - For the current analysis, 2018 data is downloaded.
> - The data folder contains 12 csv files, one for each month in 2018.
> - Half of the records in each file will be randomly sampled and concatenated into a single file.

> - After sampling and concatenation, the dataset has 931858 rows and 16 columns.
> - The size is enough for analysis.
> - Colum labels are satisfying (no odd characters - no extra spaces - snake cased).
> - Some columns have missing values.
> - Some columns have incorrect data types.
> - We could use some new columns (see later).


## Summary of Findings

> - since there is no user id column, we can't guarantee that these counts represent unique individuals.
> - Since subscribers usually use any service more often, I think that subscribers and cusomers must be weighted differently and it will be crucial to segment our audience later on.
> - All we can conclude that:
>> 1. The service is being used by subscribers about 8 times more often than ordinary customers.
>> 2. The service is being used by males about 3 times more often than females.
> - The age group around 30 years old is the most common pattern.
> - The presence of ages older than 60 years may suggest wrong enteries (ages greater than 100 were dropped at the early cleaning phase).
> - Most bike rides were done by age groups 30-35 > 25-30 > 35-40.
> - About 60% of bike rides were done by people aged around 25-40 years.
> - The frequency of trips along the day suggests  2 rush hours: 7 am : 9 am & 4 pm : 7 pm.
> - The rides reach their nadir between 1-4 am.
> - Another common pattern is that weekdays tend to witness more rides than weekends and winter months witness less rides.
> - About 90% of the rides took less than 20 minutes.
> - About 90% of the rides are less than 3 km long.
> - It turns out that subcribers are more like to ride for a fixed duration (they may use the service for fixed trips) than customers.
> - There is no correlation between age and trip duration.
> - The trip average duration and distribution is nearly the same among all age groups.
> - During weekdays the majority of rides are more likely to be during rush hours (riders may use the srvice for fixed trips), on the other hand the majority of rides in weekends are more likely to be during the period 7 am - 10 pm.
> - Subscribers are more likely to ride during rush hours (they may use the srvice for fixed trips as formerly mentioned), on the other hand customer are more to ride 7 am - 8 pm.
> - During rush hours, the average trip duration is nearly the same with minimal variation.
> - During the rest of the day, there is a relatively higher variation in trip duration.
> - Trip duration tend to be slightly longer and more variale in weekends (Fri evening - Sat - Sun).
> - longer and relatively more variable rides are more likely to occur during weeekends than weekdays.
> - The average duration is generally higher for the customers group.
> - The duration is highly variable outside the rush hours.
> - The variation in duration is higher for the customers group than subscribers group.


## Key Insights for Presentation
> - The service is being used by males about 3 times more often than females.
> - Most bike rides were done by age groups 30-35 > 25-30 > 35-40.
> - About 60% of bike rides were done by people aged around 25-40 years.
> - The frequency of trips along the day suggests  2 rush hours: 7 am : 9 am & 4 pm : 7 pm.
> - The rides reach their nadir between 1-4 am.
> - About 90% of the rides took less than 20 minutes.
> - About 90% of the rides are less than 3 km long.
> - longer and relatively more variable rides are more likely to occur during weeekends than weekdays.