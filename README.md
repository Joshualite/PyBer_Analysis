# PyBer_Analysis
## Overview of the analysis
In this work, an analysis is carried out for a fictitious company called Pyber, which is in charge of offering the ridesharing service. We were asked to do two tasks in order to carry out the analysis, the first was about creating a summary in a database to clearly see the trips that are had in each type of city, and the second task was to create a graph of fares that are had in each type of city per week

## Resources
- Data source:city_data.csv , ride_data.csv
- Software: Python 3.7.0 , Anaconda , Jupyter
- Pyhton libraries : Numpy, Pandas, Matplotlib


## Results
Reviewing the database that was created, it allows us to analyze several points, first of all we can see that the amount of trips in urban cities are much greater than in rural or suburban cities, therefore the number of drivers is greater in cities Urban than in the rest.

Since the difference between the number of trips to each type of city is so great, it is logical to think that the gains in urban areas are much greater, and the database confirms this much, but from here there are things That should be shocked, having such a small number of drivers, the average price per trip increases much more in rural cities than in urban cities, with a difference of almost 10 dollars and the profits that each driver takes in rural cities is almost 3 times greater than one in an urban city

![image](https://user-images.githubusercontent.com/66183125/138624487-1ec091c3-1359-448a-80f7-d057cc8937a5.png)

The graph was made by taking the fire data of each type of city per week, the time range that was used was from the first week of January 2019 to the last week of April 2019.

In the analysis we can see something similar between urban, suburban and rural cities, the highest income is taken by urban cities, in second place is taken by suburban cities and lastly by rural areas.

Within this period of time, the highest point that both urban and suburban cities reached was the last week of February, while in rural cities this was in early April.

![image](https://user-images.githubusercontent.com/66183125/138624542-99c4fd21-5e03-4638-8b5c-a10af37c5e0d.png)


## Summary

After having carried out the analysis, some recommendations could be made or at least mentioned certain points that should be taken into account in the future.

 One of the reasons why incomes within rural areas are so low is because of the high prices they have, one may come to think that in rural cities people have a lower income than people generally have. In urban cities, for the same reason, the difference between the price of a trip between a Rural city and an urban one should not be so much, the reason why this is so is because of the small number of drivers that there are in rural cities To correct this, the distribution of drivers between cities could be improved, so first it would be:
- decrease the number of drivers in urban cities
- increase the number of drivers in rural areas

When doing this, two effects will be reflected immediately, the prices of trips in rural areas will decrease and also the profits that each driver has will decrease in rural areas, and the opposite effect will be had in urban areas,

It may be a bit risky, since the amount of trips in rural areas is too low, but I would also dare to think that the reason why there are almost no trips is because of the high price, it may be that by lowering the prices more people want use this service.

- A final recommendation would be to take care of the high and low seasons within the 3 different types of cities since there are peaks that are too low in certain seasons and you have to know why, so as not to lose more income to the company
