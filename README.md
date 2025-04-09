# Mall Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using the **K-Means clustering algorithm** on the *Mall Customers* dataset. The goal is to categorize customers into distinct groups based on their shopping behavior, which can help businesses better understand and target their customer base.

## 📊 Dataset

**File:** `Mall_Customers.csv`  
**Attributes:**

- `CustomerID`: Unique ID for each customer  
- `Gender`: Customer's gender  
- `Age`: Age of the customer  
- `Annual Income (k$)`: Annual income in thousands of dollars  
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior  

## 🔍 Objective

Segment customers into different groups using **unsupervised machine learning** (K-Means clustering) to identify patterns in purchasing behavior.

## ⚙️ Methodology

1. **Data Preprocessing**
   - Loaded the dataset using pandas
   - Performed basic data exploration
   - Selected features: `Annual Income (k$)` and `Spending Score (1-100)`

2. **Finding Optimal Clusters**
   - Used the **Elbow Method** to find the optimal number of clusters (`k`)
   - Visualized the Within-Cluster Sum of Squares (WCSS)

3. **K-Means Clustering**
   - Applied `KMeans` from `sklearn.cluster`
   - Trained model with optimal `k`
   - Predicted cluster labels for all customers

4. **Visualization**
   - Used `matplotlib` and `seaborn` to visualize:
     - The Elbow Curve
     - The resulting clusters with centroids
     - Distribution of clusters

## 📈 Results

- Identified **5 distinct customer segments** based on income and spending score
- Generated scatter plots to illustrate each cluster
- Useful insights for marketing teams to personalize strategies for different customer groups

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (KMeans)

