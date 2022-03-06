# Surfs Up
Weather Analysis for surfing and ice cream shop business.
## Project Overview
This project involves gathering data on the seasons of Oahu and determining whether the seasons could affect the surf and ice cream shop business. Specifically, are there certain times of the year when business might be slower, or the type of customer could be different?

### Tools
This shop can easily become a popular spot, potentially expanding to other Hawaiian Islands and other further-distance islands. Because of the potential quick turn-around, the analysis is built by using quick and fast tools:

• SQLite a popular database engine, a version of SQL, that is stored locally and supports quick testing and easy prototyping.

• SQLAlchemy a query tool design for SQLite to query SQLite databases.

### Summary:
Comparison of the Temperatures for June and December

1. Number of data

    •	There are less data for December (1517 data points) than for June (1700 data points).

2. Dispersion of the data

    •	Temperatures are more spread out in December (std = 3.7) than in June (std = 3.3).

   •	June’s mean and median are 74.94 °F and 75.00 °F respectively.

   •	December’s mean and median are 71.04 °F and 71.0 °F respectively.

   •	Maximum temperature in December is 83 °F and in June 85 °F.

   •	Minimum temperature in December is 56 °F and in June 64 °F.

3. Quartiles

    •	1st quartile: 25% of all data is below 69 °F in December and 73 °F in June.

     •	3rd quartile 75% of all data is below 74 °F in December and 77 °F in June.

The June-2017 and December-2016 key statistical data across all of the stations has been shown below:

![image](https://user-images.githubusercontent.com/95595378/156913358-6c31b38f-fde6-4780-b713-ac5a90f4f012.png)

As per the above table, the observations are :

  •	The minimum, mean and maximum temperatures in June(summer) is more than that of December(winter), which is suitable for the surfing and ice-cream shop. The standard deviation in temperature for June is less than that of December.

  •	The counts of temperature for the month of June is also less than that of December. Because of the more standard deviation in the month of December, the   weather across all the stations varies more as compared to the month of June.

  •	As per the above observations, the surfing and ice-cream shop will make more profit in the month of June as compared to the month of December.

### Recommendations

  •	For further analysis, we should increase our range of summer and winter months for a better and in-depth analysis.
  
  •	We can also do a separate analysis for the best stations using filter based on the total number of observations.
  
  •	We can also drop the stations which are outliers in terms of data for our analysis.
