# Customer Segmentation Wine Dataset
Customer segmentation based on wine attributes dataset

### 🍷 Wine Customer Segmentation
This project focuses on clustering and segmenting wine customers based on their behavioral attributes. By leveraging unsupervised machine learning techniques, the goal is to discover hidden customer segments that can inform personalized marketing strategies and product offerings.

### 📊 Dataset
It includes features such as:
CustomerID: Unique ID for each customer
Recency: Days since last purchase
Frequency: Number of purchases
Monetary: Amount spent
Champagne, Other, Red, White: Product preferences
Discount: Sensitivity to discounts

### 🧠 Methods Used
1. Data Preprocessing
2. Clustering Techniques 
3. Evaluation Metrics
Silhouette Score: Measures how similar an object is to its own cluster compared to other clusters. Ranges from -1 to 1.
Adjusted Rand Index (ARI): Measures clustering accuracy by comparing predicted clusters to actual labels.

### 🏆 Results
KMeans and GMM produced similar Silhouette Scores, indicating comparable intra-cluster similarity.
GMM slightly outperformed KMeans in ARI, suggesting better alignment with true underlying patterns.

### 🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn (KMeans, GaussianMixture, PCA)
Matplotlib, Seaborn (for visualization)
Jupyter Notebook

