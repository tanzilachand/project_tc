# Project_tc

**Project_tc** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* Project Example Idea 4: Online Retail Transaction Analysis
Data source: https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset 







## Business Requirements
* Data analysis goals: Analyse online retail transaction data to understand customer behaviour, identify popular products, and optimise pricing and marketing strategies. Provide insights into customer behaviour, popular products, and pricing strategies to improve sales and marketing efforts.
Context
The "Online Retail Transaction" dataset contains information on customer transactions made through an online retail platform. It includes data on products purchased, quantities, transaction dates and times, prices, customer identifiers, and customer locations. This dataset can be used to analyse customer behaviour and preferences, identify popular products, and optimise pricing and marketing strategies.


## Hypothesis and how to validate?
* Hypothesis: Customers who purchase more frequently tend to spend more per transaction.
* Validation:   Perform a correlation analysis between purchase frequency and average transaction value. Use statistical tests to determine if the relationship is significant. Visualise the data using scatter plots to illustrate the relationship.      



## Project Plan

### Objectives
* Clean and preprocess the dataset for analysis.
* Identify sales trends over time.
* Understand customer purchasing behavior.
* Discover top-performing products and countries.
### Extract
* Extract data from the dataset using pandas.
### Transformation
* Clean the data by handling missing values and removing duplicates.
* Encode categorical variables and create new features such as total transaction value.
* Aggregate data to the desired level (e.g., daily, monthly) for analysis.
* Convert Date columns to proper datetime formats.
* Create Sales = Unit price * Quantity
### Load
Store and cleaned and transformed data in a suitable format (e.g., CSV, database) for analysis.

Build visualizations to communicate findings effectively.

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
The analysis of the online retail transaction dataset was conducted to derive insights into customer purchasing patterns, product performance, and sales trends. The primary goal was to understand how customers interact with the platform, identify popular products, and assess the impact of various factors on sales.
The analysis was carried out using Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly) and involved the following techniques:

1. ### Data Cleaning & Preprocessing

*   Removed missing values for critical fields (CustomerID, Country, InvoiceDate, UnitPrice, Quantity).
*   Corrected data types (converted dates to datetime objects).
*    Removed duplicate records.

2. ### Feature Engineering

*   Created Sales = UnitPrice × Quantity.
*   Extracted Month (full name) and Day (day name) from the transaction date.
*  Grouped and aggregated data for:
               * Sales per country
               * Sales per customer
               * Monthly and weekly sales trends



* Encoded categorical values where necessary for analysis.

3. ### Descriptive Statistics

* Calculated total revenue, average order value, and number of unique customers.
* Identified top-selling products and most frequent buyers.

4. ### Trend Analysis

* Monthly, weekly, and daily sales patterns visualized.
* Seasonal variations in revenue identified.

5. ### Customer Behavior Analysis
* Customer Purchase Frequency (how many times each customer made a purchase).
* Sales contribution per customer segment.
* Average spending per customer.

6.Product Analysis

* Top 10 products by quantity sold.
* Top 10 products by revenue.

7.Geographical Analysis

* Revenue contribution by country.
*Country-wise distribution of customers and purchases.

8. Data Visualization

Matplotlib: Line charts, bar charts, scatter plots for static analysis.

Seaborn: Statistical plots including boxplots, histograms, and heatmaps.

Plotly: Interactive bar charts, 

I used generative AI tools to brainstorm ideas for data visualizations and to optimize code snippets for data processing tasks. These tools helped me quickly iterate on design concepts and improve the efficiency of my code.





## Credits 

* Most the codes are adapted from LMS Code Institute (Learning Material). 
* While I have written the majority of the code myself, I have also referenced various online resources to help with specific challenges.
When I found code is not working or givig error then the I used Copilot to find the direct solution to the problem and adapted according to my own understanding. 




## Acknowledgements (optional)
* Thank the people who provided support through this project.
I Acknowledge the support of my mentor, who provided valuable feedback and guidance throughout the project. Their insights helped me refine my analysis and improve the overall quality of the work.