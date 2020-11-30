# Introduction 

We would like to analyse the data for video game sales. The video game sales dataset was downloaded from Kaggle. The dataset was scrapped from vgchartz.com. 

First and foremost, the required libraries will be imported. 
We then use pandas read the csv file.

# Importing and cleaning data

We imported the data using pandas and studied the types of data in the dataset.
Several changes were applied to the dataset, these changes include:
  1. Dropping "NaN" values from the dataset
  2. Converting the "Year" column to "int" from "float"
  
  
  3. Filtering out years where data is incomplete ie. 2017 to 2020
  4. Limiting our dataset to games which made at least 1 million in global sales

# Data Analysis

The data was analyzed according to sales of video game by the following metrics:
  1. Region
  2. Platform
  3. Genre

# Conclusion
A case study was also conducted to determine the sales of video games from long running series such as Pokemon.

In this project, we cleaned the data and got rid of a few NaN values as we did not have the neccessary information to replace them with.

It was determined that over the years, the video game industry have been on the rise from the 1990s and it peaked around the late 2000s. It has then been on a decline from 2010. This trend is similar throughout the 4 regions.

We determined that the PS2 and PS3 were the most popular platforms for game developers as they both held 15.5% and 12% of the dataset. We also examined the sales of games by platform and determined that these values differ greatly from the US and JP market.

We determined that the most popular genre of games developed are Action and Sports but Platform and Role-Playing games are doing better in terms of average sales.

We also studied the sales of a long running video game series, Pokemon, to determine how the sales of Pokemon game change over the years. We can conclude that even though the sales of recent Pokemon games are weaker than that of the past, we can assume that the company is still profits with the release of each title.
  
