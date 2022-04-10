# PyBer Ride Sharing Analysis

## Overview:

The purpose of this analysis is by using the raw data, to create a number of charts to visualize the dynamic between the type of the communities (Urban, Suburban and Rural) and the numbers of riders and drivers as well as the percentages of total fares, riders and drivers by type of city. This analysis should help the ride sharing company PyBer to be able to make decisions about which types of cities needs more driver support.

## Results:

We first merged the two data files by their common element which was the name of the city to have one DataFrame showing all the information for this analysis.

We then split the main DataFrame into three different DataFrames for each type of city. We were then able to create reports and numbers and charts based on type of community, that would help the CEO and stakeholders in PyBer to decide which type of city needs more support and investment.

We calculated the number of rides for each city type, the average fare for each city type and number of drivers for each city type. With this information, we were able to create a bubble chart that would show all that in one single chart, as below:

![Pyber_Ride_Sharing](/analysis/Fig1.png "PyBer Ride-Sharing Data")

We then created the statistical summaries for Number of Rides, Fares and Number of Drivers by city type and created a whisker and box plot to see if there are any outliers in the data that we have and also where our minimums and maximums, median and 1st and 3rd quartiles are. Figure as below:

![Ride_Count_Data](/analysis/Fig2.png "Ride Count Data")

In the Ride Count Data plot figure, we can see that there is an outlier in the data pertaining to the Urban rides, that we can take a look at, to see if it should be taken out of the data set or be left there.

![Ride_Fare_Data](/analysis/Fig3.png "Ride Fare Data")

In the Ride Fare Data figure, we can see that the overal Fare for Rural areas is higher than the urban and suburban cities, and even the median fare for rural areas is higher than the upper quartile of the urban fare rides, which could mean that it would be less affordable in rural areas to use the service.

![Driver_Count_Data](/analysis/Fig4.png "Driver Count Data")

In the Driver Count Data figure, we can see that the number of drivers in the rural areas are much lower than the urban areas. The low number of drivers could mean more wait time and higher fares, which will result in lower ridership.


We then calculated the percentages of Urban, Suburban and Rural areas for the Total Fares, Total Rides and Total Drivers and to showcase them the best, we used pie charts that best show the shares of a whole, like percentages. figures shown:

![Percentage_of_Total_Fares](/analysis/Fig5.png "Percentage of Total Fares")

This pie chart shows that over 60% of the Pyber revenue is from the Urban cities!


![Percentage_of_Total_Rides](/analysis/Fig6.png "Percentage of Total Rides")

This pie chart shows that about a quarter of the total rides using PyBer is done in suburban cities.


![Percentage_of_Total_Drivers](/analysis/Fig7.png "Percentage of Total Drivers")

The pie chart shows that over 80% of the PyBer drivers serve the urban cities and only under 3% work in rural cities.


## Summary:

By looking at the first bubble chart that we plotted, we can clearly see that the number rides are lower in Rural areas comparing to suburban and then urban which can be partly due to the lower density of population in rural cities, but what also catches the attention is that the fares are much higher in the rural areas, which can also be a factor for lower ridership. PyBer, can lower the fares for rural areas by increasing the number of drivers and most probably lower the wait times and this can also help increasing the ridership. Similarly, by looking at the pie charts, we can see that suburban areas can also get some boost in the number of drivers since they have about 30% share of the rides but only  16% of the share in the number of drivers. So we can recommend based on the charts and data, to:

1) Increase the number of drivers in rural areas
2) Lower the fares in the rural areas
3) Increase the number of drivers in suburban areas
