# Movies-ETL

## Overview

This project will extract, transform, and load movie data and ratings into a database for the Amazing Prime hackathon to identify which movies could become popular online. The database will provide hackathon participants with a clean dataset, removing duplicate or corrupt data and organizing similar datasets within the same format.

## Results

The resulting data tables have removed or combined extraneous columns and information. For example, some data listed directors under "Director" where others listed under "Directed by." Similar columns for editors, distributors, countries, and more were combined. Dollar amounts were also captured in different formats ($1 billion, $1.3 mil, $1,200,000, etc.) and cleaned up to compare the numbers in the same format. Some data were also mainly empty, so anything 90% empty was dropped, as it doesn't provide enough data to compare.

## Summary

Overall, the database gives us two tables with clean, organized, formatted data from Wikipedia, IMDB, and Kaggle for the hackathon participants to use in their project.