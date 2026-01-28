# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases**[cite: 3]. [cite_start]The goal is to uncover insights into spending patterns, customer segments, and subscription behavior to guide strategic business decisions[cite: 4].

## Dataset
The dataset contains **3,900 rows and 18 columns**[cite: 6, 7].
* [cite_start]**Demographics:** Age, Gender, Location, and Subscription Status[cite: 9].
* [cite_start]**Purchase Details:** Item Purchased, Category, Amount, Season, Size, and Color[cite: 10].
* [cite_start]**Behavioral Data:** Review Ratings, Shipping Type, and Purchase Frequency[cite: 11].
* [cite_start]**Data Quality:** Handled 37 missing values in the Review Rating column[cite: 12].

## Tools & Technologies
* [cite_start]**Python (Pandas):** Data cleaning and exploratory data analysis[cite: 13, 15].
* [cite_start]**PostgreSQL:** Structured analysis to answer business-critical questions[cite: 26, 27].
* [cite_start]**Power BI:** Interactive dashboarding for visual insights[cite: 62, 63].
* **Gamma:** Presentation generation for stakeholder reporting.

## Project Steps
1.  [cite_start]**EDA & Cleaning:** Loaded data in Python, performed initial exploration, and handled missing values using category medians[cite: 15, 16, 19].
2.  [cite_start]**Feature Engineering:** Created `age_group` bins and standardized columns to snake_case[cite: 20, 22].
3.  [cite_start]**Database Integration:** Connected Python to **PostgreSQL** to load the cleaned data[cite: 25].
4.  [cite_start]**SQL Analysis:** Queried metrics such as revenue by gender, top-rated products, and shipping comparisons[cite: 28, 42, 44].
5.  [cite_start]**Visualization:** Built a Power BI dashboard showing that **27%** of customers are subscribers[cite: 77, 80].

## Results & Insights
* [cite_start]**Revenue by Gender:** Male customers generated **$157,890**, while female customers generated **$75,191**[cite: 34, 37].
* [cite_start]**Customer Segments:** Identified **3,116 Loyal customers**, 701 Returning, and 83 New customers[cite: 54].
* [cite_start]**Product Performance:** "Gloves" achieved the highest average rating of **3.86**[cite: 43].
* [cite_start]**Age Demographics:** The **Young Adult** group contributed the highest total revenue at **$62,143**[cite: 61].

## How to Run
1.  **Data Processing:** Run the Python script to clean the raw data and generate the SQL-ready file.
2.  **Database Setup:** Execute the SQL scripts in a PostgreSQL environment to recreate the analysis tables.
3.  **Dashboard:** Open the `.pbix` file in Power BI Desktop to view the interactive visualizations.
