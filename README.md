# Overview of Analysis

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

- The first goal for this assignment will be to perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. 
- The second goal will be to use PySpark to perform a statistical analysis of selected data.

## Resources

Data Source: Amazon Review datasets, Video Games Review dataset
Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

# Results

## Total number of reviews

- Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129619664-740504ec-ca6c-48da-87e4-d41dee18fd55.png)

- Non-Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129619737-44b7d6b7-348e-4a43-865d-3a0c5895048c.png)

## Total number of 5-star reviews

- Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129619878-82bbf101-130f-4cfd-8306-abd6f4da7c3b.png)

- Non-Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129619950-c316f9a1-6149-40df-9c9e-9289e223ff39.png)

## Percentage of 5-star reviews

- Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129620005-0c896450-225e-4f04-b760-bb2343fa1706.png)

- Non-Vine reviews
![image](https://user-images.githubusercontent.com/82552594/129620070-6ea7cced-cafe-437b-87fc-be4209b6a4c0.png)

# Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
