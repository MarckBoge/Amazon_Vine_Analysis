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


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

   * After analysising the data I found that there was a total of 15,711 5-star reviews, 48 of which was Vine (paid) reviews, and 15,663 were non-Vine (unpaid) reviews.

<img width="726" alt="image 2" src="https://user-images.githubusercontent.com/90155651/198798533-3fe502f5-d962-4a59-9a1d-ae738e569fad.png">


