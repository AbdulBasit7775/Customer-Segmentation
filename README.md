# Customer-Segmentation
customer segmentation system utilizing K-Means clustering, providing actionable insights into customer behavior, preferences and demographics 


This customer analysis project utilizes Python, Pandas, Matplotlib and Seaborn libraries to extract insights from an online retail dataset. The project begins with data exploration, displaying dataset statistics, structure and initial rows.
Data cleaning involves removing canceled invoices, handling missing values and data type conversions. Filtering ensures valid invoice and stock codes. Data aggregation creates customer-level metrics: TotalSpent, NumberOfInvoices and LatestPurchaseDate.
Data visualization employs histograms, box plots and 3D scatter plots to illustrate TotalSpent, NumberOfInvoices and LastVisit distributions. Outlier detection identifies exceptional monetary and frequency patterns.
StandardScaler transforms data for KMeans clustering analysis. Elbow and silhouette methods determine optimal cluster count (k=4). Cluster assignment reveals customer segments.
Cluster interpretation:
Cluster 0 (Blue): "Retain" - High-value, regular customers requiring loyalty programs.
Cluster 1 (Orange): "Re-Engage" - Infrequent, lower-value customers needing targeted marketing.
Cluster 2 (Green): "Nurture" - Low-activity customers requiring relationship-building.
Cluster 3 (Red): "Reward" - Loyal, high-value customers deserving exclusive offers.
Visualizations include violin plots for cluster comparisons, cluster distribution and average feature values.
This comprehensive analysis enables targeted marketing strategies, enhancing customer engagement and retention.
