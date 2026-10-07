# Renewable Energy Data Analysis

## Overview

This project analyzes a renewable energy dataset using **Python, Pandas, and SQL**. The objective is to clean and transform raw energy data and perform exploratory analysis to understand renewable energy performance, investment patterns, funding sources, employment generation, and environmental impact.

## Tools & Technologies

- **Python**
- **Pandas**
- **SQL**
- **Jupyter Notebook**

## Project Workflow

### 1. Data Cleaning & Preparation

The raw dataset was processed using Python and Pandas before performing SQL analysis.

The data preparation process included:

- Checking data types and overall data quality
- Identifying missing and duplicate values
- Cleaning and formatting numerical features
- Mapping categorical values into meaningful labels
- Standardizing features for further analysis
- Exporting the cleaned dataset for SQL-based analysis

### 2. SQL Analysis

SQL queries were used to explore and compare different renewable energy types across several business and performance metrics.

The analysis focused on:

- Installed capacity across renewable energy types
- Total energy production
- Energy production-to-consumption ratios
- Storage efficiency
- Funding sources and renewable energy installations
- Job creation across different funding sources
- Initial investments and financial incentives
- Greenhouse gas (GHG) emission reduction
- Air pollution reduction

## Key Analysis Questions

The project explores questions such as:

1. Which renewable energy type has the highest installed capacity?
2. Which energy type produces the most energy?
3. Which energy types have the highest production-to-consumption ratio?
4. Which funding sources are associated with the highest job creation?
5. How are renewable energy installations distributed across funding sources?
6. Which energy types receive the highest investment and financial incentives?
7. How do different renewable energy types compare in terms of GHG emission and air-pollution reduction?
8. Which renewable energy types have the highest average storage efficiency?

SQL Techniques Used

The analysis makes use of SQL concepts including:

SELECT
GROUP BY
ORDER BY
Aggregate functions such as SUM(), AVG(), and COUNT()

Calculated ratios
Multi-column grouping

Repository Structure

Renewable-Energy-Data-Analysis/
│
├── green energy data extract and clean.ipynb
├── green_energy-analysis_sql.sql
└── README.md

Objective
The project demonstrates an end-to-end analytical workflow — from data extraction and cleaning using Python/Pandas to exploratory analysis using SQL — to derive meaningful insights from renewable energy data.

Skills Demonstrated
Python, Pandas, SQL, Data Cleaning, Data Transformation, Exploratory Data Analysis, Data Aggregation
