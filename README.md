# EDA-Cars-24-Web-Scraping
EDA Project
## Business Problem and Use Case Domain Understanding
#### Business Problem:

The used car market has a wide range of prices, availability, and car conditions that vary across cities.

The need is to analyze and aggregate this data for better decision-making,  such as price comparison, and identifying trends in car market.

#### Use Case Domain:

This analysis is focused on the Indian used car market. Understanding car prices, models, and other features can help businesses, such as car dealerships or customers, make informed decisions.

Here I  used data scraped from Cars24, a popular website in India for buying and selling used cars.

## Objective ofthe Project
### Main Objective:
The goal is to extract and analyze used car listings data from various cities in India to gain insights into car prices, conditions, and trends.

This can help dealerships optimize their pricing strategies and assist buyers in making well-informed decisions.

#### Specific Goals:
Scrape used car data (e.g., brand, model, price, mileage, etc.) from multiple cities.

Clean and preprocess the data for analysis.

Perform exploratory data analysis (EDA) to identify patterns and correlations.

## Exploratory Data Analysis - Using Python
### Data Cleaning Steps
 #### Missing Values:
        Identified and handled missing values in the dataset, particularly for driven kilometers.

#### Outliers:
         Detected outliers in prices (e.g., very high-priced cars) and corrected where necessary.

  #### Data Types:
Converted columns like price and mileage to appropriate numerical types for analysis.
Converted string-based numbers (with commas) to numeric types.

 #### Statistical imputations:
Mean for continuous variables like Driven_Km
Data Manipulation Steps       
Feature Engineering:
Converted the price units (Crore/lakh) to a unified scale (INR).

#### City Mapping:
Mapped city names to their respective locations for easier analysis.

## Conclusion (Key Findings Overall)
 #### Key Insights:

The age of a car plays a significant role in determining its price, with newer cars being priced higher.

There is a clear preference for certain car brands in the used car market, leading to higher prices for popular brands.

Fuel type has a noticeable effect on pricing, with electric cars generally priced higher.

Cities like Delhi and Mumbai show higher average prices due to demand.

Driven kilometers have a strong negative correlation with car prices, with higher mileage reducing the price.



