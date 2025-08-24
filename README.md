# 🛍️ Customer Segmentation  

A Machine Learning project for clustering customers into meaningful groups based on their purchasing behavior and characteristics.  
This project applies **unsupervised learning algorithms** to identify distinct customer segments for better marketing and business decisions.  

---

## 🚀 Features  
- Data preprocessing and feature scaling  
- Apply multiple clustering algorithms:  
  - **K-Means**  
  - **Gaussian Mixture Model (GMM)**  
  - **DBSCAN**  
- Compare clustering results using visualization techniques  
- Identify customer groups with distinct characteristics  

---

## 📊 Dataset  
- Customer demographics and purchasing behavior  
- Features like **Age, Annual Income, Spending Score, etc.**  
- Preprocessed and scaled for clustering  

---

## 🧠 Models & Algorithms  

### 1️⃣ K-Means Clustering  
- Partitions customers into *k* groups.  
- Efficient and widely used for market segmentation.  

### 2️⃣ Gaussian Mixture Model (GMM)  
- A probabilistic model assuming data is generated from a mixture of several Gaussian distributions.  
- Provides soft clustering (probability-based assignment).  

### 3️⃣ DBSCAN (Density-Based Spatial Clustering)  
- Groups customers based on data density.  
- Can discover clusters of arbitrary shapes and detect noise/outliers.  

---

## ⚙️ Getting Started  

### Prerequisites  
- Python 3.7+  
- pip or conda environment  

## 📈 Performance & Evaluation  

- **K-Means:**  
  - Evaluated using **Silhouette Score** & **Inertia**.  
  - Provided clear and interpretable clusters.  

- **Gaussian Mixture Model (GMM):**  
  - Evaluated using **Log-Likelihood** & **BIC/AIC**.  
  - Captured overlapping clusters better than K-Means.  

- **DBSCAN:**  
  - Evaluated using **Silhouette Score** (on valid clusters).  
  - Effective in detecting noise and non-linear shaped clusters.  

✅ Each algorithm has different strengths:  
- **K-Means**: Simple & fast, good for spherical clusters.  
- **GMM**: Soft clustering with probabilistic interpretation.  
- **DBSCAN**: Handles noise & discovers clusters of arbitrary shape.  

---

## 🔍 Example Results  

- **K-Means** identified **5 clusters** with good separation.  
- **GMM** achieved smoother boundaries between customer groups.  
- **DBSCAN** detected dense clusters and flagged some customers as **noise**.  

### Example Segments:  

- **Cluster 1 →** High Income, High Spending (Target Customers 💎)  
- **Cluster 2 →** Low Income, High Spending (Potential Risk ⚠️)  
- **Cluster 3 →** Medium Income, Medium Spending (Average Customers 🙂)  
- **Cluster 4 →** High Income, Low Spending (Untapped Potential 🚀)  
- **Cluster 5 →** Low Income, Low Spending (Budget Customers 💰)  

