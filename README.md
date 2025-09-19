# UK House Price Analysis Project

Data Source: https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads

The dataset contains property transactions across England and Wales for the year 2018.


# Project Overview

The UK housing market is highly dynamic, influenced by economic trends, location, property types, and buyer demographics. This project explores property transaction data from 2018 to understand trends, price variations, and affordability across different property types and regions. The goal is to provide actionable insights for first-time buyers, investors, and policymakers.


# Key objectives:

   (1) Analyze historical housing price trends.
  
   (2) Compare affordability between property types (flats vs terraced houses).
  
   (3) Identify regional variations and patterns in prices and transaction counts.
  
   (4) Provide visualizations to highlight insights for data-driven decision-making.



# Data Pre-Processing

  (1) The dataset was pre-processed to handle missing values, clean inconsistent entries, and engineer new features, including:

  (2) price_band: categorical variable based on transaction price ranges.

  (3) affordability_score: metric to compare first-time buyer affordability.



# Data Cleaning and Feature Engineering

  (1) Missing Values:
  
   Columns with high missing values were dropped or imputed.

   Categorical variables were filled with mode, numeric variables with median.


  (2) Feature Engineering:
  
   Added price_band to categorize prices into low, mid, and high ranges.
   
   Calculated monthly median prices for trend analysis.
   
   Computed first-time buyer affordability by comparing average flat and terraced house prices with estimated income levels.



# Exploratory Data Analysis (EDA)

1. Price Analysis

   Median property price in 2018 was analyzed.
   
   Price distribution shows a right-skewed pattern with a few high-value outliers.
   
   Boxplots highlighted price variation across property types and tenure.

   Insights:
   
   Detached houses were the most expensive, followed by semi-detached, terraced, and flats.
    
   Leasehold properties tend to be cheaper than freehold ones, particularly for flats.



2. Regional Analysis

   Heatmaps displayed median property prices across counties.
   
   Scatter plots revealed districts with high transaction volumes but lower median prices.

  Insights:
  
  London and South East counties have the highest median prices.
  
  Northern counties show lower median prices but higher affordability.



3. Property Type Distribution

    Bar charts show that terraced houses and flats dominate the transaction counts.
    
    New-build properties make up a smaller fraction but show higher average prices.



4. Temporal Trends

    Line charts of monthly median prices indicate a steady upward trend in property prices through 2018.
    
    Seasonal peaks observed in spring and autumn.



5. Affordability Analysis

    Compared flats vs terraced houses for first-time buyers.
    
    Terraced houses were generally less affordable than flats in urban centers, but offer better space and value in suburban areas.



# Visualizations

  Line chart: Monthly median price trend.
  
  Heatmap: Median prices by county.
  
  Bar chart: Distribution of property types.
  
  Boxplot: Price by tenure and property type.
  
  Scatter plot: Price vs transaction count per district.

These visualizations provide an intuitive view of market trends, price variability, and transaction patterns.




# Key Insights

  Price Segmentation: Detached houses are high-value properties, while flats are entry-level options for first-time buyers.
  
  Regional Affordability: Northern counties and smaller towns are more affordable than London and South East.
  
  Market Dynamics: New-build properties tend to be priced higher but make up a small portion of total transactions.
  
  Temporal Patterns: Spring and autumn see higher transaction volumes, possibly linked to market seasonality.
  
  Buyer Guidance: Flats are generally more accessible for first-time buyers, but terraced houses may provide better long-term investment in certain districts.



# Conclusion

This project provides a comprehensive analysis of the UK housing market for 2018. By combining statistical analysis, feature engineering, and visualizations, we identified price trends, affordability gaps, and regional disparities. These insights can help first-time buyers, investors, and policymakers make informed decisions.



# Potential Next Steps:

Extend analysis to multiple years for long-term trend forecasting.

Incorporate demographic and income data for more precise affordability scoring.

Build an interactive dashboard for real-time analysis and insights.
