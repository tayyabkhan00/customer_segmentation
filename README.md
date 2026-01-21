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

- Data Loading (CSV)
- Exploratory Data Analysis (EDA)
- Feature Scaling
- K-Means Clustering (Before PCA)
- PCA Transformation
- K-Means Clustering (After PCA)
- Cluster Visualization
- Business Interpretation
- Streamlit Deployment

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
- Makes visualization easier (2D)<br>
✔ PCA preserved most of the variance while simplifying the feature space.

# 📌 Clustering Results

### After applying PCA and K-Means:
- Clusters are clearly separated
- Customer groups are easy to interpret
- Business insights become actionable<br>
### Example Customer Segments:
- High income – High spending (Premium customers)
- High income – Low spending
- Low income – High spending
- Budget-conscious customers
- Average spenders

# 🌐 Streamlit Application

An interactive Streamlit dashboard was built to:
- Visualize clusters dynamically
- Change number of clusters (K) using a slider
- Display PCA-based segmentation in real time

# ▶️ Run the App
streamlit run app.py

# 📁 Project Structure

```
customer_segmentation_project/
│
├── data/
│   └── mall_customers.csv
│
├── app.py                # Streamlit dashboard
├── segmentation.py       # ML logic & EDA
├── requirements.txt
└── README.md
```

# 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Streamlit

# 📄 requirements.txt

pandas<br>
numpy<br>
scikit-learn<br>
matplotlib<br>
seaborn<br>
streamlit

# 📌 Key Takeaways

- PCA significantly improves clustering visualization
- K-Means works best after proper scaling
- Unsupervised learning is powerful for business insights
- Visualization is critical for interpretability

# 👤 Author

Tayyab Khan<br>
BTech – AI & Data Science<br>
Aspiring Data Scientist / ML Engineer 

### ⭐ If you like this project, don’t forget to star the repository!
