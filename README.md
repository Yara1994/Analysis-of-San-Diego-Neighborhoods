# Analysis of Schools in San Diego Neighborhoods 

----------------------------------------------------------------------------------------------------------------------------------------

## Introduction

I live in San Diego, CA.
So, i've decided to explore and analyze neighborhoods in this wonderful city to understand, is it any correlation between median household income and amount of schools in this neighborhood.

The main question is:

# Does it mean that in the richest neighborhoods more and better schools than in Poorest Neighborhoods?.

---------------------------------------------------------------------------------------------------------------------------------------

### Target Audience:

* Families with kids, who moving in in San Diego. They know their income, they want their kids to go to the right school, so this will help them to find right place.
* Budding Data Scientists, who wants to implement some of the most used Exploratory Data Analysis techniques to
obtain necessary data, analyze it and, finally be able to tell a story out of it.

# Initial Data Preparation:

## GeoJSON file

I found the great GeoJSON file [Zillow Neighborhoods](https://data.opendatasoft.com/explore/dataset/zillow-neighborhoods%40public/information/) that consists of all USA Neighborhoods with latitude and longitude information. 
After filtering and cleaning data we get dataframe with all neighborhoods (121) in San Diego City (NOT COUNTY!).

![San_Diego_Neighborhoods_DF](Images/San_Diego_Neighborhoods_DF.PNG)


## Web-Scrapping 

Then we scraped [Richest Neighborhoods In San Diego For 2020](https://www.homesnacks.net/richest-neighborhoods-in-san-diego-129013/) using **Beautiful Soup** library. This web page represents "List Of The Richest Neighborhoods In San Diego For 2020". 

![Richest_San_Diego_Neighborhoods_DF](Images/Richest_San_Diego_Neighborhoods_DF.PNG)

## Completed San Diego Neighborhoods Data Frame

I had to merge 2 above dataframes to get final dataframe that we will work with.

![Completed_San_Diego_Neighborhoods_DF](Image/Completed_San_Diego_Neighborhoods_DF.PNG)

----------------------------------------------------------------------------------------------------------------------------------------





















