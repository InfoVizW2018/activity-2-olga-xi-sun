## Assumption:

* There are 4 berths in Tilbury

* We can create two routes of vessel FL and VIL to meet the requirement

## What

### Dataset Type - TABLE

### Data:
    
* Vessel Name - ITEM
* Depart/Arrive Time - ATTRIBUTE
* Port Location - ITEM
* Routes - LINK
* Week - ITEM on a weekly basis

### Attribute type:
    
Time is quantitative ordering data, the ordering direction is cyclic and sequential

## Why

According to customer’s requirement, we are going to DISCOVER the potential routes. Then we should PRESENT a new chart or diagram to make the data arrangement more clearly and efficiently. From the new chart, we can SEARCH the status of each vessel at any time (QUERY) and deduce the potential route (DERIVE) between two available ports/berths (LOOKUP). We also annotate the berth number to indicate the capacity of each port.

Our Target is finding the available vessels and time (OUTLIERS) to create new routes. So the DISTRIBUTION of time and vessels is very crucial for our target.

## How

We combine the three tables and rearrange the data (ARRANGE). First, we separate the data from old tables (SEPARATE). The new table is ordered by time and vessel name (ORDER), and the new date is shaped and presented as a rectangle (MAP-SHAPE) to show the relationship between vessels’ location and time. Customers would able to move the rectangle to adjust the routes to create a new and available schedule.

## Design Study Methodology

## PRECONDITION

* Learn: background investigation about Seaspan ferry and bc ferry situation, and get the information from varying channel, such as website, google map, etc. Otherwise, a technical and professional knowledge learning is necessary. we should study data analysis tech and visualization method and tools.

* Winnow: Collaboration sometimes is very useful for understanding the requirement and data meaning. But in this activity, this stage could be skipped.

* Cast: We define the roles in this stage, students should be a front-line analyst who is responsible for data analysis and meet the requirement. The instructor might be a gatekeeper to verify the result.

## CORE

* Discover: In this stage, we summarize the requirement of customers and make a clear target in order to avoid useless workload.

* Design: we work on the current schedule, separate and abstract data such as depart/arrive time and routes. We should choose proper tools and algorithms to encode the date.

* Implement: As we mention in the last stage, in this case, we use excel as a framework, rearrange the data into a new sequence and present information in different shape and colors.

* Deploy: If necessary, we could present our prototyping design and assumption to Seaspan or other experts for validation, and gather feedback for modification and new solution.

## ANALYSIS

* Reflect: collect more evidence to validate our prototype, if there was conflict or mistake, we would go back to the previous stage to optimize our design.

* Writing: Ater Reflection, we should write a study paper for potential researchers to continue our design.

## PITFALLS

* PF-1: we just need to focus on the schedule, In learning stage, we would research vary backgrounds such as geographic information or other ferry company's schedule. That just is a background, we should not be affected by the peripheral information.

* PF-4: According to the Seaspan's requirement, they want to know how full of each vessel. But there is no data about a load of each vessel, we could not deduce the assumption.

* PF-11: During the design, we should communicate with collaborators, such as Seaspan or other co-workers, so that we could not misunderstand their problems and purpose.

* PF-23: the design should be able to extend to the new dataset, if their data changes, the same prototype could be applied to a new dataset.

* PF-29：In this case, we did not use too many technologies or algorithms to the design, but it does not mean it is not a good study.



