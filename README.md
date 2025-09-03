# BIT2053_Group_Final_Project
Final Project BIT2053 Fundamental of Modern Data 
# Retail Sales Performance Dashboard

## Executive Summary
This project our project plan for the BIT2053 Final Group Project. We will deeply analyze a real retail sales dataset to simulate a data-driven decision-making process. The project includes sourcing, cleaning, and preprocessing of the data using Python, and then designing an interactive Business Intelligence (BI) dashboard using Power BI. The final objective is to conclude solid insights on sales trends, product performance, and client profiles to provide actionable business recommendations. The project will demonstrate our understanding of the end-to-end data analysis life cycle and our ability to apply computational thinking to solve business problems.

## Problem Statement
In the competitive retail landscape, businesses often struggle to make sense of large volumes of transactional data. This project addresses three core business problems:
1.  **Identifying Sales Trends:** Understanding sales and quantity sold fluctuate over time (monthly/quarterly)
2.  **Evaluating Product Portfolio:** Determining Which product categories (Electronics, Clothing, Beauty) generate the highest revenue, and what are the best-selling products
3.  **Analyzing Customer and Geographic Distribution:** pinpointing the most valuable customer segments and regions to allocate marketing resources efficiently.

## Dataset Source
The dataset used for this analysis is the **"Retail Sales Data Dashboard"** sourced from Kaggle.

*   **Author:** Jose Miguel Terron
*   **Direct Link:** [https://www.kaggle.com/datasets/josemiguelterron/retail-sales-data-dashboard](https://www.kaggle.com/datasets/josemiguelterron/retail-sales-data-dashboard)
*   **Description:** The dataset contains 9,994 transactions with details on orders, customers, products, and financials (Sales, Profit).

## Methodology
Our analysis followed a structured data analytics lifecycle:
1.  **Data Understanding:** We first explored the dataset to understand its structure and variables.
2.  **Data Preparation:** Using Python Pandas, we cleaned the data by checking for duplicates, handling missing values, and converting data types. New features like `Order Month Year` were created for time-series analysis.
3.  **Data Analysis & Visualization:** The cleaned data was imported into Power BI. We built an interactive dashboard with key visualizations:
    *   Time-series line charts for sales and profit trends.
    *   Bar and treemap charts for product category analysis.
    *   Piechart 
4.  **Interpretation:** We derived insights from the visualizations to answer the business questions and form recommendations.

## Results
Our analysis successfully uncovered significant patterns in the data:
*   **Sales Trends:**
*   Peak Seasons: Sales peaked in May and September 2023, indicating strong seasonal demand.
*   High Value: The average transaction value was $456, suggesting successful premium pricing or upselling strategies.
*   **Product Performance:**
*   Revenue Leader: Electronics generated the highest revenue, indicating strong profitability.
*   Volume Leader: Clothing sold the most units, operating on a high-volume model.
*   Growth Opportunity: Beauty was the lowest-performing category in both sales and revenue, highlighting a  key area for improvement.
*   **Customer/Geography:**
*   Balanced Demographics: Spending was nearly equal between Female (51.1%) and Male (48.9%) customers.
*   High-Value Segment: Customers around age 37 (within the 34-43 cohort) were the highest-spending demographic.

## The Functioning of BI Dashboard
The dashboard is designed for interactivity and insight discovery:
*   **Filters:** Use the **Year** and **Region** slicers at the top to filter the entire dashboard dynamically.
*   **Trend Analysis:** The line charts at the top show monthly Sales and Profit. Hover over data points to see exact values.
*   **Product Drill-Down:** The bar chart shows profit by category. Click on a category (e.g., "Technology") to filter the treemap below to show its sub-categories.
*   **Geographic Insight:** The map highlights states based on profit. Darker shades indicate higher profit.
*   **Access the Dashboard:** [Click here to view the interactive dashboard](https://lookerstudio.google.com/u/0/reporting/f1f41b6f-3d24-4dbd-9d53-41e82dd6c1b3/page/p_4xx8myxvvd?s=iCFpXGjr68Y)




![Dashboard Screenshot](images/dashboard_screenshot.png) <!-- You need to upload a screenshot to a folder called 'images' in your repo and link it here -->

## Acknowledgement
We would like to extend our gratitude to:
*   Our lecturer, Sir Nazmirul Izzad Bin Nassir, for his guidance throughout this project.
*   Kaggle user [Jose Miguel Terron](https://www.kaggle.com/josemiguelterron) for providing a clean and well-structured dataset.
*   Our group members for their collaboration and hard work.
