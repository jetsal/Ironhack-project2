# Ironhack-project2

This projects goal is to gather data from the internet - through webscraping - which can later be used for analysis. 

### Subject: The Race Arount The Netherlands 

Every year a bunch of cycling-fanatics set of to Race Around the Netherlands. This is a 1.913km long race with 4.164m elevation starting and ending in Amerongen (Utrecht). The route is predetermined, the rest is up to the riders. They have 9 days to finish the ride.
The race is not as much a race against competitors, as it is a race against the elements and well, quite frankly, a very painful backside.
Detailed race-data is available for the 2018-2021 editions, which will be the topic of this project.

In addition to the race-data, weather data will be gathered. Because as every cyclist knows: the weather has an impact on your ride.

### Repository content

#### RATN - reasearch questions.txt
- more detailed description of the subject and research questions

#### main.ipynb
This file can be used for analysis of the data (currently (dd 2021-5-18) empty)

#### Data-folder:
The data folder contains several Jupyter notebooks and csv's.

The leaderboard webscraping for each year is done in these Jupyter files (====> resulting csv):
- RATN - leaderboard_2018.ipynb ====> all_riders_2018.csv  
- RATN - leaderboard_2019.ipynb ====> all_riders_2019.csv  
- RATN - leaderboard_2020.ipynb ====> all_riders_2020.csv  
- RATN - leaderboard_2021.ipynb ====> all_riders_2021.csv  

The cleaning is done in these files (input csv's ===> Jupyter file where cleaning is performed ====> resulting csv):
- all_riders_2018.csv, all_riders_2019.csv, all_riders_2020.csv ====> all_riders_2018-2020_cleaning ====> all_riders_2018-2020_cleaned.csv 
- all_riders_2021.csv ====> all_riders_2021_cleaning ====> all_riders_2021_cleaned.csv

all_riders_2021_cleaned.csv and all_riders_2018-2020_cleaned.csv are ready to be concatenated.

For 2021 the ages are webscraped in this Jupyter file (====> resulting csv):
- RATN - ages_2021.ipynb ====> riders2021_name_age.csv

To concatenate these ages to the 2021 riders, use the name-info.

The datafolder also contains a zip-file of the route of the 2021 edition (gpx-files).