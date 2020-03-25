# SD-Collision-Hotspots

## Analysis of Traffic Collision Data in the City of San Diego 

In this project we have taken data produced by the City of San Diego - Police Division, which contains traffic collision data from 2018-Present.
Using this data and various data analysis tools, we search to find meaningful insights on traffic collisions in the City of San Diego. The ultimate goal is to use these insights to make recommendations on how to reduce traffic collisions.

## Link to Prezi Presentation: (https://prezi.com/view/lOSfHWlzNaSsjqI3qZ44/)

![Accident](images/accident.png)

### Questions & Observations

* What is the total number of collisions involving pedestrians, bicyclists, and other motor vehicles? Is one a greater problem than the other. 

  * **Findings:** Vehicle to vehicle collisions, by far, outnumber the collisions with pedestrians and bicyclists. Collisions with other motor vehicles were thousands, while collisions amongst the other two categories remained under 200.
		When looking at the data between Pedestrians and Bicyclists, we can see that collisions with pedestrians is the larger issue. This can be due to the sheer number of people vs bicyclist on the road, but this information 
		confirms that we should probably deploy more resources into making the streets safer for pedestrians, rather than bicyclist, which is where it seems a lot of resources tend to go. Further looking at the data for just Jan. to 
		Feb. and including 2020, we can see that collisions amongst these two groups have declined withing 2020 from the prior years.

![Bar1](images/Bar1.png)

![Bar2](images/Bar2.png)

![Bar3](images/Bar3.png)

* What are the most common causes of collision in San Diego? What are San Diego zip codes with a high volume of collisions?

  * **Findings:** The most common causes of collisions in San Diego include “No Turning Signals”, “Speeding”, “Vehicle Code Violation”, etc. Also, these collisions most commonly happen in high populated areas in San Diego such as: Pacific Beach, Mission Valley, Clairemont, etc.
		  These findings are consistent with my experience living and commuting in San Diego. Based on these findings, we can inform drivers of their behaviors and help avoid more collisions. 

![Pie-Plot](images/pie_plot.png)


* How do number of injuries/deaths due to collisions vary over the course of a day?

  * **Findings:** Our data, when grouped by hour of the day, shows that the injuries from collisions are most common during rush hour traffic, from 5-6pm. The data also confirms that, as the day goes on, hour by hour, up until 6pm, the number
		  injuries due to traffic collision increases. Whereas, the number of deaths due to traffic collisions does not appear to have any correlation with the time of day. The recorded number of deaths per hour are so low, between 0 and 11,
		  and there appears to be no trend showing what hour of the day a death due to a collision will occur. In conclusion, we know we want to work on stopping collision during the "rush hour" times of the day.

![Line1](images/Line1.png)

![Line2](images/Line2.png)


* What are the deadliest collision types, based on whether or not they kill or injure people?

  * **Findings:** Through this analysis, it became clear that certain collisions/violations were more prone to lead to deaths than injuries, even though the number of injuries are more common across all collisions. 
		  It is clear that “J-walking” and “Pedestrians outside of Crosswalks” are the two deadliest collisions, since they lead to death more often than the other collisions, when you compare the amount injured to killed.

![2bar](images/double_bar.png)

*What is the most common time of the day for DUIs? 

  * **Findings:** As any of us would anticipate, DUIs are most common at night, and least in the morning. 
		  They are lowest from 6am-7am, and are plateaued until 1pm, and then begin to climb in the amount of DUIs for the rest of the day, until 9-10pm where they are the highest. From there, they begin to decline until the early morning (6am). 
  
![2line](images/dui.png)

* Where are collision hotspots in San Diego? Can we view these geo-spatially using a heatmap?

  * **Findings:** Collisions are most common near busy cross streets, popular tourist & social destinations, and freeway off-ramps. Areas with higher population density also tend to have higher incidents of collisions.

![Heatmap](images/heatmap.png)

### Summary and Conclusions

* Injuries due to traffic collisions are highest during rush hour.
* Most common causes of collisions are "No Turning Signals" and "Speeding."
* Collisions are most common near busy cross streets, popular tourist & social destinations, and freeway off-ramps.
* DUIs occur in the later hours when social interaction and drinking is more common & the deadliest collisions are when pedestrians are careless.

* Our findings generally confirmed our hypotheses about San Diego Collision trends based on our own experiences.
* We recommend increasing fines for most common violations.
* We recommend deploying more police resources around rush hour. 
 

## Source Data
* https://data.sandiego.gov/datasets/police-collisions/

