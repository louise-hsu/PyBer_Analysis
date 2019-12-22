# PyBer_Analysis

## Project Overview
Perform data analysis as a PyBer Data Analyst. We are trying to help PyBer improve access to ride-sharing services, and determine affordability in under-served neighborhoods. 

1. Convert CSV Files to Pandas DataFrames
2. Create a Bubble Chart for Ride-Sharing Data
3. Calculate Summary Statistics
4. Pie Chart: Percentage of Total Fares by City Type
5. Pie Chart: Percentage of Total Rides by City Type
6. Pie Chart: Percentage of Total Drivers by City Type
7. Line Chart: Tital Fare by City Type 

This Module taught me the following through Jupyter Notebook,Pandasm and MatPlotLib:
1. Inspect data
2. Merge data sets
3. Perform calculations
4. Create data series and data frames
5. Produce publication-quality figures using MatPlotLib 
6. Tell a visual story from the data using MatPlotLib

## Resource Folder
- city_data: Used for the Module 5 Skill Drills & Challenge. The Data shows each city, driver_count, and city type.
- PyBer_ride_data: This data was used to test and learn how to plot data.
- ride_data: Used for the Module 5 Skill Drills & Challenge. The Data shows each ride information - city, date, fare, ride_id

## analysis folder
- Fig1: PyBer Ride Sharing Data (2019)
- Fig2: Ride Count Data (2019)
- Fig3: Ride Share Data (2019)
- Fig4: Driver Count Data (2019)
- Fig5: % of Total Fares by City Type
- Fig6: % of Total Rides by City Type
- Fig7: % of Total Drivers by City Type
- Fig8: Total Fare by City Type (CHallenge)

## PyBer Analysis
- Resource Folder - Look above for info
- analysis Folder - Look above for info
- Chart_Extras: Extra file for learning how to plat
- matplotlib_practice: Learning the syntax of the MatPlotLib
- PyBer : Module 5 and skill drills
- PyBer_ride _data: Leaning how to read data from a file and plot it
- PyBer_Challenge: Module 5 Skill Drills, and the Challenge 5

# Summary
***Please note: The summary is found in the in the analysis Folder, and the code found in the PyBer.ipny *** 

The analysis of the PyBer Data show that:
- There are 3 different City Type: Urban, Suburban, and Rural
- PyBer Sharring Data:
    - Urban City Types have the highest total number of rides per city and driver count, however the lowest average Fare($) per ride.
    - Rural City Types have the lowest total number of rides per city and driver count, however the highest average Fare($) per ride.
    - Suburban City Types are in between Urban and Rural in total number of rides per city, driver count, and average Fare($)
- Urban Ride Count Data:
    - The mean for the ride counts for urban trips is 24.62.
    - The median for the ride counts for urban trips is 24.0.
    - The mode for the ride counts for urban trips is ModeResult(mode=array([22], dtype=int64), count=array([7])).
- Suburban Ride Count Data:
    - The mean for the ride counts for suburban trips is 17.36.
    - The median for the ride counts for suburban trips is 17.0.
    - The mode for the ride counts for suburban trips is ModeResult(mode=array([17], dtype=int64), count=array([7])).
- Rural Ride Count Data:
    - The mean for the ride counts for rural trips is 6.94.
    - The median for the ride counts for rural trips is 6.0.
    - The mode for the ride counts for rural trips is ModeResult(mode=array([6], dtype=int64), count=array([5])). 
- Urban Fare Price Data:
    - The mean fare price for urban trips is $24.53.
    - The median fare price for urban trips is $24.64.
    - The mode fare price for urban trips is ModeResult(mode=array([22.86]), count=array([5])).
- Suburben Fare Price Data:
    - The mean fare price for suburban trips is $30.97.
    - The median fare price for suburban trips is $30.75.
    - The mode fare price for suburban trips is ModeResult(mode=array([17.99]), count=array([3])).
- Rural Fare Price Data:
    - The mean fare price for rural trips is $34.62.
    - The median fare price for rural trips is $37.05.
    - The mode fare price for rural trips is ModeResult(mode=array([37.05]), count=array([2])).
- Urban Driver Count Data:
    - The mean driver count for urban trips is 36.68.
    - The median driver count for urban trips is 37.0.
    - The mode driver count for urban trips is ModeResult(mode=array([39], dtype=int64), count=array([86])).
- Suburban Driver Count Data:
    - The mean driver count for suburban trips is 13.71.
    - The median driver count for suburban trips is 16.0.
    - The mode driver count for suburban trips is ModeResult(mode=array([20], dtype=int64), count=array([79])).
- Rural Driver Count Data:
    - The mean driver count for rural trips is 4.30.
    - The median driver count for rural trips is 4.0.
    - The mode driver count for rural trips is ModeResult(mode=array([1], dtype=int64), count=array([32])).
- % of Total Fares by City Type
    - 62.7% of the total Fares are from Urban City Types
    - 30.5% of the total Fares are from Suburban City Types
    - 6.8% of the total Fares are from Rural City Types
- % of Total Rides by City Type
    - 68.4% of Rides are from Urban City Types
    - 26.3% of Rides are from Suburban City Types
    - 5.3% of Rides are from Rural City Types
- % of Total Drivers by City Type 
    - 86.7% of Drivers are in Urban City Types
    - 12.5 % of Drivers are in Suburban City Types
    - 0.8% of Drivers are in Rural City Types
    
We can guess that since there are a lot more drivers in Urban Cities compared to Suburban and Rural, that the cost per ride is lower and the count rides are much greater. 

## Challenge Overview
To create an overall snapshot of the ride_sharing data. he CEO would like to see a summary table of key metrics of the ride- sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

1. Create a PyBer Summary DataFrame
2. Create a multiple-line plot for the sum of the fares for each city Type

## Challenge Summary
***Please note: The Data Frame Summary is found in PyBer_Challenge, and the line graph Fig8 is found in the Analysis Folder in Github***

The analysis of the election (Module 5 Challenge) shows that:
- The Total Rides
    - Urban: 1,625
    - Suburban: 625
    - Rural: 125
- The Total Drivers
    - Urban: 2,405
    - Suburban: 490
    - Rural: 78
- The Total Fare:
    - Urban: $39,854.38
    - Suburban: $19,356.33
    - Rural: $4,327.93
- Average Fare per Ride:
    - Urban: $24.53
    - Suburban: $30.97
    - Rural: $34.62
- Average Fare per Driver
    - Urban: $16.57
    - Suburban: $39.50
    - Rural: $55.49   
- Total Fare by City Type (Fig.8)
    - The Fare for Urban city types is the greatest, then Suburban. The lowest fare out of all the city types is Rural. 
    - From  Jan 2019- to mid April 2019, the fare for all the city types do not change greatly. 
    - During this time frame, the Rural Fare stays ~$200-500, Suburban Fare stays ~$525-1500, and the Urban Fare stays ~$1600-2800. 

   
