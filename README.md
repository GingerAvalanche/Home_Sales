# Homework 22 - PySpark

## Description

This notebook analyzes data from home sales in the 2010-2017 period, to determine various basic details using the PySpark library and Spark distributed computing.

## Summary

Using SQL commands in PySpark, I was able to find:

* Average price of 4-bedroom homes
* Average price of 3-bedroom, 3-bathroom homes, grouped by year
* Average price of 3-bedroom, 3-bathroom, 2,000+ sq ft homes, grouped by year
* Average view rating of homes priced higher than $350,000

The last query was run in uncached, cached, and parquet-partitioned contexts. The parquet could've been the fastest, but the partitioning was done on an unrelated column, so extra work had to be done across Spark nodes, making it the slowest.

### Notes

I couldn't determine, from the directions, what one of the queries was actually supposed to be. I did my best to interpret it, but it could've meant one of half a dozen things.

### Source

No code was copied from external sources.
