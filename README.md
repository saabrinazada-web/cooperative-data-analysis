# Cooperative Distribution Analysis Using SQL

## Overview

This project presents an exploratory data analysis of a cooperative registry dataset using MySQL. The objective is to transform raw structured data into analytical insights through systematic data cleaning, feature engineering, aggregation, and ranking techniques.

The dataset consists of 100 cooperative entities containing cooperative names and address information.

## Objectives

The analysis aims to:

- Evaluate data quality and structural consistency
- Extract district-level information from unstructured address fields
- Classify cooperatives based on operational type
- Measure category distribution and contribution percentages
- Identify geographic concentration patterns
- Detect duplicate entity records

## Dataset

The dataset includes:

- Cooperative identifier (no)
- Cooperative name
- Cooperative address

The address field was transformed to derive district-level grouping for spatial distribution analysis.

## Methodology

The analytical workflow included:

1. Data cleaning and normalization using a dedicated SQL VIEW layer  
2. Feature engineering through string manipulation functions  
3. Aggregation and segmentation by cooperative category  
4. Window functions for ranking and contribution analysis  
5. Data integrity validation through duplicate detection  

The analysis focuses on structural exploration and descriptive insights rather than predictive modeling.

## Key Insights

- Cooperative distribution shows geographic concentration in specific districts.
- Consumer and Savings & Loans cooperatives represent the dominant operational categories.
- Window-based ranking highlights districts with the highest cooperative density.
- Data integrity checks confirm minimal structural anomalies within the dataset.

## Tools and Technologies

- MySQL
- MySQL Workbench
- Advanced SQL (CTE, Window Functions, Aggregation, Ranking)

---

This project demonstrates intermediate-level SQL proficiency in data transformation, segmentation, and analytical exploration within a relational database environment.
