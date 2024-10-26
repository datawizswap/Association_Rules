# Association Rule Mining for Retail Store Sales Optimization

## Project Overview
This project aims to improve a retail store’s sales strategy by identifying patterns in customer purchase behavior using Association Rule Mining. By analyzing transaction data, association rules between products are derived to enhance product placement, cross-selling opportunities, and profitability.

## Problem Statement
Sales in the client’s retail store have lagged behind competitors. Using customer transaction data, the goal is to identify relationships between products frequently bought together, allowing the client to optimize shelf arrangements and develop strategies to boost sales.

## Project Goals
#### Business Objective: Increase cross-selling by 15–20%.
#### Technical Objective: Efficiently identify associations in customer purchases.
#### Economic Objective: Increase profits by 15% with effective cross-selling and customer insights.

## CRISP-ML(Q) Phases
#### - Business and Data Understanding
#### - Data Preparation
#### - Model Building
#### - Model Evaluation
#### - Deployment
#### - Monitoring and Maintenance

## Data Collection
The dataset consists of 9,835 transactions recorded over a month, capturing daily purchases in a CSV format.

## Methodology
#### Data Preprocessing: Transactions are processed into a suitable format using Python lists and TransactionEncoder.
#### Frequent Itemsets Mining: Using the Apriori algorithm to find itemsets with minimum support.
#### Association Rule Mining: Extracting association rules with minimum confidence and lift thresholds.
#### Redundancy Elimination: Filtering duplicate rules to retain only unique, actionable insights.

## Key Features
#### Itemset Analysis: Identifies popular itemsets in transactions.
#### Association Rule Mining: Finds association rules using metrics like lift, confidence, and support.
#### Visualization: Displays most frequent items and association rules using matplotlib.

## Technologies Used
#### Python: Data processing and mining
#### MLxtend: Apriori and association rule functionalities
#### Matplotlib: Data visualization

## Usage
#### Prepare transaction data in the CSV format.
#### Run the notebook or script to view:
#### Most popular items
#### Frequent itemsets and association rules
#### Visualizations of top association rules for strategy development
#### Sample Output
#### Most Popular Items: Bar chart of top 10 items.
#### Top Association Rules: Scatter plot showing support vs. confidence with color-coded lift.

## Future Enhancements
#### Automate data collection and association rule analysis for real-time insights.
#### Implement clustering to further segment customer buying patterns.
