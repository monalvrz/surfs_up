# Surfs_up

## Project Overview

This project consisted of an analysis of a dataset containing information about the climate of the island of Oahu in Hawaii, with the intention of providing information to an investor to consider opening a Surf n' Shake store on the island. After performing an initial analysis of the data, the investor W. Avy requested a more thorough analysis of the temperature data for the months of June and December on Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources

- Data Source: hawaii.sqlite
- Software: SQLite

## Results

After filtering the database to obtain only the data corresponding to the months of June and December, we performed a statistical summary that allows us to conclude the following: 

<img width="135" alt="june-statistics" src="https://user-images.githubusercontent.com/107893200/187957569-a5b7e042-c1f9-4984-b576-e9dc0905b15d.png"> <img width="164" alt="december-statistics" src="https://user-images.githubusercontent.com/107893200/187957633-b72ffd9f-5c3d-4b10-8060-8fdb9517452d.png">

- In the case of June we can see that within the years from 2010 to 2017 the highest temperature they have had is 85°F and the lowest is 64°F. The average is 74°F , which is within the range of the most pleasant climates in Hawaii between 73°F and 86°F according to the Audley Travel guide.
- In the case of December we can see that within the years from 2010 to 2017 the highest temperature they have had is 83°F and the lowest is 56°F. The average is 71°F, which is still a pleasant climate to enjoy the outdoors without being too hot or cold. 
-  On the one hand, one of the differences between the information collected for June and December is the number of entries for each. Although the difference is not significant, for June we have 1,700 entries and for December we have 1,517.
-  Another difference that can be observed by analyzing the statistical summary is that December has lower temperatures. The 25% percent of the recorded temperatures are in the range of 56°F and 69°F, a few degrees lower than in the case of June. 

## Summary

To complement the analysis of the temperature of the months of June and July, we have added to the project two graphs showing the average of precipitation in the years contained in the database from 2010 to 2017. This will not only take into consideration the temperature, but also how likely it is to rain during those months. 

![June Precipitation](https://user-images.githubusercontent.com/107893200/187969646-5f30f0a3-ed90-4fcd-934b-44e481639c21.png) ![December Precipitation](https://user-images.githubusercontent.com/107893200/187969672-1539dd2f-2bad-4514-bcec-4c2f9b37a411.png)

- Regarding the June graph we can observe that during most of the years the precipitation record is between 0.10 and 0.15, and only in 2011 and 2016 it passes the range of 0.20. This could mean that there are no records of abrupt changes in the levels of precipitation on the island during the month of June.
- On the other hand, the graph for December shows that there is a slightly higher amount of precipitation recorded during this month. While in 2010 we can observe a 0.45 precipitation level, in the following years it oscillates between 0.20 and 0.16. Although with small variations, the month of December does not document abrupt changes in precipitation on the island. 

Although overall, the analysis of temperature and precipitation shows that there is no alarming climate data for Oahu, it is pertinent to note that climate changes are not entirely predictable and that there may be significant changes over the years. For the time being, our analysis shows that the weather on the island is pleasant enough to invest in a Surf n' Shake store, and that in the months of June and December the weather would not severely affect the store's sales.



