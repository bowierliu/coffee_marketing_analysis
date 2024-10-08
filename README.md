# Coffee Shop Sales and Customer Segmentation Analysis

## Project Motivation

This project explores the weekly sales data of a coffee shop with the goal of uncovering patterns in customer purchasing behaviors and revenue fluctuations. The analysis aims to segment customers based on their spending habits and visit frequency, allowing for personalized marketing strategies to improve customer engagement and satisfaction. The data-driven insights generated from this project are intended to help the coffee shop optimize its inventory management, refine promotional efforts, and ultimately increase profitability.

## Project Overview

The project utilizes advanced data analytics and clustering techniques to identify key insights from the coffee shop's sales data. The primary objectives include:

1. **Sales and Revenue Analysis**: Understanding item pricing, category performance, and weekly revenue fluctuations.
2. **Customer Segmentation**: Grouping customers based on their transaction count and total spending to inform targeted marketing strategies.

The following key tasks were completed as part of this project:
- **Data Merging**: Combined weekly sales data with item information to create a comprehensive dataset.
- **Visualization**: Created bar charts, pie charts, and line charts to visualize item pricing, category performance, and weekly sales trends.
- **Clustering Analysis**: Performed K-means clustering to segment customers into three distinct groups: Low-Spending Occasional Visitors, High-Spending Loyal Customers, and Moderate-Spend Regulars.
  
## Key Findings

### Sales Analysis
- **Item Pricing**: A bar chart was created to show the pricing distribution across different items, aiding in pricing strategy and inventory management.
- **Category Performance**: A pie chart showing the revenue breakdown by item category highlighted which product categories are the most profitable.
- **Weekly Revenue Trends**: A line chart visualized the fluctuations in daily revenue, helping identify patterns and periods of high and low sales.

### Customer Segmentation
- **Cluster 0 (Low-Spending Occasional Visitors)**: Customers in this group spent an average of $7.30 with around 1.58 transactions each. This segment requires more engagement to increase their visit frequency and spending.
- **Cluster 1 (High-Spending Loyal Customers)**: This small but highly valuable segment spent around $81.66 with about 16.63 transactions. Retaining and enhancing the experience of these loyal customers is critical to the business.
- **Cluster 2 (Moderate-Spend Regulars)**: These customers spent about $48.72 and had 10 transactions on average. Strategies to increase their spend per visit or frequency could push them towards higher engagement.

## Libraries Used

- **Pandas**: For data manipulation and merging.
- **NumPy**: For numerical calculations and distance computations during clustering.
- **Altair**: For data visualization, including bar charts, pie charts, and line charts.
- **Scikit-learn**: For implementing the K-means clustering algorithm.

## Data

The dataset consists of two key sources:
1. **Sales Data**: Contains order details such as order ID, item ID, quantity, customer name, and whether the order was for dine-in or takeout.
2. **Item Data**: Provides details about each item's name, category, size, and price.

These datasets were merged to create a unified view of the coffee shop's sales and customer purchasing behavior.
