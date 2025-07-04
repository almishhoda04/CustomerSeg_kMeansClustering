# 🛍️ Customer Segmentation with K-Means Clustering

## 📌 Objective
To perform unsupervised machine learning using **K-Means Clustering** for customer segmentation based on spending behavior and income levels.

## 📊 Dataset
- **Name:** Mall Customers Dataset  
- **Source:** [Kaggle - Customer Segmentation Tutorial](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Rows:** 200  
- **Columns:** 5  
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

✅ No missing or duplicate values.

## 📖 Task Workflow

### 1️⃣ Data Loading and Exploration
- Loaded dataset using Pandas
- Checked data shape, data types, and null values
- Visualized initial data distribution using scatter plots

### 2️⃣ Feature Selection
- Selected **Annual Income (k$)** and **Spending Score (1-100)** for clustering

### 3️⃣ Elbow Method to Find Optimal K
- Used Within-Cluster Sum of Squares (WCSS)
- Determined optimal number of clusters **K = 5**

### 4️⃣ Apply K-Means Clustering
- Initialized KMeans with `n_clusters=5`
- Fitted the model and predicted cluster labels
- Added cluster labels back to the original dataset

### 5️⃣ Cluster Visualization
- Visualized customer segments with color-coded scatter plot
- Highlighted cluster centroids

### 6️⃣ Clustering Evaluation
- Evaluated clustering performance using **Silhouette Score**

## 📈 Results

- **Optimal Clusters (K):** 5  
- **Silhouette Score:** 0.554

Visualized clear and distinct customer groups based on income and spending behavior.

## 📌 Conclusion

K-Means clustering successfully segmented mall customers into meaningful groups based on their annual income and spending score. This approach can assist businesses in targeted marketing, customer profiling, and personalized service strategies.
