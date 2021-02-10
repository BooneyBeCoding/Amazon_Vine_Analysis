# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to analyze Amazon reviews written by reviewers paid by the Amazon Vine program. This program allows companies to receive reviews for their products written by Vine members who are receive the products and are required to publish a review. For the project I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. I then used Pyspark to analyze the data to determine if any bias existed from Vine member reviews.

## Results

-- There were 0 Vine (paid) reviews and 1,563 non-Vine (unpaid) reviews.

-- There were 0 5-star Vine reviews and 80,677 5-star non-Vine reviews.

-- 0.0% of Vine reviews were 5 stars and 100% of non-Vine reviews were 5 stars.

## Summary

Based on this analysis...it doesn't look like the Vine Reviewers are avid gamers, or gamers at all.
