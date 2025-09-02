# BIT2053_Group_Final_Project
Final Project BIT2053 Fundamental of Modern Data 
# Retail Sales Performance Dashboard

## Executive Summary
This project analyzes a retail sales dataset to uncover key business insights regarding sales trends, product performance, and customer segmentation. Using Python for data preparation and Power BI for visualization, we developed an interactive dashboard to aid in strategic decision-making. Our analysis revealed critical findings such as strong Q4 seasonality, the high profitability of the Technology product category, and the dominance of the West region in sales. Based on these insights, we provide actionable recommendations to increase overall profitability by 15%.

## Problem Statement
In the competitive retail landscape, businesses often struggle to make sense of large volumes of transactional data. This project addresses three core business problems:
1.  **Identifying Sales Trends:** Understanding seasonal patterns to improve inventory planning and marketing campaigns.
2.  **Evaluating Product Portfolio:** Determining which product categories and sub-categories are most profitable to optimize assortment and pricing strategies.
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
    *   A map visualization for geographic analysis.
    *   Slicers for interactive filtering by year and region.
4.  **Interpretation:** We derived insights from the visualizations to answer the business questions and form recommendations.

## Results
Our analysis successfully uncovered significant patterns in the data:
*   **Sales Trends:** A consistent and significant peak in sales and profit occurs in Q4 (November and December) due to the holiday season.
*   **Product Performance:** The Technology category is the most profitable, while Furniture has high sales volume but lower margins. High discounts (>20%) were found to negatively impact profit.
*   **Customer/Geography:** The West region is the most profitable. The Consumer segment generates the most sales, while the Corporate segment has a high average order value.

## The Functioning of BI Dashboard
The dashboard is designed for interactivity and insight discovery:
*   **Filters:** Use the **Year** and **Region** slicers at the top to filter the entire dashboard dynamically.
*   **Trend Analysis:** The line charts at the top show monthly Sales and Profit. Hover over data points to see exact values.
*   **Product Drill-Down:** The bar chart shows profit by category. Click on a category (e.g., "Technology") to filter the treemap below to show its sub-categories.
*   **Geographic Insight:** The map highlights states based on profit. Darker shades indicate higher profit.
*   **Access the Dashboard:** [Click here to view the interactive dashboard]([https://lookerstudio.google.com/reporting/your_dashboard_lin](https://lookerstudio.google.com/s/iCFpXGjr68Y)


![Dashboard Screenshot](images/dashboard_screenshot.png) <!-- You need to upload a screenshot to a folder called 'images' in your repo and link it here -->

## Acknowledgement
We would like to extend our gratitude to:
*   Our lecturer, Sir Nazmirul Izzad Bin Nassir, for his guidance throughout this project.
*   Kaggle user [Jose Miguel Terron](https://www.kaggle.com/josemiguelterron) for providing a clean and well-structured dataset.
*   Our group members for their collaboration and hard work.
