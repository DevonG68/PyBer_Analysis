# PyBer_Analysis

Module 5 MatPlotlib PyBer_Analysis

Background: 
  Perform exploratory analysis on data in large csv files, create visualizations to tell a compelling story about the data, write python scripts using panda        library, jupyter notebook, and matplotlib to create a variety of charts. This will help showcase relationships between the type of cities, number of drivers      and riders, and obtain percentage of total fares ,riders ,and drivers by the type of city This analysis is for Pyber, a python-based ride sharing app             company. The analysis will help the company improve access to ridesharing services and determine affordability for underserved neighborhoods. 

Resources: 
  Matplotlib (python 2-dimensional plot library) to create line charts, bar charts, scatter plots, bubble charts, pie charts, and box-and-whisker plots, and make   them visually compelling and informative by adding titles, axes labels, legends, and custom colors. 

  Jupyter Notebook, Pandas, SciPy (statistical Python package), and NumPy (package scientific computing in Python)to inspect data, merge data sets, create data     series and dataframes, and perform calculations and summary statistics.

Assignment: 
  Use Python and knowledge of Pandas, to create a summary DataFrame of the ride-sharing data by city type. Then, use Pandas and Matplotlib, to create a multiple-   line graph that shows the total weekly fares for each city type. Finally, submit a written report that summarizes how the data differs by city type and how       those differences can be used by decision-makers at PyBer.

  Consists of two technical analysis deliverables and a written report to present your results. You will submit the following:
    •	Deliverable 1: A ride-sharing summary DataFrame by city type
    •	Deliverable 2: A multiple-line chart of total fares for each city type
    •	Deliverable 3: A written report for the PyBer analysis (README.md) 

Overview of the analysis:
1.	The purpose of the new analysis is to explore data
Perform exploratory analysis on data from large csv files provided by a ridesharing app company name PyBer. Goal is to analyze data using python Dataseries and DataFrame calculations to retrieve data and evaluation relationship between total number of rides for each type of city, total number of drivers for each type of city, total amount of fares for each type of city, and the average cost of fare per ride and per driver for each type of city. The city types included urban, rural, and suburban. Then create a summary DataFrame to easily evaluate and identify the number of those accessing services and potential affordability or average cost amount for neighborhoods based on the type of city. Cleaned up the data, created new dataframes and drilled down deeper to evaluate the average fare per week from January 1, 2019, to April 29, 2019, for each of the city types. Then resampled the data to get to the sum of fares for each week within that timeframe. Finally, create a line graph to visually tell the story of total fares per city type within those specific dates of service. The data metrics and visualizations devised will be used in determining disparities for underserved neighborhoods per each city type.

2.	Results:
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt.)
This DataFrame provides a summary of metrics that shows potential disparities in the total rides, total drivers, total fares, average fare per rider, and average fare per driver per city type. 

 ![image](https://user-images.githubusercontent.com/85171897/142746950-be2ba2f3-4220-4484-a27f-69a44f3dfcf5.png)

This shows rural area has the least number of rides in comparison to Urban having the greatest number of rides. This gap could be due to the total number of drivers with Rural have less drivers (537) and urban having the most out of all three city types (59,602). Urban has the highest number of drivers and brings in the most revenue in comparison to Rural and Suburban areas combined. This could be partly due to the average fare cost per ride is less than Rural and Suburban city type. The driver’s average cost of fare is significantly lower in Urban city type showing $0.67 in relation to the other areas showing $2.00 or more. There is a significant gap in this space as well with Rural average fare per driver is the highest at $8.06 and Suburban around $6.00 less at $2.26. In summary, the metrics in the DataFrame clearly shows Urban city type brings in the most revenue due to the increased number of rides that occur with the highest number of drivers providing rides at the lowest cost of fare per ride and per driver.
The multiple line chart below provides a visualization of metrics sated above clearly showing the total fares per each city type within the dates of January 1, 2019, to April 29, 2019. As you can see, Urban city type has significantly higher numbers of total fares than Rural and Suburban city types. All three city types had an increase in numbers in or around the month of March. Then showing a decrease in total fare amounts as got closer to or in the month of April.
 
 ![image](https://user-images.githubusercontent.com/85171897/142746957-5a2ad42e-b570-4bff-b53a-cd57bebd2ff4.png)

 
3.	Summary:
In retrieving and calculating the metrics for each city type, the following recommendations in determining disparities among neighborhoods include:

•	Rural city type has the lowest total number of rides, drivers, and amount of revenue per total amount of fares. However, I question why the average amount of fare per rider and driver is the highest. I recommend offsetting these numbers, increase the number of drivers in this area and lower the cost of fares for riders and drivers. This will help increase the number of rides, drivers and amount of revenue acquired in Rural city type.
•	Based on metric calculations, the Suburban city type the middle performing city in comparison to all three areas.  I recommend trying to replicate Urban city type and get close as possible in investing in this city type as well as the Rural area in order to increase revenue and provide service to more riders and jobs for more drivers.
•	Urban city type has the highest total fares amount and total number of rides and drivers, with the lowest average amount of fare per ride and drive.  This city type is the highest performing and brings the most revenue into the company based on total amount of fares. Continue with strategic plan and investments for this city type. However, try to replicate what is done in this city type to help increase revenue in the Rural and Suburban city types.
![image](https://user-images.githubusercontent.com/85171897/142746917-44f68647-6e38-4527-b8b4-f90174ae2a2f.png)
