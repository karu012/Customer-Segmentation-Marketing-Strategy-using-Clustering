1.Project Overview

The objective was to analyze customer data and identify distinct segments using unsupervised learning, which can help tailor marketing efforts more effectively and increase customer engagement and conversions.

2.Tech Stack

Language: Python

IDE: Jupyter Notebook

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

Algorithm: K-Means Clustering, Hierarchical Clustering

Dimensionality Reduction: PCA (Principal Component Analysis)

3.Dataset Attributes

The dataset includes customer information over 2 years of marketing campaigns and spending history:

Demographics: Age, Education, Marital Status, Income, etc.

Household: Kids at home, Teens at home

Purchases: Wine, Fruits, Meat, Fish, Sweet, Gold

Campaign Response: Number of accepted campaigns, complaints

Behavior: Recency, Date of enrollment

4.Key Steps Performed

4.1 Data Preprocessing

Removed null values and duplicates

Converted date columns and calculated customer age

Encoded categorical variables

Normalized numerical features for clustering

4.2 Exploratory Data Analysis (EDA)

Visualized customer behavior trends using:

Count plots

Box plots

Heatmaps (correlation)

Pairplots to understand feature distributions

4.3 Feature Engineering
Derived new features like age, total spending

Applied one-hot encoding for categorical variables

Standardized features before clustering

4.4 Dimensionality Reduction
Used PCA to reduce dimensionality and visualize customer clusters in 2D

4.5 Customer Segmentation
Applied K-Means Clustering to group customers

Evaluated optimal k using Elbow Method

Applied Agglomerative Hierarchical Clustering and visualized with dendrograms


5.Insights & Outcome
   
Identified distinct customer groups (e.g., high spenders vs low spenders, young families, etc.)

Delivered actionable insights to improve campaign targeting


6.Conclusion

This project demonstrates how clustering techniques can be used for intelligent customer segmentation and data-driven marketing strategy. The insights gained can help in creating personalized experiences and increasing customer satisfaction and revenue.


