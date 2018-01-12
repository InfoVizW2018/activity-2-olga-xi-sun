## Assumption:

1,There are 4 berths in Tilbury

2, We can create two routes of vessel FL and VIL to meet the requirement

## What

### Dataset Type - TABLE

### Data:
	
	Vessel Name - ITEM
	Depart/Arrive Time - ATTRIBUTE
	Port Location - ITEM
	Routes - LINK
	Week - ITEM on a weekly basis

### Attribute type:
	
	Time is quantitative ordering data, the ordirection is cyclic and sequential

## Why

	According to customer’s requirement, we are going to DISCOVER the potential routes. Then we should PRESENT a new chart or diagram to make the data arrangement more clearly and efficiently. From the new chart, we can SEARCH the status of each vessel at anytime (QUERY) and deduce the potential route (DERIVE) between two available ports/berths (LOOKUP).

	Our Target is finding the available vessels and time (OUTLIERS) to create new routes. So the DISTRIBUTION of time and vessels is very crucial for our target.

## How

	We combine the three tables and rearrange the data (ARRANGE). First we separate the data from old tables (SEPARATE). The new table is ordered by time and vessel name (ORDER), and the new date is shaped and presented as rectangle (MAP-SHAPE) to show the relationship between vessels’ location and time. Customers would able to move the rectangle to adjust the routes to create a new and available schedule.

