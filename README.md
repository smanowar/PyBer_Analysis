# PyBer Analysis

## Overview of Pyber Analysis

### Purpose

The purpose of this analysis is to analyze ride-sharing data collected for Urban, Suburban, and Rural cities for the time period spanning January 2019 to May 2019. . 

Using Pandas and the data sets city_data.csv, and ride_data.csv we will determine:

- the total rides, drivers, and fares for Urban, Suburban, and Rural cities, 
- the average fare per ride in Urban, Suburban, and Rural cities,
- the average fare per driver in Urban, Suburban, and Rural cities, and
- the total fares collected by week in the period between January 1<sup>st</sup> 2019 to April 29<sup>th</sup> 2019 in Urban, Suburban, and Rural cities.

## PyBer Analysis Results

### Result by City Type
The total amount of drivers, rides, and fares were determined based on the type of city the ride took place in. The average fare per ride by city type as well as the average fare per driver by city type was also calculated.

We can see the results displayed in the figure below:
<p align="center">
<img src=https://github.com/smanowar/PyBer_Analysis/blob/main/analysis/pyber_totals_avg_summary.PNG> 
</p>
 
Starting with the first column, we see that the vast majority of rides occourred in Urban cities, with 1625 rides happening there - followed by Suburban cities, with 625 rides taking place, and lastly by Rural with 125 rides taking place. 

The total drivers also differ significantly based on city type: Urban cities having 2405 drivers, Suburban cities with about one fifth the amount with 490 drivers, and 78 drivers in Rural cities. 

The large difference in these numbers are reflected in the Average Fare per Ride and Average Fare per Driver:

- Rural cities had the highest averages in both categories, averaging fares of $34.62 per ride, and $55.49 per driver - with total fares being $4327.93.
- Suburban cities, had a total fare of $19,356.33, averaging $30.97 per ride and $39.50 per driver.
- Lastly is Urban cities, with fares totaling $39,854.38 - an average of $24.53 per ride and $16.57 per driver.
 
### Results by Week: Trend
In the time period between January 1 2019 to April 29th 2019, we can see the trends in the fares between Urban, Suburban, and Rural cities depicted below:
  
<p align="center">
<img src=https://github.com/smanowar/PyBer_Analysis/blob/main/analysis/pyber_fare_summary.png> 
</p>

There is a slight fluctuation in the Total Fare for the time period being analyzed:

 - Rural cities fluctuate between $501.24 and $67.65, peaking in the week of April 7th and a low the week of January 13th.    
 - Suburban cities flucutuate between $1412.74 and $721.60 peaking the week of February 24th and a low the week of January 6th.
 - and lastly, Urban cities fluctuate between $2466.29 and $1661.68 peaking the week of February 24th and a low the week of Janurary 6th. 

## PyBer Analysis Summary

From the results summarized above we can see that there are very large differences in fares, ridership, and drivers between the three city types. Urban cities have the vast majority of ridership, the largest amount of fares, and the most drivers between the three. Based on these results the following reccomendations can be made:

- A focus should be placed increasing ridership in Rural areas as determined from our analysis of total fares by week. The total fare was at its lowest the week of January 13th, with fares totaling $67.65 - based on our average fare per ride this means that about 2 rides took place that week. 

- A similar argument could be made for Suburban cities. Even though their numbers are higher than Rural cities, they are still much lower than the results from Urban cities. As there is huge potential for growth a focus could be placed in Suburban cities to maximize the ridership in these areas. 

- Although the average fare per driver is less than half the average fare per drivers in Suburban cities and three times less the average fare per driver in Rural areas, the total amount of rides in Urban cities are much higher. Therefore, although the average fare per ride is lower, the drivers are completing more rides - as reflected in the high amount of total fares. A focus should be placed on protecting the average fare per driver in Urban areas; if the average fare drops too low it can discourage drivers from working in Urban cities. 
