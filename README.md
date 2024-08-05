# Supermarket Customer Analysis

This repository contains the analysis of supermarket customer data, focusing on customer demographics, income, spending patterns, purchase behavior, and the effectiveness of promotional campaigns. The goal is to gain insights into customer behavior and identify opportunities for targeted marketing strategies.

## Introduction
This project is an exploration of customer data from a supermarket to understand various aspects of customer behavior. The analyses include correlations between age, income, and recency of purchases, segmentation of customers based on their spending habits, and the effectiveness of different sales channels and promotional strategies.

## Dataset
The dataset used in this project is `Supermarket_Clean.csv`, which includes customer demographic details, income, purchase behaviors, and response to promotional campaigns.

### Key Columns:
- `ID`: Unique identifier for each customer.
- `Year_Birth`: Year of birth of the customer.
- `Age`: Age of the customer.
- `Education`: Education level of the customer.
- `Marital_Status`: Marital status of the customer.
- `Income`: Annual income of the customer.
- `NumWebPurchases`: Number of purchases made through the website.
- `NumCatalogPurchases`: Number of purchases made through catalog.
- `NumStorePurchases`: Number of purchases made in-store.
- `totalpurchases`: Total number of purchases made by the customer.
- `totalacceptedcmp`: Total number of accepted campaigns by the customer.
- `Response`: Response to the most recent campaign.

## Analysis Overview
The analysis is divided into several sections, each focusing on different aspects of customer behavior:

1. **Customer Demographics**: Relationship between age and recency, and the impact of education level on recency.
2. **Customer Income and Spending**: Distribution of income among low-recency customers and correlation between income and total purchases.
3. **Purchase Behavior**: Frequency of purchases through different channels (web, catalog, store) and their impact on recency.
4. **Promotion Response**: Effectiveness of promotional campaigns and discounts in reducing recency.

## Insights
### Customer Demographics
- A weak positive correlation between age and recency was found, suggesting older customers may purchase less frequently.
- Education level impacts recency, with higher education levels associated with slightly higher recency.

### Customer Income and Spending
- Customers with low recency have a moderate income level.
- There is a strong positive correlation between income and total purchases, especially through catalogs and in-store.

### Purchase Behavior
- Website purchases are strongly correlated with higher recency.
- Store and catalog purchases are also strongly correlated with recency, indicating their importance in customer engagement.

### Promotion Response
- Customers who engage more with promotional campaigns tend to have higher recency, contrary to the expectation that promotions reduce recency.

## Technologies Used
- Python (Pandas, NumPy)
- Jupyter Notebook
