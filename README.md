# PyBer Analysis Report

## Background and Results

### This project represents an analysis of Pyber ridesharing in three popluation types to determine under-represented city types.
### Total rides were divided into city, suburban, and rural types, with average revenue per driver and ride compared.  The total fare by type tracked from January 21 to April 28 in 2019:

![Summary DataFrame](https://github.com/mydogmandy/PyBer_Analysis/blob/master/analysis/summary_DataFrame.png)

### The average Rural fares returned over 3 times the average per driver for Urban areas, but the Urban total fares were 9.2 times what was earned with Rural rides.

![Total Fares by City Type](https://github.com/mydogmandy/PyBer_Analysis/blob/master/analysis/Total_Fare_by_City_Type.png)

### Although the rural rides are the most profitable per ride and per driver, the total revenues for Suburban and Urban areas consistently produced the most revenue over the months measured.


## Challenges Encountered and Overcome

### When analyzing the data, the individual ride ID's are itemized, but the driver ID's are not, with just the total drivers listed.  If driver ID's were listed, it would have been easier to determine how many drivers gave rides in each city type without the need for further manipulation.  In order to accurately determine the driver count, I had to total the drivers by unique cities.

[Data Analysis Code Link](https://github.com/mydogmandy/PyBer_Analysis/blob/master/PyBer_Challenge.ipynb)

## Recommendations and Next Steps

### Based on the data from the different city types, PyBer should invest in attracting more drivers for Suburban routes, as that sector has seen recent growth in total fares, where the Urban and Rural routes have seen recent declines in revenue generated.
### While rural drivers produced a small increase in average fares per ride, it may be easier to increase the drivers in the Rural market, as the average fare per driver is much greater that in Suburban or Urban areas.  
### A recommendation would be to continue tracking for a complete year to see if the city types react differently during certain times of the year.

## Further Recommended Analysis:

- If ride length and distance are added to the data along with driver ID's, we can determine how much time the average ride takes and the average distance traveled.
- Since there is a timestamp included with the dates, it would be valuable to run another analysis for each city type to gain insight when more or less drivers need to be available.

### If a dataset containing driver ID's associated with Ride ID's exists, it can be merged into the new dataset created to include the ID visibility.