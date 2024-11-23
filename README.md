# Analyzing Customer Behavior Using KMeans in Python

## Project Overview

Small online retailers often lack the technical expertise to implement data mining and customer-centric marketing strategies. This project provides a practical case study on using data mining techniques to enhance business intelligence for an online retailer. 

The goal is to help the retailer understand its customers better and enable effective marketing strategies based on insights gained from the data. Using the Recency, Frequency, and Monetary (RFM) model, customers are segmented into meaningful groups through KMeans clustering and decision tree induction. Key characteristics of each segment are identified, leading to actionable recommendations for customer-centric marketing.

---

## Resources Used

- **Dataset**: [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)  
- **Research Paper**: [Data Mining for Online Retail](https://link.springer.com/article/10.1057/dbm.2012.17)  

---

## Operations Performed

1. **Data Exploration**: Understanding the dataset structure and identifying initial patterns.
2. **Data Cleaning**: Addressing inconsistencies, handling missing data, and preparing data for analysis.
3. **Feature Engineering**: Creating RFM metrics to better analyze customer behavior.
4. **KMeans Clustering**: Grouping customers into clusters based on RFM features.
5. **Generating Insights**: Analyzing cluster characteristics to draw business implications.
6. **Handling Missing Data**: Identifying and addressing gaps in the dataset.

---

## Outputs from the Project

### **Frequency Analysis**
- **Recency**: Number of days since each customer made their last purchase.
- **Frequency**: Total number of purchases made by each customer.
- **Monetary**: Total spending contribution of each customer.

### **KMeans Clustering**
- **Purpose**: Unsupervised machine learning to detect patterns in customer behavior.
- **Outcome**: Customers were segmented into meaningful groups for better targeting.

---

## Goal

The primary goal is to enable the retailer to better understand their customers and implement targeted, data-driven marketing strategies.

---

## Modules Used

- **pandas**: For importing and manipulating the dataset.
- **matplotlib**: For visualizing data trends.
- **seaborn**: For enhanced data visualization.
- **scikit-learn**: For implementing machine learning algorithms like KMeans.
- **openpyxl**: For importing datasets in Excel format.

---
