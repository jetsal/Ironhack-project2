# Ironhack-project2

This projects goal is to gather data from the internet - through webscraping and an API - which can later be used for analysis. 

Subject:
Every year a bunch of cycling-fanatics set of to Race Around the Netherlands. This is a 1.913km long race with 4.164m elevation starting and ending in Amerongen (Utrecht). The route is predetermined, the rest is up to the riders. They have 9 days to finish the ride.
The race is not as much a race against competitors, as it is a race against the elements and well, quite frankly, a very painful backside.
Detailed race-data is available for the 2018-2021 editions, which will be the topic of this project.

Additionally weather data will be gathered through the KNMI-API. Because every cyclists knows that the wind impacts how fast you go.

Jupyter-files present:
- RATN - ages_2021: scraping the ages of the riders in 2021
- RATN - leaderboard: scraping the names, sex and check-point-timings from 2018-2021
- KNMI - gathering weather data through the KNMI API

The RATN-files save the DataFrames to csv's. These CSV's are present in the data-folder.
