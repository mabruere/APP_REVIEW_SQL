# Apple Store Analysis SQL Queries

This repository contains SQL queries to analyze data from the Apple Store, focusing on app descriptions, ratings, genres, etc.

## Overview

The SQL queries provided in this repository cover a range of topics and are designed to provide insights into the Apple Store app data. These queries can be used to perform tasks such as:

- Combining data from multiple tables
- Checking for missing values
- Analyzing the number of apps per genre
- Investigating app ratings
- Comparing ratings between paid and free apps
- Exploring the correlation between supported languages and ratings
- Identifying genres with lower ratings
- Examining the relationship between description length and user ratings
- Finding the top-rated apps for each genre

## Queries

Below is a brief overview of each query included in this repository:

- Combining Tables: This query combines data from multiple `appleStore_description` tables to create a consolidated dataset.
- Unique App IDs: This query checks the count of unique app IDs in both the `AppleStore` table and the combined description table.
- Missing Values: This query counts missing values in specific columns for both the `AppleStore` table and the combined description table.
- Apps per Genre: This query calculates the number of apps in each genre using the `AppleStore` table.
- App Ratings**: This query retrieves the minimum, maximum, and average user ratings from the `AppleStore` table.
- Paid vs. Free App Ratings: This query compares the average ratings between paid and free apps in the `AppleStore` table.
- Languages and Ratings: This query checks whether apps with different numbers of supported languages have varying average ratings.
- Low-Rated Genres: This query identifies genres with the lowest average ratings in the `AppleStore` table.
- Description Length and Ratings: This query explores the potential correlation between app description length and user ratings.
- Top-Rated Apps per Genre: This query lists the top-rated app for each genre based on user ratings.
