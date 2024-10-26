# Association Rule Mining for Book Retail Store Sales Optimization

## Project Overview
This project leverages transaction data from a book retail store to identify customer purchasing patterns. By applying association rule mining techniques, we aim to reveal relationships between books frequently bought together, providing insights for cross-selling and optimized book placements.

## Problem Statement
The client, a book retail store, seeks to improve sales by identifying associations between books in customer transactions. Analyzing transaction data can inform better book placement and promotional strategies, ultimately increasing revenue through cross-selling.

## Objectives
#### Business Objective: Maximize profits by understanding purchasing patterns and enhancing cross-selling.
#### Technical Objective: Efficiently mine association rules in transaction data to reveal high-confidence book pairings.
#### Economic Objective: Achieve at least a 15% increase in store profits by strategically applying insights.

## CRISP-ML(Q) Phases
#### Business and Data Understanding: Explore customer purchasing behaviors.
#### Data Preparation: Preprocess transaction data into an analyzable format.
#### Model Building: Use Apriori algorithm and association rule mining to detect frequent itemsets.
#### Model Evaluation: Assess rules based on metrics such as support, confidence, and lift.
#### Deployment: Implement insights to optimize book placements and cross-selling.
#### Monitoring and Maintenance: Regularly update rules based on new customer behavior patterns.

## Data Collection
#### Source: Daily transaction data from the store, capturing book purchases.
#### Size: 1,999 transactions over one month.

## Methodology
#### Preprocessing: Clean and structure transaction data with TransactionEncoder.
#### Frequent Itemset Mining: Identify book combinations with a minimum support threshold using the Apriori algorithm.
#### Association Rule Mining: Extract association rules with a minimum lift of 1 to find meaningful book pairings.
#### Redundancy Elimination: Filter redundant rules to focus on unique, high-value patterns.

## Key Features
#### Frequent Itemsets: Analyze book combinations based on frequency (support).
#### Association Rules: Identify relationships using support, confidence, and lift metrics.
#### Visualization: Display top itemsets and association rules with matplotlib.

## Technologies Used
#### Python: Data preprocessing and analysis
#### MLxtend: Apriori and association rule functionalities
#### Matplotlib: Visualizations

## Usage
#### Load the transaction dataset (book.csv) and preprocess it using TransactionEncoder.
#### Execute the Apriori algorithm to find frequent itemsets and association rules.
#### Visualize top frequent itemsets and rules.
#### Sample Output
#### Frequent Itemsets: Bar chart of the top 10 itemsets.
#### Association Rules: Scatter plot of rules with support and confidence metrics, color-coded by lift.

## Future Enhancements
#### Automate regular data collection and model updates for real-time insights.
#### Introduce clustering techniques to further understand customer segments.
