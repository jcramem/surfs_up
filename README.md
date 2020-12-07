# Surfs Up

## Project Overview
The goal of this project is to determine if a surf and ice cream shop is sustainable year-round in Oahu by looking at temperatures for the months of June and December. 

## Resources
* Data Sources: SQLAlchemy *hawaii.sqlite* database
* Software: Python 3.7.6; Jupyter Notebook 6.0.3

## Results 
Distinct differences exist in ride-sharing data between city types. 

* As noted in the chart below, urban locales have substantially more drivers to accommodate substantially more rides. The farther one gets from urban areas, the fewer drivers and rides.   
* And yet the more rural the location, the higher the average fare, both per ride and per driver. This could be the result of the typical distance per ride in suburban and rural areas.

![June_Temperature_DataFrame](/June_Temperature_DataFrame.png).


![December_Temperature_DataFrame](/December_Temperature_DataFrame.png).


## Summary

Based on the analysis of ride-sharing data, Pyber may want to address the following:

* There are more rides than drivers in rural and suburban areas. To determine if the smaller number of rides in these areas is a function of fewer drivers, add more drivers. If rides increase, revenue increases based on the higher than average fares.
* Consider adding more or scaling back drivers for certain weeks. If drivers are willing to operate out of their typical city type, consider shifting driver areas based on weekly volumes. 
* Consider charging higher fares in urban areas based on sheer market demand.

