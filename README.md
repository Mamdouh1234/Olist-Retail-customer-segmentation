# Olist-Retail-customer-segmentation
A Machine Learning Unsupervised task for clustering customers at Olist store

## Overview
This project focuses on solving Olist Retail's challenge of optimizing operations and enhancing customer experiences through customer segmentation. By leveraging the Olist dataset from Kaggle, advanced clustering techniques like K-means were applied to identify customer groups based on purchasing behaviors, demographics, and order data. These insights aim to empower Olist Retail to design targeted marketing strategies, improve product recommendations, and foster customer loyalty in the competitive e-commerce landscape.

## Business Understanding
Problem Statement:
Olist Retail connects Brazilian retailers with customers across the country but struggles with a lack of actionable insights into customer preferences and behaviors. This has hindered its ability to:

Boost sales and customer retention.
Enhance personalized customer experiences.
Allocate resources efficiently.

Goal:To implement customer segmentation using K-means clustering to identify distinct customer groups and enable data-driven decision-making for marketing, product recommendations, and resource optimization.

## Data Understanding
The Brazilian E-Commerce Public Dataset by Olist (Andre Sionek · Leo Dabague · Francisco Magioli) is a complex data set consists of:
- 9 CSV files which are customers , geolocation , order_items , order_payments , order_reviews , orders , products , sellers and product_category_name
- more than 100K instance 
- 39 columns (after merging the 9 sets together)
for more information about the data set , visit it's [page](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data) on kaggle.

## Modeling
- The clustering algorithm used was Kmeans clustering , using 3 clusters , after being determined by the **elbow method** technique.
- The algorithm successfully classified the cutomers to three clusters which are:
  - High-value, satisfied customers
  - Mid-value, moderate satisfaction
  - Moderate-value, low satisfaction
 
## Key takeaways & Conclusion

The clustering analysis successfully segmented Olist Retail customers into three distinct groups with actionable insights:

- Cluster 0 (High-value, satisfied customers): Customers with the highest total spending and satisfaction, preferring fewer payment installments.

Action: Focus on retention strategies, such as loyalty programs and exclusive offers, while gathering feedback to maintain satisfaction.

- Cluster 1 (Mid-value, moderate satisfaction customers): Customers who prefer installment payments, with moderate satisfaction and spending.

Action: Target with installment-friendly campaigns and personalized incentives to boost spending and satisfaction.

- Cluster 2 (Moderate-value, low satisfaction customers): Customers with low satisfaction but moderate spending, indicating potential for improvement.

Action: Investigate and address reasons for low satisfaction (e.g., product or service issues), while providing targeted offers to enhance their experience and spending.

This segmentation enables Olist Retail to craft data-driven strategies for customer retention, satisfaction improvement, and revenue growth, ensuring optimized resource allocation in a competitive e-commerce landscape.
