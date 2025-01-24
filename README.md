# eCommerceTransactions
This repository contains an end-to-end analysis of eCommerce transaction data, including Exploratory Data Analysis (EDA), Lookalike Modeling, and Customer Segmentation (Clustering). The goal of this project is to derive insights into customer behavior, identify high-value customer segments, and create targeted marketing strategies using clustering and lookalike modeling techniques.

The project is divided into three main parts:

1. Exploratory Data Analysis (EDA)
Cleaned and pre-processed the eCommerce transaction dataset.
Analyzed the distribution of customer demographics, transaction frequency, total purchase amounts, etc.
Visualized patterns using plots such as histograms, box plots, and correlation heatmaps to understand the data.
2. Lookalike Modeling
Analyzed customer profiles and found the top 3 most similar customers for each based on transaction similarity.
Generated a "Lookalike.csv" file mapping customer IDs to their most similar counterparts, with similarity scores.
3. Customer Segmentation (Clustering)
Used the Gaussian Mixture Model (GMM) for clustering customers into segments based on their total transaction values.
Evaluated the clusters using the Davies-Bouldin Index to assess their quality.
Visualized the clusters using scatter plots and other techniques to provide insights into customer behavior.
Libraries Used
Pandas: Data manipulation and analysis.
Matplotlib/Seaborn: Visualization tools for plotting.
Sklearn: Machine learning library for clustering and evaluation metrics.
NumPy: Numerical computing.
Files
Customers.csv: Customer demographic and transactional data.
Transactions.csv: Transactional data for each customer.
Lookalike.csv: Customer lookalike mapping with similarity scores.
