# Boat Market Analysis: Pricing, Segmentation & Time Series Insights
# Project Overview

This project is the final case study for Achievement 6 of the Data Analytics Immersion Program.
The goal is to perform an end-to-end exploratory and analytical study on boat listings data in order to understand pricing behavior, market segmentation, and temporal trends.
Using Python for data preprocessing and analysis, and Tableau for storytelling and visualization, the project demonstrates skills in:
 Data sourcing and cleaning
Exploratory data analysis(EDA)
Regression analysis
Unsupervised machine learning (k-means clustering)
Time series analysis
Dashboarding and data storytelling
The final insights are presented in an interactive Tableau storyboard.
# Research Questions
 How are boat prices distributed across the market?
Is there a linear relationship between boat size (length) and price?
Can boats be meaningfully segmented into market categories using clustering?
How do average boat prices vary geographically by country?
What trends and patterns exist in related time-series data?
# Data Sources
 Primary Dataset
Boat listings dataset containing:
 Price
 Boat type
 Length and width
 Manufacturer
 Location (country)
 Year and listing attributes

Source: Kaggle – public boat listings dataset
Additional Data
# Time Series Data:

# Crude oil and energy-related economic indicators sourced via Nasdaq Data Link (Quandl / FRED alternatives)

# Geographic Data:
Country-level location data used for choropleth mapping in Tableau
All datasets were cleaned and preprocessed prior to analysis. No forecasted values were used in the time series analysis.
# Analytical Approach
The project follows a structured workflow:
Data Cleaning & Preparation
Removal of missing and inconsistent values
Feature selection and scaling
Creation of derived variables (price bins, clusters)
Exploratory Data Analysis
Price distribution analysis
Relationship exploration between key numerical variables
Regression Analysis
Linear regression between boat length and price
Evaluation using model diagnostics and goodness-of-fit
Cluster Analysis
K-means clustering applied to standardized price and length variables
Identification of distinct market segments
Integration of cluster labels into the cleaned dataset
Time Series Analysis
Trend and seasonal decomposition
Stationarity testing using the Augmented Dickey-Fuller test
Differencing and autocorrelation analysis
Visualization & Storytelling
Interactive dashboards and story points built in Tableau
Focus on insights relevant to pricing, segmentation, and geography

# Link to the tableau: https://public.tableau.com/views/Ex6_7Dashboards/GlobalBoatMarket?:language=de-DE&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
