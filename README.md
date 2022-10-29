# Amazon_Vine_Analysis


## Overview

The purpose of this project was to learn what can be catergorized as big data and how you effectively analysis it. Using Pyspark to perform the ETL process to extract the dataset, transform the data. As well as connect to a AWS RDS instance, and load data to pgAdmin.

The dataset consisted of Amazon Reviews written by members of a paid Amazon Vine program. Our duty is to use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset. The following resources were used to complete this project.

   * PySpark to handle large Datasets
   * PySpark to perform ETL
   * PySpark methods and functions to transform and filter data, and get DataFrame information
   * AWS Simple Storage Service
   * SQL & PgAdmin
   * Google Colab Notebook


## Results

Utilizing the above resources, the product reviews were counted and grouped by star ratings. The analysis found the following:

How many Vine reviews and non-Vine reviews were there?

   * There were 40,565 reviews in total. Out of that total, 94 were Vine (paid) reviews, and 40,471 non-Vine (unpaid) reviews.


<img width="637" alt="image 1" src="https://user-images.githubusercontent.com/90155651/198793429-aadf8cf7-ddda-4bf2-a35e-3162a0426df6.png">




