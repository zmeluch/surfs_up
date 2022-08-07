# Surfs Up

## Overview of Project
In advance of opening up a surf and ice cream shop in Oahu, statistical analysis of the weather
was done to make sure the conditions are ideal before presenting it to investors. Using a SQL lite
database, queries were performed on temperatures, preciptations and weather stations. 

### Purpose
In this analysis, W. Avy has asked for more specific information. He has asked for temperature data
for the months of June and December, to make sure the shop can be sustainable year round. To do this
the SQL lite database was queried using jupyter notebook, and filtered by month and then summary
statistics for each month were calculated.

## Results

![Summary Stats](https://user-images.githubusercontent.com/103155045/183305314-a7d11ef7-f98c-488a-a9c3-e631eae538a6.png)

- The minimum temperature difference between June (64) and December (56) is 8 degrees.
- The difference in the mean temperature is around 4 degrees.
- The max temperature difference between June (85) and December (83) is 2 degrees.


## Summary

- While there is a 8 degree difference in minimum temperature between December and June, for the most
	part the temperature difference is only about 4 degrees between the mean and the quartile ranges. 
- With this slight difference the shop business should be sustainable year round.
- An additional query to see the difference in precipitation between June and December could also be helpful
	in determining the year round success of the shop.
- Another query to see the difference in precipitation and temperature for a fall and spring month could give
	a more complete view of weather through the year to make sure business can be sustained year round.
