Pet Product Sales Analysis - Certification Project
Description:

This repository contains the code and visualizations used to analyze a pet product sales dataset for a certification project.

Data Validation

** data/clean_data.csv**

The original dataset contained 879 rows and 9 columns. The data cleaning process involved the following steps documented in the script data_cleaning.py:

Sales Column: Converted to a numeric data type by removing commas and dollar signs.
Pet Type: Rows containing pet types other than dogs, cats, fish, and birds were removed (46 rows).
Duplicates & Missing Values: Scripts checked for and confirmed no duplicate rows or missing values exist.
The cleaned dataset with 833 rows has the following characteristics:

Product Identifiers: 879 unique product IDs.
Product Categories: 11 categories.
Pet Sizes: 5 sizes.
Pet Types: 4 types (dog, cat, fish, bird).
Rating: 10-point scale.
Rebuy: Binary (1 or 0).
Data Discovery & Visualization

** visualizations/ (folder)**

This section utilizes various visualizations within the visualizations folder to answer the customer's questions in the project brief.

Single Variable Analysis:

Distribution of Ratings: A histogram or box plot visualizes the distribution of product ratings (e.g., rating_distribution.png). This reveals if there's a skew towards high or low ratings.
Pet Type Breakdown: A bar chart shows the proportions of sales within each pet type category (e.g., pet_type_breakdown.png), indicating which pet category generates the most sales.
Relationship Analysis:

Rating vs. Rebuy Rate: A scatter plot explores the relationship between product rating and the likelihood of a repeat purchase (e.g., rating_vs_rebuy.png). This might reveal if higher-rated products have a higher rebuy rate.
Answering Business Questions:

By analyzing the cleaned data and creating visualizations, we can answer the following business questions from the project brief (replace these with the specific questions from your project):

What are the most popular pet categories? (Bar chart of pet type breakdown)
Do customers tend to repurchase higher-rated products? (Scatter plot of rating vs. rebuy rate)
Further Exploration:

This repository provides a starting point for further analysis. You can explore additional questions by creating more visualizations and performing statistical tests.

Tools Used:

(Replace with the specific tools you used for analysis and visualization)

Programming Language (e.g., Python)
Data Analysis Library (e.g., pandas)
Visualization Library (e.g., matplotlib, seaborn)
