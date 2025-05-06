# Customer Segmentation Using Clustering Algorithms

This project uses **KMeans clustering** to segment customers based on their **Age**, **Annual Income**, and **Spending Score**. The goal is to group customers into different segments that can help businesses target their marketing efforts more effectively. The project involves **data preprocessing**, **KMeans clustering**, **evaluation**, and **visualization**.

---

## 📝 Objective

To apply **KMeans clustering** and other data analysis techniques to segment customers into distinct groups based on their behavior. By analyzing customer data, businesses can tailor marketing campaigns to specific customer segments.

---

## 📂 Dataset

- **Source**: Synthetic dataset 
- **Features**:
  - `Age`: Customer's age
  - `AnnualIncome`: Customer's annual income
  - `SpendingScore`: Customer's spending behavior (score from 1 to 100)
- **Rows**: 200 customer records

---

## 🔧 Tools & Libraries

- **Python 3.x**
- **pandas**: Data manipulation
- **numpy**: Numerical operations
- **matplotlib**, **seaborn**: Data visualization
- **scikit-learn**: Machine learning (KMeans, StandardScaler)

---

## 🏗️ Project Workflow

1. **Data Collection**: A synthetic dataset representing customer data with features like age, income, and spending score is generated.
2. **Data Preprocessing**:
   - Handle missing values (filled with median values).
   - Feature scaling using **StandardScaler**.
3. **Clustering**:
   - **KMeans** algorithm is used for customer segmentation.
   - Optimal number of clusters is determined using the **Elbow Method**.
4. **Evaluation**:
   - Evaluate clustering results using the **Silhouette Score**.
5. **Visualization**:
   - Visualize the customer segments using **2D scatter plots** and **3D plots**.
6. **Interpretation**:
   - Analyze each cluster to derive insights, such as income and spending patterns for each group.

---

## 📊 Results

- **Optimal Clusters**: After applying the **Elbow Method**, the optimal number of clusters was found to be **5**.
- **Silhouette Score**: The **Silhouette Score** was calculated to evaluate how well the clusters are formed.
- **Customer Segments**:
  - Segment 1: Young, high income, high spending score
  - Segment 2: Older, low income, low spending score
  - Other segments show different income and spending behaviors.

---

## 📈 Visualizations

- **Elbow Method Plot**: Visual representation of the inertia to determine the optimal number of clusters.
- **2D Scatter Plot**: Customer segments visualized by **Age** and **Annual Income**.
- **3D Scatter Plot**: Segments visualized using **Principal Component Analysis (PCA)**.
- **Cluster Analysis**: Visual insights into each cluster’s characteristics based on **Age**, **Annual Income**, and **Spending Score**.

---

## 🚀 Future Improvements

- Experiment with **DBSCAN** or **Agglomerative Clustering** for potentially better segmentation.
- Apply advanced **Dimensionality Reduction** techniques for better visualizations.
- Handle class imbalances and missing data more efficiently using different imputation strategies.


