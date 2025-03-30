Project Title: Coffee Sales Dashboard using Power BI
Objective:
The goal of this project was to analyze coffee sales data to gain insights into sales trends, order sizes, and customer behavior. The dashboard provides a comprehensive view of sales metrics and helps stakeholders make data-driven decisions.

Data Preprocessing:
Transaction Date Format:

Changed the transaction date format to ensure uniformity and easy time-based analysis.
Dropped Transaction Time:

Removed unnecessary time data to reduce noise and focus on date-based analysis.
Condition Column and Splitting Techniques:

Used condition columns to derive meaningful categories from raw data.
Applied splitting techniques to extract order sizes from product names, ensuring accurate size categorization.
Flash Fill Technique:

Filled null values efficiently using Flash Fill, which automatically detected patterns and completed the data.
Replace Value Technique:

Removed size information from product names to keep them consistent and concise.
Custom Column for Total Bill Calculation:

Created a calculated column to compute the total bill for each transaction, enhancing revenue analysis.
Data Transformation and Calculations:
DAX for Time Categorization:

Used DAX functions to classify the transaction time into four categories:
Morning
Afternoon
Evening
Night
This classification provided insights into peak business hours.
Role-Level Security (RLS):

Implemented RLS to restrict data visibility based on store locations.
Ensured that users could only view data related to their specific store, enhancing data security and relevance.
Dashboard Features:
Sales Analysis:

Visualizations for revenue, average bill size, and number of transactions.
Trend analysis to identify growth patterns over time.
Time-Based Insights:

Heatmaps and bar charts to identify peak sales hours and customer behavior across different times of the day.
Product Performance:

Analysis of the most popular coffee types and their sizes.
Revenue contribution of different products.
Geographical Insights:

Store-wise performance breakdown to compare sales across locations.
Key Learnings and Challenges:
Data Cleaning and Preprocessing:

Handling inconsistent date formats and null values efficiently.
Complex Calculations:

Creating custom columns and DAX measures to accurately categorize time and calculate the total bill.
Implementing RLS:

Configuring dynamic security rules to restrict data visibility based on user roles.
Impact and Benefits:
Enabled decision-makers to track sales performance and identify high-demand products.
Helped store managers optimize staff scheduling by identifying peak business hours.
Improved data security and relevance through Role-Level Security (RLS).
