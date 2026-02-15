# Cooperative Distribution Analysis Using SQL

## Overview

This project presents an exploratory data analysis of a cooperative registry dataset using MySQL. The objective is to transform structured raw data into analytical insights through systematic data cleaning, feature engineering, aggregation, and ranking techniques.

The dataset consists of 100 cooperative entities containing cooperative names and address information.

## Objectives

The analysis aims to:

- Assess data quality and structural consistency
- Extract district-level information from address fields
- Classify cooperatives based on operational type
- Measure distribution and contribution percentages
- Identify geographic concentration patterns
- Detect duplicate entity records

## Dataset Structure

The dataset includes:

- Cooperative identifier (`no`)
- Cooperative name (`nama_koperasi`)
- Cooperative address (`alamat`)

The address field was transformed to derive district-level segmentation for spatial distribution analysis.

## Analytical Approach

The analytical workflow includes:

1. Data normalization using a dedicated SQL VIEW layer  
2. Feature engineering via string manipulation functions  
3. Category segmentation using conditional logic  
4. Aggregation and percentage distribution analysis  
5. District-level ranking using window functions  
6. Duplicate detection and structural validation  

The analysis focuses on descriptive exploration and structural insight extraction rather than predictive modeling.

## Key Insights

- Cooperative distribution shows measurable geographic concentration across districts.
- Consumer and Savings & Loans cooperatives represent the dominant operational categories.
- Window-based ranking highlights districts with the highest cooperative density.
- Data integrity validation confirms minimal structural inconsistencies within the dataset.

## Technologies Used

- MySQL
- MySQL Workbench
- Advanced SQL (Window Functions, Ranking, Aggregation, View Abstraction)

---

This project demonstrates structured SQL-based data exploration, transformation, and analytical segmentation within a relational database environment.
