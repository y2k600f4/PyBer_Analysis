# PyBer_Analysis



##Overview of the analysis:

The purpose of this analysis is to utilize python and pandas to create a summary dataframe of the provided ride-sharing data (city data and ride data files) by city type. Pandas and matplotlib will then be used on the data from the summary dataframe that was created from these data sets to create a multiple-line graph that shows the total weekly fares for each city type. This graph will then be used to present an analysis based on city type.


##Results:

A summary dataframe was created summarizing city type (rural, suburban and urban) and showing the key data of interest for each city type (Total Rides, Total Drivers, Total Fares, Average Fare per Ride and Average Fare per Driver). This summary table can be referenced below:

![City Type Summary](https://github.com/y2k600f4/Pyber_analysis/blob/main/analysis/summary.png)

###Key analysis points of interest include the following:
1.	Urban city type is by far has the greatest number of total rides, total drivers and total fares. In addition, the average Fare per Driver is significantly lower than the other city types.
2.	Rural city type generates a higher average fare per ride and significantly higher average fare per driver than the other city types. 
3.	Suburban city type falls in the middle of all the city types (total rides, total drivers, total fares, average fare per ride and average fare per driver).

By plotting the total fare by date for each of the city types further analysis of this data set can be performed. Referencing the graph below with the dates of interest it can be seen that the trend of the city types follow the analysis from the summary with total urban fares being highest, suburban in the middle and rural being the lowest. Looking at the trend of total fares across specific dates there is a peak in late February across all three city types with the maximum being for both the urban and suburban city types with the rural being close to the maximum which actually is in April.

![City Type graph](https://github.com/y2k600f4/Pyber_analysis/blob/main/analysis/PyBer_fare_summary.png)

###Summary:
Based on the results the following business recommendations are recommended to the CEO to address disparities among the city types.
1.	Drivers in the rural area generally make more money per fare per ride. The data shows ~40% increase average fare per ride over urban drivers. This is most likely due to the longer distances per fare in the rural cities. There are much fewer total rides in the rural cities, ~8% of that of the urban total rides. This is reflected in the total # of drivers in the rural areas being much lower. The rural areas only showed a 125 total rides in the five months of interest in 2019. It is recommended that the rural cities not be targeted for any potential growth.
2.	The urban cities are not the ideal target market for growth.  The average fare per driver is the lowest which is likely due to the short distances. In addition, the ratio of total drivers to total rides is the highest with the total drivers being larger than the total rides. The urban cities should not be targeted for any potential growth.
3.	The suburban cities should be the target area for growth. The average fare per driver being less than the rural fares but much more than the urban fares. The total rides are less in the suburban area but not as low as the rural. The medium distance for fares along with the fact that the ratio of total drivers to total rides is much lower than the urban cities showing the highest potential for growth.
