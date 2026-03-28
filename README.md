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

  
## Project Insights

- Premium localities have significantly higher average prices and price per square foot
- Ready-to-move properties generally cost more than under-construction properties
- RERA-approved properties tend to have a higher average price, indicating a trust premium
- Builder reputation plays a major role in property pricing
- Apartments usually have higher price per square foot compared to floors and plots
- Certain builders consistently charge higher rates than others
- Larger homes are not always more expensive per square foot
- Area and price show a positive relationship, but not perfectly linear

## Final Conclusion

This analysis highlights key factors influencing real estate pricing in Gurgaon.

Location, builder reputation, and regulatory approval (RERA) significantly impact property prices. While larger homes have higher total prices, they do not always offer higher value per square foot.

The insights from this project can help:
- Buyers choose better investment options
- Developers understand pricing strategies
- Investors identify high-value localities

Overall, data-driven analysis plays a crucial role in making informed real estate decisions.
