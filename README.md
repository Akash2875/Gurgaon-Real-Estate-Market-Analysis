# Gurgaon-Real-Estate-Market-Analysis
Performed exploratory data analysis on Gurgaon real estate data to derive actionable insights on pricing, locality comparison, and investment opportunities.

##  Project Objective

The objective of this project is to analyze residential real estate data from Gurgaon and extract meaningful insights that can help buyers, investors, and developers make informed decisions.

The analysis focuses on understanding pricing patterns, identifying premium localities, evaluating builder impact, and examining how property features influence prices.

##  Data Used

The dataset contains residential property listings from Gurgaon with the following key features:

- Price of the property
- Area (in square feet)
- BHK configuration
- Property type (Apartment, Floor, Plot)
- Locality
- Builder/Company name
- Property status (Ready-to-move / Under construction)
- RERA approval status
- Rate per square foot

The dataset was cleaned and preprocessed to ensure accurate analysis.

DATASET=<a href="https://github.com/Akash2875/Gurgaon-Real-Estate-Market-Analysis/blob/main/data.csv">Dataset</a>

CODE=<a href="https://github.com/Akash2875/Gurgaon-Real-Estate-Market-Analysis/blob/main/main.py">code <\a>

## Business Questions

The analysis aims to answer the following questions:

1. Which is the costliest flat in the dataset?
2. Which locality has the highest average price?
3. Which locality has the highest rate per square foot?
4. Do ready-to-move properties cost more than under-construction properties?
5. Do RERA-approved properties command a price premium?
6. How does area impact property price?
7. Which BHK configuration is the most expensive?
8. Which property type is the costliest?
9. Do certain builders consistently price higher?
10. Are larger homes more expensive per square foot?

## Process

The project was completed in the following steps:

### 1. Data Loading
- Loaded dataset using Pandas

### 2. Data Cleaning
- Standardized column names
- Removed duplicate records
- Converted price, area, and rate_per_sqft to numeric values
- Cleaned categorical columns (status, flat type, RERA approval)

### 3. Data Analysis
- Used groupby operations to analyze locality, builder, and property trends
- Identified maximum and average values for key metrics

### 4. Visualization
- Used Seaborn and Matplotlib for scatter plots:
  - Area vs Price
  - Area vs Price per Sqft

### 5. Insight Extraction
- Interpreted patterns and relationships to derive meaningful conclusions
