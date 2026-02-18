# Assignment 06 - Real Estate Data Cleaning and Preparation

## Overview
This assignment focuses on data cleaning, preprocessing, and analysis using Pandas.  
The dataset represents real estate property details.

---

## Dataset: Real Estate Dataset

### Columns:
- Property_ID
- Location
- Price
- Bedrooms
- Bathrooms
- Area_sqft
- Year_Built

---

## Task 1: Data Exploration

1. Load the dataset using Pandas.
2. Display the first 5 rows.
3. Check dataset shape.
4. Display column names.
5. Check data types.
6. Identify missing values in each column.

---

## Task 2: Data Cleaning

1. Fill missing "Price" values using median.
2. Fill missing "Bedrooms" using mode.
3. Drop rows where "Area_sqft" is missing.
4. Remove duplicate records.
5. Convert "Year_Built" column to integer type (if needed).

---

## Task 3: Data Transformation

1. Create a new column "Price_per_sqft".
2. Create a new column "Property_Age" using current year.
3. Categorize properties:
   - Expensive → Price > 1,000,000
   - Affordable → Price ≤ 1,000,000

---

## Task 4: Data Analysis

1. Calculate average price by location.
2. Find location with highest average price.
3. Calculate average property size by location.
4. Identify top 5 most expensive properties.
5. Sort dataset by price (descending).

---

## Task 5: Filtering & Insights

1. Filter properties with more than 3 bedrooms.
2. Filter properties built after 2015.
3. Find properties with area > 2000 sqft.
4. Generate summary statistics.
5. Provide 3 business insights based on the dataset.

