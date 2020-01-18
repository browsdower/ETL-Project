# ETL-Project

The project must use two or more sources of data.

Recommended sources are data.world, Kaggle, or Google: https://toolbox.google.com/datasetsearch.

Alternatively, you may use APIs or scrape data from the web. However, if you chose to do this, you should run it by the instructional staff first.

Once datasets are identified, perform ETL on the data, and document the following in a technical report:


Datasets used and their sources.<br>
  Github datasets of NFL game results for two different years for the Kansas City Chiefs. 
  https://github.com/ryurko/nflscrapR-data/tree/master/games_data/regular_season
  


Types of data wrangling performed, such as data cleaning, joining, filtering, and aggregating.
  Appending years 2018-2019
  Filtering non KC games out
  Dropping irrelevant / repetitive columns (Game type - all reg season).
  


The schemata used in the final production database, whether relational or non-relational.  
  Postgresql data upload
  Validation query 
