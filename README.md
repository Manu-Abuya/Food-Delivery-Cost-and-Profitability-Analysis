# Food Delivery Cost and Profitability Analysis

## Overview
The Food Delivery Cost and Profitability Analysis project aims to understand and optimize the financial dynamics of a food delivery operation. By examining various costs associated with delivering food orders and juxtaposing these costs against the revenue generated, the project provides insights into the profitability of the service on a per-order basis. The goal is to identify areas where the service can reduce costs, increase revenue, and implement pricing or commission strategies that enhance profitability.

## Introduction
This project involves the following steps: 
1. Gathering comprehensive data related to food delivery operations.
2. Cleaning and preparing the dataset.
3. Extracting relevant features impacting cost and profitability.
4. Breaking down costs and revenue for each order.
5. Calculating profit and analyzing profitability.
6. Developing strategic recommendations to enhance profitability.
7. Simulating the financial impact of proposed changes.

## Analysis Process
1. Data Preparation:
   - Convert date and time columns to datetime format.
   - Extract numeric values from the 'Discounts and Offers' column.
   - Ensure all monetary values are in a suitable format for calculations.
  
2. Cost and Profitability Calculation:
   - Calculate total costs for each order (delivery fee, payment processing fee, discount amount).
   - Calculate revenue from commission fees.
   - Determine profit by subtracting total costs from revenue.

3. Visualization:
   - Histogram of profits per order.
   - Pie chart of total cost proportions.
   - Bar chart comparing total revenue, costs, and profit.
   - KDE plots comparing actual and simulated profitability.
  
4. Strategic Recommendations:
   - Analyze profitable orders to find a "sweet spot" for commission and discount percentages.
   - Simulate profitability with recommended discounts and commissions.

## Results
The analysis revealed that the current commission rates, delivery fees, and discount strategies might not be sustainable for profitability. Recommendations include adjusting commission rates closer to 30% and reducing discounts to around 6%. These changes could shift profitability towards a higher proportion of profitable orders.


