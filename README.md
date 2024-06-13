# Data Exploration README

## Overview
This SQL script explores the cleaned layoffs data to extract meaningful insights. The exploration includes calculating various statistics and aggregating data by different dimensions like industry, country, and date.

## Steps and Skills Used

### Data Aggregation:
- Aggregated data by industry, country, year, and month.
- Calculated total layoffs by different dimensions to identify trends and patterns.

### Window Functions:
- Used `ROW_NUMBER()` and `DENSE_RANK()` to rank companies by layoffs in different years.

### Common Table Expressions (CTEs):
- Utilized CTEs to create intermediate results for calculating rolling totals and ranking companies.

### Date Manipulation:
- Extracted year and month from date fields to perform time-series analysis.
