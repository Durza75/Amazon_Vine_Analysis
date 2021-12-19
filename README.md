# Amazon Vine Analysis
## Overview
An analysis was performed on the Amazon Vine program in order to determine any possible bias towards positive reviews from vine members.

## Source
Amazon Review Datasets

## Tools
- PostgresSQL
- Amazon Web Service AWS
- Google Colab Notebook
- PySpark
- pgAdmin 4

Extracted the dataset, transformed the data, connected to an AWS RDS instance, loaded the transformed data into pgAdmin, and calculated different metrics. Conducted all the above via an ETL process.

## Summary
51% of the reviews in the Vine program were 5 stars, Non-Vine reviews on the other hand were low: as low as 39%. The analysis showed that a favorable bias exists towards the reviews in the Vine program.
