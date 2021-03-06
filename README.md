# PyBer_Analysis

## Project Overview
PyBer operates a ride share application with drivers operating in Urban, Suburban and Rural cities. The purpose of this anlaysis is to look at how weekly fares differ by city type and how these differences can be used by PyBer to make address disparities among the city types.

## Resources
* Data Source: city_data.csv and ride_data.csv
* Software: Python 3.8.3
* Jupyter Notebook: 6.0.3

## Results
The analysis consists of two parts:
* a summary of ride-sharing data for each of the city types
* a line graph showing the Total Fares by City type for the period January 1, 2019 to April 29, 2019.

### Ride-Sharing Data Summary
In the summary we see that the average fare per ride and the average fare per driver is highest in rural cities with the lowest being in Urban cities.  This is easily explained given that Rural drivers account for only 5% of the total drivers.  Another observation that can be made from this summary is that the average fare per driver is lower than the average fare per ride for Uban cities, $16.57 and $25,53 respectively. This is not surprising given that the total drivers exceed the total rides in Urban cities which is not true for Rural and Suburban cities. 

Ride Sharing Summary
https://github.com/bedwardssmith/PyBer_Analysis/blob/main/Analysis/Ride_Sharing_Data_by_City_Type.png

### Total Fare By City Type
The line graph reflects the total fare per week for the period January 1, 2019 to April 29, 2019 for each type of city.  This shows that although the city type changes, the peaks are for the most part similiar; specifically late February. Although there are other peaks throughout this period the only other substantial peaks are for Urban cities during the period of early March and mid-March.  Another conclusion that can be drawn from the graph is that total fares for Urban cities experience greater fluctuations than both Suburban and Rural cities; peaks in late February, early March and mid March followed by significant decreases. 
 
Total Fare By City Type
https://github.com/bedwardssmith/PyBer_Analysis/blob/main/Analysis/Fig1.png

 ## Summary
 Based on the above analysis I would recommend the following to address the disparities between city types:
 * Increase the number of drivers in Rural cities. Although this will decrease the average fare per driver it will allow for greater growth within the Rural market.  With a lower fare per ride the service will be more appealing to the market thereby increasing demand.
 * Decrease the number of drivers in Urban cities as currently the total rides exceed the number of drivers.  The idea behind this recommendation is that the supply of drivers should be equal to demand.  Currently the supply of drivers is greater than demand thereby decreasing total fares. 
 * The line graph indicates that emphasis needs to be placed on growing the revenue of the Rural market. It can be seen that the total fares were fairly consistent for the period with small peaks indicating it is a market that is worth expanding.
 
 
