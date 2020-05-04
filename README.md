# PyBer Analysis Report

## Background 
As data analysts at PyBer, a ride sharing company, my team was assign an analytical project to analyze the relationship between type of city, fares, and numbers of drivers and riders, which aim to generate insights for company's future strategies to provide better service and increase revenue. 

### Purpose
There are two technical analyses in this project. The first one is to create a DataFrame of the key metrics for the ride-sharing data by city type, including total rides, total drivers, total fares, average fare per ride and average fare per driver. The second one is to create the multiple-line graph that shows the total fares for each week by city types. Both technical analyses can help us gain insight from data information and make appropriate adjustments based on the needs from different city types. 

### Technical Analysis
  From the first technical analysis, we caculate the total rides, total drivers, total fares, average fare per ride and average fare per driver, and display the numbers in a table. The table shows that urban cities have significant higher number of total rides and the lowest average fares. We can observe a negative relationship between the number of rides and the avereage fares.In the opposite, rural areas have the highest average fares and the lowest amount of rides, but there is no evident correlation to average fares. 
  In the second technical analysis, we created line graphs to compare the total fare for each week by city types. We can observe that urban areas have the highest total fares all the time, and the total fares of rural cities are only one fourth of the urban area. 
  
### Summary
The results shows that there are uneuqal market share in urban, suburban, and rural areas. Urban areas have high demand of rides as well as high supply of drivers, which make the average fares decrease. Rural areas have low demand of rides, therefore small numbers of drivers in these cities will make the average fare higher. In both techinal analyses, we can confirm that the total fare is positive related to the total number of rides.

### Challenges and Difficulties Encountered
* Programming:using functions such as groupby() and resample() to calculate the weekly fares

* Graphing: still need more practies to formate the graphs

### Technical Analyses Used
The data was analysed using Python module Pandas and MatPlotlib.

## Recommendations and Next Steps
I would like to recommend the company to adjust the number of drivers in different types of city based on the demand of rides. Also, I think we should consider how the population, geographic size, and travel distance per ride for our future analyses. 

### Recommendations for Future Analysis
In the future, it is necessary to clarify the process and make a list of steps before start the analysis.
