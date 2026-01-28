# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases**. The goal is to uncover insights into spending patterns, customer segments, and subscription behavior to guide strategic business decisions.

## Dataset
The dataset contains **3,900 rows and 18 columns**.
* **Demographics:** Age, Gender, Location, and Subscription Status.
* **Purchase Details:** Item Purchased, Category, Amount, Season, Size, and Color.
* **Behavioral Data:** Review Ratings, Shipping Type, and Purchase Frequency.
* **Data Quality:** Handled 37 missing values in the Review Rating column.

## Tools & Technologies
* **Python (Pandas):** Data cleaning and exploratory data analysis.
* **PostgreSQL:** Structured analysis to answer business-critical questions.
* **Power BI:** Interactive dashboarding for visual insights.
* **Gamma:** Presentation generation for stakeholder reporting.

## Project Steps
1. **EDA & Cleaning:** Loaded data in Python, performed initial exploration, and handled missing values using category medians.
2. **Feature Engineering:** Created `age_group` bins and standardized columns to snake_case.
3. **Database Integration:** Connected Python to **PostgreSQL** to load the cleaned data.
4. **SQL Analysis:** Queried metrics such as revenue by gender, top-rated products, and shipping comparisons.
5. **Visualization:** Built a Power BI dashboard showing that **27%** of customers are subscribers.

## Results & Insights
* **Revenue by Gender:** Male customers generated **$157,890**, while female customers generated **$75,191**.
* **Customer Segments:** Identified **3,116 Loyal customers**, 701 Returning, and 83 New customers.
* **Product Performance:** "Gloves" achieved the highest average rating of **3.86**.
* **Age Demographics:** The **Young Adult** group contributed the highest total revenue at **$62,143**[cite: 61].

## How to Run
1.  **Data Processing:** Run the Python script to clean the raw data and generate the SQL-ready file.
2.  **Database Setup:** Execute the SQL scripts in a PostgreSQL environment to recreate the analysis tables.
3.  **Dashboard:** Open the `.pbix` file in Power BI Desktop to view the interactive visualizations.
