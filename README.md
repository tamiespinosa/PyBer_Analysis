# PyBer_Analysis

## Table of Contents
- [Overview of Project](#OverviewProject)
  * [Purpose](#purpose)
- [Results](#Results)
  * [Scatter Plot](#scatter)
  * [Box and Whisker Plots](#boxw)
  * [Pie Charts](#piechart)
  * [Line Chart](#linechart)
- [Summary](#Summary)
- [Resources](#Resources)

## <a name="OverviewProject"></a>Overview of Project

Pyber, a ride sharing app, wants an exploratory analysis of the data using visualization.  The data to be analyzed includes the city where the ride took place, the date, number of drivers per city,  the type of city for every city (suburban, urban and rural) for 2019 [[3]](#3)[[4]](#4). We will use this opportunity to determine affordability for underserved neighborhoods. 

### <a name="purpose"></a>Purpose

As part of the analysis we would determine the following paramenters:
 - The relationship between the average fare per city and the total number of rides per city. 
 - We will create whisker and box plots with:
   * Number of rides per city type,
   * Average ride fare per city type, 
   * Number of drivers per city type. 
 - We will explore the percentage of:   
   * Total rides per city type,
   * Total fares per city type, 
   * Drivers per city type. 
 - We will look into trends fares per city type over a period of 4 months.   

We used python and matplotlib to create the analysis [[1]](#1)[[2]](#2).

## <a name="Results"></a>Results

### <a name="scatter"></a>Scatter Plot

<p align="center"> <img src="analysis/Fig1.png" width ="70%" alt="Fig1"> </p>
<p align="center"> Figure 1: Pyber Ride Sharing Data (2019) </p> 

### <a name="boxw"></a>Box and Whisker Plots


<p align="center"> <img src="analysis/Fig2.png" width ="70%" alt="Fig2"> </p>
<p align="center"> Figure 2: Ride Count Box and Whisker Plot </p> 

<p align="center"> <img src="analysis/Fig3.png" width ="70%" alt="Fig3"> </p>
<p align="center"> Figure 3: Ride Fare Box and Whisker Plot </p> 

<p align="center"> <img src="analysis/Fig4.png" width ="70%" alt="Fig4"> </p>
<p align="center"> Figure 4: Driver Count Box and Whisker Plot </p> 

### <a name="piechart"></a>Pie Charts


<p align="center"> <img src="analysis/Fig5.png" width ="70%" alt="Fig5"> </p>
<p align="center"> Figure 5: Percentage of Total Fares per City Type </p> 

<p align="center"> <img src="analysis/Fig6.png" width ="70%" alt="Fig6"> </p>
<p align="center"> Figure 6: Percentage of Total Rides per City Type </p> 

<p align="center"> <img src="analysis/Fig7.png" width ="70%" alt="Fig7"> </p>
<p align="center"> Figure 7: Percentage of Total Drivers per City Type </p> 

### <a name="linechart"></a>Line Charts

In this graph we can see that although there is no noticeable tren of when the prices will increase or decrease, except maybe a slight peak towards the end of February, the tital fares of urban cities are always about 3-4 times higher than those of rural cities, and suburban cities are about twice as high as rural cities. Urban cities always compromise the majority of the total fares Pyber has. 

<p align="center"> <img src="analysis/Pyber_fare_summary.png" width ="100%" alt="Pyber_fare_summary"> </p>
<p align="center"> Figure 8: Pyber Fare Summary</p> 

## <a name="Summary"></a> Summary

In general the price of the fares for rural areas is higher than in suburban and urban areas. Yet there's less number of rides and drivers in rural areas than in suburban and urban areas. This could be due to distances being longer in rural areas, therefore increasing the price of the ride. Additionally rural areas are less densely populated therefore decreasing the availability of drivers and number of rides. Yet discounts in rural areas could incentivize the users to increase the number of rides which overtime could improve the profits for drivers. 

## <a name="Resources"></a>Resources

<a name="1">[1]</a> [Analysis Code 1 (Challenge)](https://github.com/tamiespinosa/PyBer_Analysis/blob/8ebcdeea678b7b5232dd7a593e6c8d62eb9b900a/PyBer_Challenge.ipynb)

<a name="1">[2]</a> [Analysis Code 2](https://github.com/tamiespinosa/PyBer_Analysis/blob/8ebcdeea678b7b5232dd7a593e6c8d62eb9b900a/PyBer.ipynb)

<a name="2">[3]</a> [City Data](https://github.com/tamiespinosa/PyBer_Analysis/blob/8ebcdeea678b7b5232dd7a593e6c8d62eb9b900a/Resources/city_data.csv)

<a name="3">[4]</a> [Ride Data](https://github.com/tamiespinosa/PyBer_Analysis/blob/8ebcdeea678b7b5232dd7a593e6c8d62eb9b900a/Resources/ride_data.csv)

[5] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
