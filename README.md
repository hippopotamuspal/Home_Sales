# Home Sales Analysis with SparkSQL

This project analyzes home sales data using PySpark and SparkSQL to compute key metrics and best manage data handling. 

## Key Features
- **Data Analysis:** Calculate average home prices based on various criteria, including bedrooms, bathrooms, year built, and view ratings.
- **Caching and Optimization:** Compare query runtimes for cached and uncached data to highlight Spark's in-memory processing benefits.
- **Partitioning:** Partition data by the date_built field for optimized storage and retrieval.
- **Parquet Integration:** Work with Parquet files to demonstrate efficient data handling and querying.

## Instructions
The project includes code to:

1. Load and query home sales data.
1. Cache and uncache temporary tables.
1. Partition and process data for optimized analytics.
1. Compare runtimes for various data states.


## Sources
- Most code was borrowed or inspired from class concepts taught in Module 22 of the June 2024 UMN Data Analytics Bootcamp course

- Chat GPT was used for review of structure in specific lines and for debugging
