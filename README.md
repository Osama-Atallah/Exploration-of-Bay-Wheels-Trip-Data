# Exploration of Bay Wheels Trip Data

## Dataset

For this analysis I used "Ford GoBike System Data". The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for year 2019. The data set consists of 12 files, one file for each month of the year. The data set has information of 2,506,983 rides and 334 stations. It includes: start date and time, start station, end station, ride duration, longitudes and latitudes of start and end stations.

## Summary of Findings

In the exploration, I found that there was a strong relationship between the
station hiring activity and date, time, day of week and station location. 
I sepearated stations into four categories based on their hiring activity.
Holidays and weekends has strong negative effect on station hiring activity 
especially on the busiest category of stations. 
I noticed a major decline in plot of the hiring activity time series after April 15th. This was due the withdrawal of electric bikes based on safety concerns . I also found that station hiring activity was at its peak during rush hours at mornings and evenings. The busiest stations category has more hiring activity at evening rush hours than moring rush hours. I found where the different stations category is located and disributed amonge the West Bay and the East Bay. West bay has larger number of stations than the East bay. Most of the busiest stations are in West Bay area while East Bay has mostly less busier station.  

Outside of the main variables of interest, I investigated the relationship between
station hiring activity, day of week activity and ride duratuion. I found that Ride durations have inversely proportional relation with station hiring activity. Interestingly, ride duration mean are higher in weekends by about 1 - 2 min than weekdays.


## Key Insights for Presentation

For the presentation, I investigated the influence of date, time, day of week and station location on station hiring activity. I start by introducing the station hiring activity variable and its distribution followed by the pattern in the daily and weekly time series of hiring activity, day of week hiring activity distribution, and the hourly hiring activity distribution.

Afterwards,I splitted stations into four categories based on their hiring activity quartiles. I looked at the relation between station category and day of week hiring activity using violin plots. Then I looked at time series of weekly hired bikes by station category using point plots. I used clustered bar chart to clearify the relations between hourly hiring activity and station category. Then, I looked at the pattern of stations locations based on their category. I plotted latitudes and longitudes of stations using scatter plot and used different colors for each category of stations. At the end, I used heatmap to look at the relationship between station hiring activity, day of week activity and ride duratuion.
