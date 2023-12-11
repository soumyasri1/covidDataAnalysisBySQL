# COVID-19 Data Exploration and Analysis with SQL README
  # Overview
This SQL script analyzes the COVID-19 dataset, aiming to provide insights into the global pandemic's trends. The dataset includes information about confirmed cases, deaths, recoveries, and various statistics over time.

  # Prerequisites
SQL Server installed
COVID database created
Data table named dbo.Data
  # Usage
Execute the SQL script in your SQL Server environment.
Ensure the COVID database is selected (USE COVID).
  # Script Sections
# 1. Checking and Handling Missing Values
Identifies and updates null values in critical columns.
# 2. Descriptive Statistics
Provides basic statistics, including the first 10 rows, total number of rows, number of months, and monthly summaries.
# 3. Central Tendency
Calculates mean (average), median, and mode for confirmed, deaths, and recovered cases.
# 4. Dispersion
Computes range, variance, and standard deviation for confirmed, deaths, and recovered cases.
# 5. Percentiles and Frequency
Examines top records and percentiles for confirmed, deaths, and recovered cases.
# 6. Correlation and Ranks
Determines the correlation between confirmed, deaths, and recovered cases.
Adds row numbers and ranks based on confirmed cases.
# 7. Linear Models
Computes linear regression to estimate deaths based on confirmed cases.
# 8. Result Interpretation
Provides insights into data distribution, central tendency, dispersion, and relationships between COVID-19 cases.
