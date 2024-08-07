# Credit Card Case Study

## Overview

This case study focuses on the analytics of the credit card industry, specifically aimed at understanding customer behavior, personalizing offerings, identifying trends, uncovering suspicious activities, and reducing chargebacks. The data provided is used to answer various business-related questions and create valuable insights for PSPD Bank, which operates globally.

## Data Description

The dataset consists of the following sheets:
- **Customer Acquisition**: Details of customers at the time of card issuance.
- **Spend (Transaction Data)**: Credit card spending data for each customer.
- **Repayment**: Payment data done by customers.

## Business Problem

To make informed decisions in the credit card industry, effective data analysis and modeling are required. Mr. Jim Watson, CEO of PSPD Bank, is interested in evaluating bankruptcy, fraud, collections, customer requests, and proactive service offers. The data analysis will help address these areas.

## Problem Statements and Tasks

### 1. Data Cleaning

- **a.** For ages less than 18, replace the value with the mean of age values.
- **b.** For spend amounts exceeding the customer’s limit, replace with 50% of the customer’s limit.
- **c.** For repayment amounts exceeding the limit, replace the repayment with the limit.

### 2. Data Summarization

- **a.** Determine the number of distinct customers.
- **b.** Determine the number of distinct categories.
- **c.** Calculate the average monthly spend by customers.
- **d.** Calculate the average monthly repayment by customers.
- **e.** Compute the monthly profit for the bank using a monthly interest rate of 2.9%. Profit is defined as interest earned on the Monthly Profit. Monthly Profit = Monthly Repayment – Monthly Spend. Interest is earned only on positive profits.
- **f.** Identify the top 5 product types.
- **g.** Find the city with the maximum spend.
- **h.** Determine which age group spends the most money.
- **i.** Identify the top 10 customers in terms of repayment.

### 3. City-Wise Product Spend Analysis

- Calculate the city-wise spend on each product on a yearly basis.
- Include a graphical representation for this analysis.

### 4. Graphical Representations

- **a.** Monthly comparison of total spends, city-wise.
- **b.** Comparison of yearly spend on air tickets.
- **c.** Comparison of monthly spend for each product to identify any seasonal trends.

### 5. User-Defined Function

- Write a Python function to find the top 10 customers for each city in terms of repayment amount by different products and time periods (yearly or monthly). The function should allow users to specify the product (Gold/Silver/Platinum) and time period (yearly or monthly) and automatically perform the analysis.

## Setup and Dependencies

The case study is implemented using Python 3.7 with the following packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Make sure to have these packages installed. You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. **Load Data**: Import the CSV files into the Jupyter Notebook.
2. **Data Cleaning**: Execute the code for cleaning the dataset based on the specified rules.
3. **Data Summarization**: Run the code to generate summaries and answers for the business questions.
4. **Visualization**: Use the provided code to generate the required graphical representations.
5. **Function Implementation**: Implement and test the user-defined function to analyze top 10 customers.
