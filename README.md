# Restaurent_Data_analysis_Project

* Project Overview

This project focuses on analyzing restaurant data using Python and Power BI to extract meaningful insights related to cuisines, ratings, pricing, online delivery, customer engagement, and restaurant chains.

The project combines data preprocessing and analysis in Python with interactive visualizations in Power BI to better understand restaurant trends and customer preferences.

* Objectives
Analyze the most popular cuisines
Compare city-wise restaurant ratings
Study restaurant price range distribution
Examine online delivery availability
Analyze relationship between votes and ratings
Identify major restaurant chains
Perform geographic analysis of restaurants

* Tools & Technologies Used
Python
Power BI
Pandas
Jupyter Notebook / Google Colab

* Project Structure
Restaurant_Data_Analysis_Project/
│
├── Dataset.csv
├── PowerBI_Dashboard.pbix
├── Python_Analysis.ipynb
├── Project_Report.pdf
└── README.md

 * Analyses Performed
1. Top Cuisines Analysis
Identified the most common cuisines
Visualized top cuisine categories
2. City-wise Rating Analysis
Compared average restaurant ratings across cities
3. Price Range Distribution
Analyzed restaurant distribution by pricing category
4. Online Delivery Analysis
Examined percentage of restaurants offering online delivery
5. Votes vs Rating Analysis
Studied relationship between customer votes and ratings
6. Cuisine Combination Analysis
Identified popular cuisine combinations
Compared ratings across combinations
7. Geographic Analysis
Visualized restaurant locations using maps
8. Restaurant Chains Analysis
Identified major restaurant chains
Compared outlet counts, ratings, and votes

 * Data Preprocessing

The following preprocessing steps were performed using Python:

Removed missing values
Cleaned column names
Handled inconsistent data
Converted data types

* Sample Code
import pandas as pd

df = pd.read_csv("Dataset.csv")

df = df.dropna()
df.columns = df.columns.str.strip()

* Power BI Dashboard

The Power BI dashboard includes:

Top cuisines visualization
City-wise rating comparison
Price range distribution
Online delivery analysis
Votes vs ratings scatter plot
Geographic map analysis
Restaurant chains analysis

 * Key Insights
A few cuisines dominate the restaurant market
Most restaurants fall in the mid-price range
Online delivery services are widely available
Some cities have higher average ratings
Restaurant chains have strong customer engagement
Votes and ratings show limited correlation

* How to Run the Project
Python Part
Install required libraries:
pip install pandas
Run the notebook:
jupyter notebook
Open:
Python_Analysis.ipynb
Power BI Part
Open:
PowerBI_Dashboard.pbix
Refresh dataset if needed
Explore dashboard visuals

* Conclusion

This project demonstrates how data analytics can be used to understand restaurant trends, customer preferences, and business performance using Python and Power BI.

