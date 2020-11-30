# Introduction 

The purpose of this project is to understand the trends in the video game sales data over the years. This project also examines the sales data of long running video game series to determine if the newer titles perform better than the older titles in terms of sales. 

The video game sales dataset was downloaded from [Kaggle](https://www.kaggle.com/gregorut/videogamesales).

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
  
  ![Capture](https://user-images.githubusercontent.com/74891641/100587912-24911e80-332c-11eb-8dd2-fdddfed11578.PNG)
  
  2. Platform
  
  ![Capture](https://user-images.githubusercontent.com/74891641/100588177-80f43e00-332c-11eb-82b4-25a30c118983.PNG)
  
  3. Genre
  
  ![Capture](https://user-images.githubusercontent.com/74891641/100588297-a84b0b00-332c-11eb-9309-0603a555d6c7.PNG)

# Case study: Pokemon series
A case study was also conducted to determine the sales of video games from long running series such as Pokemon.
![Capture](https://user-images.githubusercontent.com/74891641/100588483-ddeff400-332c-11eb-80cc-e84a55835fd4.PNG)

# Conclusion
In this project, we cleaned the data and got rid of a few NaN values as we did not have the neccessary information to replace them with.

It was determined that over the years, the video game industry have been on the rise from the 1990s and it peaked around the late 2000s. It has then been on a decline from 2010. This trend is similar throughout the 4 regions.

We determined that the PS2 and PS3 were the most popular platforms for game developers as they both held 15.5% and 12% of the dataset. We also examined the sales of games by platform and determined that these values differ greatly from the US and JP market.

We determined that the most popular genre of games developed are Action and Sports but Platform and Role-Playing games are doing better in terms of average sales.

We also studied the sales of a long running video game series, Pokemon, to determine how the sales of Pokemon game change over the years. We can conclude that even though the sales of recent Pokemon games are weaker than that of the past, we can assume that the company is still profits with the release of each title.
  
