# 🛍️ Customer Segmentation using PCA & K-Means
### (Unsupervised Learning | EDA | Visualization | Streamlit Deployment)

# 📌 Project Overview

This project applies unsupervised machine learning techniques to segment customers based on their demographic and spending behavior.<br>
Using PCA (Principal Component Analysis) and K-Means clustering, customers are grouped into meaningful segments that can help businesses design targeted marketing strategies.

The project also includes advanced data visualization using Seaborn and an interactive Streamlit dashboard.

# 🎯 Problem Statement

Businesses often struggle to understand customer behavior from raw data.<br>
The goal of this project is to:
- Discover hidden customer segments
- Reduce data complexity using PCA
- Visualize and interpret customer groups effectively

# 📂 Dataset Information

Dataset: Mall Customers Segmentation Dataset<br>
Size: ~200 records
Features:
| Column                 | Description                |
| ---------------------- | -------------------------- |
| CustomerID             | Unique customer identifier |
| Gender                 | Male / Female              |
| Age                    | Customer age               |
| Annual Income (k$)     | Yearly income              |
| Spending Score (1–100) | Customer spending behavior |

# 🧠 Machine Learning Concepts Used

- Unsupervised Learning
- K-Means Clustering
- PCA (Dimensionality Reduction)
- Feature Scaling (StandardScaler)
- Elbow Method
- Cluster Interpretation

# 🔁 Project Workflow

- 1.Data Loading (CSV)
- 2.Exploratory Data Analysis (EDA)
- 3.Feature Scaling
- 4.K-Means Clustering (Before PCA)
- 5.PCA Transformation
- 6.K-Means Clustering (After PCA)
- 7.Cluster Visualization
- 8.Business Interpretation
- 9.Streamlit Deployment

# 📊 Exploratory Data Analysis (EDA)

- Distribution plots (Income & Spending)
- Pair plots for feature relationships
- Gender vs Spending behavior
- Cluster scatter plots
EDA was performed using Seaborn and Matplotlib.

# 📉 Why PCA?

- Reduces dimensionality
- Removes multicollinearity
- Improves cluster separation
- Makes visualization easier (2D)
✔ PCA preserved most of the variance while simplifying the feature space.
