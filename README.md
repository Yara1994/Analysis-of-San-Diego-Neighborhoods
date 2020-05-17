# Analysis-of-San-Diego-Neighborhoods

## Introduction/Business Problem

I live in San Diego, CA.
So, i've decided to explore and analyze neighborhoods in this wonderful city to understand is it any correlation between median household income and amount of schools.

I found the great GeoJSON file from Zillow that consists of all USA Neighborhoods in USA, with latitude and longitude information. I will filter it to find all Neighborhoods in San Diego. Then i will scrape https://www.homesnacks.net/richest-neighborhoods-in-san-diego-129013/. This web page represents "List Of The Richest Neighborhoods In San Diego For 2020". After preprocessing the data, i will start playing with Foursqure API to find out how many schools in each neighborhood and then cluster them. 

We will answer the question:

# "Does it mean that in the richest neighborhoods more and better schools than in Poorest Neighborhoods?".
