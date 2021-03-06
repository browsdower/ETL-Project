# ETL-Project

The project must use two or more sources of data.

Recommended sources are data.world, Kaggle, or Google: https://toolbox.google.com/datasetsearch.

Alternatively, you may use APIs or scrape data from the web. However, if you chose to do this, you should run it by the instructional staff first.

Once datasets are identified, perform ETL on the data, and document the following in a technical report:


**Datasets used and their sources.**<br>
  + Github datasets of regular season NFL game results and play by play data
  + Two different years (2018 and 2019)  
  + https://github.com/ryurko/nflscrapR-data/tree/master/games_data/regular_season
  + https://github.com/ryurko/nflscrapR-data/tree/master/play_by_play_data/regular_season
  


**Types of data wrangling performed, such as data cleaning, joining, filtering, and aggregating.**<br>
  + Create Postgre database and set up tables.
  + Appending years 2018 and 2019.
  + Filtering non KC games out from dataset
  + Cleaning irrelevant / repetitive columns (Game type - all reg season) and unneeded play by play data.  Will only need EPA, date, team data from the play by play data.
  + Using Python and Pandas to create dataframes with necessary data columns from a CSV source.
     + Create dataframe from all data
     + Create new dataframe with Game_ID, Possession Team, Game Date, EP, and EPA
     + Find only KC Games
     + Sum EPA totals by game
     + Export new CSV data
     + Import new CSV (KCEPA) into Postgre
     
  

**The schemata used in the final production database, whether relational or non-relational.** <br>
 + Creating table schemata
 + Create DB
 + Postgresql data upload
 + Validation query 
