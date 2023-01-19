# Surfs-Up Analysis

## Purpose
This code is using the SQLAlchemy library to connect to a SQLite database and retrieve temperature data for the months of June and December. It's using the extract function to filter the data by month and then converting the results to lists and creating DataFrames with the temperature data. Finally, it's calculating and printing out summary statistics for the temperature data in each DataFrame. The purpose of the assignment is to analyse temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results:

![December](Starter_Code\December_Statistics.png)
![June](Starter_Code\June_Statistics.png)

## Summary:
* The mean temperature is warmer in the summer month of June by almost 3 degrees. Surprisingly the December mean temp is still 71 degrees. This would indicate that in both December and June the temperatures are stable enough to have a successful sruf and icecream shop.
* Both the standard deviations of both months are roughly the same as well. This indicates that the data retrieved is accurate and consistant in accuracy in between June and December. This indicates that there are likely not going to be a significant impact from outlyer data in both of these months. 
* Going back to the module data anaylsis it looks like there is a spike in rainfall in each quarter in the year. The temperature data is also fairly consistant across all of the months that were queried. This points to a lot of consistancy in weather patterns for the island of Oahu.

I would also reccomend expanding the quesies to include the same summary data for all months. Rain is also not an indicator of a successful surf shop. I would reccemend taking more data points such as windspeed, perhaps expanding the range of percipitation to include a larger area. Typoically large surfing waves are caused by storm surges that blow for a sustained period over a large area. Limiting the data to Oahu would limit our understanding of how successful the surf will be. 