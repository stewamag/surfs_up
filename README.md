# Surfs_Up

## Overview of the Analysis:

Analyzing weather data for a new surf shop on the island of Oahu. The prospective new shop owner wants to convince the board that this surf shop will be a worthwhile investment. In order to do so, it is important to show them that the weather on the island will be temperate enough for surfing year round. If the weather is too poor, the venture could fail.

SQL Alchemy, flask, and pandas were employed to determine whether the shop would be a good investment.

## Results:
  - Temperatures in the summer and winter (at least June and December) are very similar. Both have similar average and maximum temperatures. 
  - December does have lower temperatures on the bottom end. However, based off of the lower quartile, December's low temperatures are not very common. This means it is not something potential surfers would really have to worry about.
  - June appears to be the more temperate month where surfers could generally rely on warmer weather. 

June Temperature Summary:

<img width="134" alt="june_temps" src="https://user-images.githubusercontent.com/106691255/188289329-d609397b-b742-4f0a-9f59-db84fe99595a.png">

December Temperature Summary:

<img width="133" alt="dec_temps" src="https://user-images.githubusercontent.com/106691255/188289333-2f4ea850-6c53-43d7-ba98-d760efc31c34.png">


## Summary:

Overall, the temperatures seem mostly pleasant. There may be days where surfers would need to wear wetsuit, but that is just one more way for the surf shop to make some extra money.

It would be good for the board to know about precipitation, so I would personally (and did) add queries for December and June regarding the level of precipitation rather than just relying on temperature. Based off of the information below, December seems to bring much more rain than June, but it looks like most of the rain occurs across a small number of days and the rest see very little. Based off of this, it still seems that this would be a good island for a surf shop.

Precipitation Query:

<img width="1019" alt="precipitation" src="https://user-images.githubusercontent.com/106691255/188289358-23021c42-3bc5-4d32-a41b-de7c788a9b87.png">

June Precipitation Summary:

<img width="137" alt="june_prcp" src="https://user-images.githubusercontent.com/106691255/188289360-06985059-1559-4916-8941-42160afc25d0.png">

December Precipitation Summary:

<img width="139" alt="dec_prcp" src="https://user-images.githubusercontent.com/106691255/188289370-a0a7dda4-3d41-47f6-ab82-1ff24c7ad9f0.png">

Something else that could be helpful is checking into the temperature and precipitation during the spring and fall (perhaps March and September).

