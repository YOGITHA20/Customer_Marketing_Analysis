# Customer Marketing Analysis

## Overview

This project analyzes customer data to understand customer spending
patterns, customer segments, income-spending relationships, and
marketing campaign responses.

The analysis was done using Python and focuses on turning customer-level
data into useful marketing insights.

## Dataset

The dataset contains 2,240 unique customer records.

The available information includes:

- Customer demographics
- Income
- Product purchases
- Purchase channels
- Campaign acceptance
- Complaints
- Customer response
- Customer date

## Data Cleaning

The dataset was cleaned before performing the analysis.

The main cleaning steps included:

- Handling missing income values
- Removing an invalid income value of `666666`
- Identifying unrealistic ages above 100
- Creating cleaned income and age fields
- Combining six product purchase columns to calculate total spending

## Analysis Performed

The analysis covered:

- Exploratory data analysis
- Customer spending distribution
- Customer segmentation
- Income vs spending relationship
- Marketing campaign response
- Customer behavior analysis

## Customer Spending

A `Total_Spending` metric was created using the six product purchase
columns.

The results were:

- Mean spending: 605.80
- Median spending: 396
- Maximum spending: 2,525

The spending distribution is right-skewed, meaning a smaller group of
customers accounts for much higher spending than the majority.

## Customer Segmentation

Customers were segmented based on their total spending.

| Segment | Customers | Percentage |
|---|---:|---:|
| Low | 1,246 | 55.6% |
| Medium | 392 | 17.5% |
| High | 356 | 15.9% |
| Very High | 246 | 11.0% |

The majority of customers fall into the Low Spending segment, while
the High and Very High segments represent a smaller group of customers
with greater spending potential.

## Income and Spending

The correlation between cleaned income and total spending was:

**0.79265**

This indicates a strong positive relationship between income and
customer spending in this dataset.

## Marketing Analysis

Campaign acceptance and customer response data were analyzed to
understand how different customer groups respond to marketing
campaigns.

The analysis can be used to identify customer groups that are more
likely to respond and distinguish them from less responsive groups.

## Key Takeaways

- Most customers belong to the Low Spending segment.
- A smaller group of High and Very High spenders contributes
  significantly to overall spending.
- Income has a strong positive relationship with customer spending.
- Customer segmentation can help target different groups with
  different marketing strategies.
- Campaign response data can be used to improve customer targeting.

## Project Workflow

Data Cleaning → Exploratory Analysis → Customer Segmentation →
Correlation Analysis → Marketing Analysis

## Skills

Python | Pandas | NumPy | Data Cleaning | Exploratory Data Analysis |
Customer Segmentation | Correlation Analysis | Marketing Analytics |
Data Visualization
