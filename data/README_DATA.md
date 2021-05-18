This data folder contains several Jupyter notebooks and csv's.

### webscraping leaderboards
The leaderboard webscraping for each year is done in these Jupyter files and result in the after the '====>' mentioned csv:
- RATN - leaderboard_2018.ipynb ====> all_riders_2018.csv  
- RATN - leaderboard_2019.ipynb ====> all_riders_2019.csv  
- RATN - leaderboard_2020.ipynb ====> all_riders_2020.csv  
- RATN - leaderboard_2021.ipynb ====> all_riders_2021.csv  

### cleaning leaderboards
The cleaning is done in these files (input csv's ===> Jupyter file where cleaning is performed ====> resulting csv):
- all_riders_2018.csv, all_riders_2019.csv, all_riders_2020.csv ====> all_riders_2018-2020_cleaning ====> all_riders_2018-2020_cleaned.csv 
- all_riders_2021.csv ====> all_riders_2021_cleaning ====> all_riders_2021_cleaned.csv

all_riders_2021_cleaned.csv and all_riders_2018-2020_cleaned.csv are ready to be concatenated.


### weather
Wind direction is still missing, but temp, rain_mm, rain_hours and wind speed are scraped and cleaned in:
- Weather_excl_wind_dir.ipynb ====> weather_excl_wind_dir.csv

### ages: scraping and cleaning
For 2021 the ages are webscraped in this Jupyter file and results in the after the '====>' mentioned csv::
- RATN - ages_2021.ipynb ====> riders2021_name_age.csv

To concatenate these ages to the 2021 riders, use the name-info.

### route
The route2021_aprilversion.zip contains the route of the 2021 edition (devided into several gpx-files).