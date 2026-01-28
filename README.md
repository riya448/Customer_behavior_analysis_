Customer Shopping Behavior Analysis

Overview
This end-to-end data analytics project examines 3,900 transactions to identify patterns in customer spending, demographics, and subscription behavior. The project bridges the gap between raw data and strategic decision-making by utilizing a full data stack—Python for data engineering, SQL for deep-dive analysis, and Power BI for executive-level visualization.

Dataset
The dataset consists of 3,900 rows and 18 columns focusing on retail consumer behavior.
  .Customer Demographics: Age, Gender, Location, and Subscription Status.
  .Purchase Details: Item Category, Purchase Amount, Size, and Color.
  .Behavioral Data: Review Ratings, Discount usage, and Frequency of Purchases.

Tools & Technologies
  .Python (Pandas/NumPy): Data cleaning, missing value imputation, and feature engineering.
  .SQL (PostgreSQL): Advanced querying for business metrics and customer segmentation.
  .Power BI: Interactive dashboarding and data storytelling.
  .Gamma: AI-powered presentation generation for stakeholder reporting.
  .PDF/Markdown: Technical documentation and project reporting.

Project Steps
  1.Data Cleaning (Python): Handled 37 missing values in "Review Rating" using median imputation     and standardized column names to snake_case.
  2.Feature Engineering: Created age_group bins and purchase_frequency_days for more granular        analysis.
  3.SQL Integration: Cleaned data was loaded into a PostgreSQL database to run complex queries       regarding revenue by gender and product popularity.
  4.Analysis: Segmented customers into New, Returning, and Loyal groups based on their purchase      history.
  5.Visualization: Designed a Power BI dashboard to track KPIs like average purchase amount and      sales by category.
  6.Presentation: Summarized findings into a professional PPT deck using Gamma to provide            actionable business recommendations.

Dashboard
The interactive Power BI dashboard provides a high-level view of:
  .Key Metrics: Total customers (3.9K), average purchase amount ($59.76), and average rating (3.75).
  .Customer Segments: Breakdown of subscribers (27%) vs. non-subscribers (73%).
  .Category Performance: Revenue and sales volume for Accessories, Clothing, Footwear, and          Outerwear.
  
Key Results & Insights
  .Top Revenue Driver: The "Young Adult" age group contributed the highest revenue at $62,143.
  .Customer Loyalty: The majority of the customer base (3,116) falls into the "Loyal" segment.
  .Gender Spend: Male customers accounted for $157,890 in revenue compared to $75,191 from          female customers.
  .Recommendation: Focus on "Discount-Dependent Products" like Hats and Sneakers, which have the    highest discount rates (up to 50%).

How to Run
  1.Python: Run cleaning_script.py to process the raw CSV and generate the cleaned dataset.
  2.SQL: Import the cleaned CSV into your PostgreSQL server and execute queries.sql to view          business insights.
  3.Power BI: Open the .pbix file to interact with the visual dashboard.
  4.Presentation: Access the project summary via the Gamma link provided in the reports/ folder.
