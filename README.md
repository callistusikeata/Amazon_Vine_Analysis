## Amazon_Vine_Analysis

## Overview of Analysis

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

- The first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. 
- The second goal will be to use PySpark to perform a statistical analysis of selected data.

# Resources

Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

# Total number of reviews

Vine reviews



Non-Vine reviews



Total number of 5-star reviews
Vine reviews



Non-Vine reviews



Percentage of 5-star reviews
Vine reviews



Non-Vine reviews

## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
