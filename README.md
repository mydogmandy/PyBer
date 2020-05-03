# PyBer Analysis Report

## Background and Results

### This project represents an analysis of Pyber ridesharing in three popluation types to determine under-represented city types.
### Total rides were divided into city, suburban, and rural types, with average revenue per driver and ride compared, with total fare by type tracked from January 21 to April 28 in 2019:

![Summary DataFrame](https://github.com/mydogmandy/PyBer_Analysis/blob/master/analysis/summary_DataFrame.png)

### The average Rural fares returned over 3 times the average per driver for Urban areas, but the Urban total fares were 9.2 times what was earned with Rural rides.

![Total Fares by City Type](https://github.com/mydogmandy/PyBer_Analysis/blob/master/analysis/Total_Fare_by_City_Type.png)

### Although the rural rides are the most profitable per ride and per driver, the total revenues for Suburban and Urban areas consistently produced the most revenue over the months measured.


## Challenges Encountered and Overcome

### When analyzing the data, the individual ride ID's are itemized, but the driver ID's are not, with just the total drivers listed.  In order to accurately determine the driver count, I had to total the drivers by unique cities.

#Total Drivers for each city type

unique_cities = pyber_data_df.drop_duplicates(["city"])

c_tot_drivers = unique_cities.groupby(["type"]).sum()["driver_count"]

### Technical Analyses Used

## Recommendations and Next Steps

### Recommendations for Future Analysis

### Additional Analysis 1

* Description of Approach

* Technical Steps

### Additional Analysis 2

* Description of Approach

* Technical Steps
