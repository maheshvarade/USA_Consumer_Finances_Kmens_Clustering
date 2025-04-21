# USA_Consumer_Finances_Kmens_Clustering
USA Consumer Finances Dataset
This repository contains the USA Consumer Finances dataset, which offers detailed financial and demographic information about individuals in the United States. It covers data on income, employment status, credit scores, loan usage, and more. Additionally, it includes information about small business owners, capturing key metrics like business income, number of employees, and loan usage. This dataset is ideal for analyzing the economic behavior, financial health, and needs of U.S. consumers and entrepreneurs.

Dataset Overview
Personal Financial Data: Includes income, employment status, loan data, credit scores, assets, liabilities, and net worth.

Small Business Owner Data: Provides business income, number of employees, and business-specific financial details.

Income Categories (INCCAT): The dataset includes income brackets (INCCAT), which are mapped to meaningful income ranges for better analysis.

Key Insights
Higher Income Correlation Among Business Owners: A significant majority of small business owners fall into the highest income bracket ("90-100"), indicating a strong correlation between business ownership and higher income levels.

Broader Distribution Among Non-Owners: Non-business owners are more evenly distributed across all income categories, with a tendency toward lower to middle income brackets.

Wide Range of Debt Levels: Debt levels are spread across individuals, even among those with lower housing values. This indicates that debt isn't always proportional to home equity.

Outliers in Debt and Housing Values: Extreme cases with very high debt or housing values are present. These outliers may skew averages and warrant separate analysis or filtering.

Entrepreneurship and Age: The majority of small business owners are between the ages of 45 and 70, suggesting that entrepreneurship is more common in mid-to-later career stages.

Fewer Young Owners: There are fewer business owners under 40, possibly due to limited capital or career establishment at younger ages.

Clustering and Analysis
Feature Variability: Financial features like ASSET, NETWORTH, and NFIN show high variance, indicating significant diversity among small business owners. These features are crucial for segmentation and predictive modeling.

Optimal Cluster Selection: Inertia decreases with increasing number of clusters, with an elbow point between 4 to 6 clusters, suggesting a good balance between model simplicity and fit. Silhouette scores validate the optimal cluster number (3 clusters), indicating clear separation between clusters.

Cluster Characteristics:

Cluster 1: Represents high-value businesses with large means across all financial features.

Cluster 0: Represents smaller or financially weaker businesses with lower average values.

Cluster 2: Represents businesses with moderate financial strength.

Principal Component Analysis (PCA)
Dimensionality Reduction: PCA was used to reduce high-dimensional financial data to two components (PC1 and PC2) for easier visualization.

Cluster Separation: The PCA scatter plot shows clear separation between the clusters, especially along PC1, confirming the validity of the KMeans clustering.

Features
Financial Data: Income, assets, net worth, liabilities, loan usage, credit scores.

Demographics: Age, employment status, education.

Small Business Data: Business income, number of employees, business debt.

Purpose & Usage
This dataset is ideal for:

Economic modeling and analysis of financial health in the U.S.

Understanding the needs and challenges of small business owners.

Exploring correlations between financial status and business ownership.

Building predictive models for business performance and financial segmentation.
