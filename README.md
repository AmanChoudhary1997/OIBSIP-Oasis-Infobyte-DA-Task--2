# Customer Segmentation Analysis

## Project Overview
This project aims to perform **Customer Segmentation Analysis** for an e-commerce company. By analyzing customer behavior and purchase patterns, the goal is to group customers into distinct segments. The insights derived from this analysis can help the business develop targeted marketing strategies, improve customer satisfaction, and optimize overall business operations.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Objectives](#key-objectives)
- [Key Insights](#key-insights)
- [Libraries Used](#libraries-used)
- [Results](#results)
- [Recommendations](#recommendations)

---

## Dataset

The dataset used for this analysis contains the following features:

- **Customer ID**: Unique identifier for each customer.
- **Income**: Annual income of the customer.
- **MntTotal**: Total amount spent by the customer across all product categories.
- **Kidhome**: Number of children in the household.
- **Teenhome**: Number of teenagers in the household.
- **AcceptedCmpOverall**: Total number of promotional campaigns accepted by the customer.
- **Product Categories**: Spending on product categories such as wine, meat, fish, gold, etc.

---

## Key Objectives

1. **Data Exploration and Cleaning**: Load the dataset and handle any missing or inconsistent values.
2. **Descriptive Statistics**: Calculate important statistics, such as total spending, average income, and campaign engagement rates.
3. **Customer Segmentation**: Use clustering algorithms (e.g., K-Means) to group customers based on their purchasing behaviors.
4. **Visualization**: Create visualizations to highlight customer segments and product purchasing patterns.
5. **Insights and Recommendations**: Provide actionable insights based on customer segments to improve marketing strategies and business performance.

---

## Key Insights

1. **Cluster 0**: Low-income customers with moderate family sizes, low spending across all products, and low engagement in promotional campaigns.
2. **Cluster 1**: Lower-income families with more kids, low spending on premium products, and minimal engagement in campaigns.
3. **Cluster 2**: High-income customers with low family sizes, high spending on premium products, and strong engagement with promotions.
4. **Cluster 3**: High-income customers with moderate family sizes, high spending across multiple product categories, and high engagement in promotional offers.

---

## Libraries Used

- **pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **scikit-learn**: For implementing clustering algorithms.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For statistical visualizations.
- **warnings**: To suppress warnings during code execution.

---

## Results

The analysis produced the following key results:

1. **Customer Segments**: Customers were divided into 4 segments based on their income, family size, purchasing behavior, and campaign engagement.
2. **Top Spenders**: High-income segments (Cluster 2 and 3) contribute significantly to the company's revenue.
3. **Product Preferences**: Wine and meat were the most popular products among high spenders.
4. **Engagement**: Customers with high engagement in promotions also have higher overall spending.

---

## Recommendations

Based on the analysis, the following recommendations were made:

1. **Cluster 0**: Increase promotion and discount offerings on essential goods to encourage spending from low-income customers.
2. **Cluster 1**: Provide family-oriented product bundles at discounted prices to cater to larger, lower-income families.
3. **Cluster 2**: Offer personalized, premium product promotions for high-income customers who prefer luxury items.
4. **Cluster 3**: Strengthen loyalty programs to maintain high engagement with this highly valuable customer segment.

