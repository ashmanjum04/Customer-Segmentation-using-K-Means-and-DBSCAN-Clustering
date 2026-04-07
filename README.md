# 📊 Customer Segmentation using K-Means and DBSCAN Clustering

## 📌 Problem Statement

The objective of this project is to group similar data points into clusters using unsupervised learning techniques, helping to identify hidden patterns in the data without predefined labels.

---

## 📊 Dataset

* Dataset used: **Customer / Unlabeled Dataset**
* Contains numerical features representing customer behavior (or similar attributes)

*(Note: Dataset does not contain target labels — suitable for clustering)*

---

## ⚙️ Approach

### 1. Data Preprocessing

* Handled missing values
* Scaled numerical features using **StandardScaler**
* Ensured all features contribute equally to distance calculations

---

### 2. Dimensionality Reduction

* Applied **PCA (Principal Component Analysis)**
* Reduced data to 2 dimensions for visualization

---

### 3. K-Means Clustering

* Applied **K-Means algorithm**
* Used **Elbow Method** to determine optimal number of clusters
* Assigned cluster labels to data points

---

### 4. DBSCAN Clustering

* Applied **DBSCAN (Density-Based Spatial Clustering)**
* Identified:

  * Core points
  * Border points
  * Noise (outliers)

---

### 5. Model Evaluation

* Used **Silhouette Score** to evaluate clustering performance

---

## 📈 Results

* **K-Means:**

  * Successfully grouped data into meaningful clusters

* **DBSCAN:**

  * Silhouette Score: **0.61** (excluding noise points)
  * Effectively detected outliers in the dataset

---

## 🔍 Key Insights

* K-Means works well for well-separated clusters
* DBSCAN is effective for detecting noise and irregular cluster shapes
* Scaling is essential for distance-based algorithms
* PCA helps visualize high-dimensional data

---

## 🚀 Future Improvements

* Try hierarchical clustering
* Optimize DBSCAN parameters (eps, min_samples)
* Use more complex datasets
* Apply clustering in real-world scenarios (customer segmentation, anomaly detection)

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📌 Conclusion

This project demonstrates how unsupervised learning techniques like K-Means and DBSCAN can be used to discover patterns in unlabeled data. It highlights the importance of preprocessing, scaling, and evaluation in clustering tasks.
