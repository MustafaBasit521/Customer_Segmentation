# Customer_Segmentation
🛒 Customer Segmentation using K-Means & DBSCAN
📌 Project Overview:
This project applies Unsupervised Learning techniques to cluster mall customers into meaningful segments based on their Annual Income and Spending Score.
The goal is to understand customer behavior and group similar customers together, which can help businesses with targeted marketing strategies.

⚙️ Steps Performed
1. Data Cleaning & Preprocessing
Removed missing values and duplicates.
Converted features into numeric format.
Scaled data using StandardScaler to normalize income & spending score.
2. Data Visualization (Before Clustering)
Plotted customer distribution by Annual Income vs. Spending Score.
This gave an initial idea of potential clusters.
3. K-Means Clustering
Used the Elbow Method (WCSS) to determine the optimal number of clusters.
Found 3 clusters to be optimal.
Trained a KMeans model with 3 clusters.
Assigned each customer to a cluster and visualized results with distinct colors.
4. Cluster Analysis
Calculated the average spending score per cluster.
Visualized average spending with a bar chart to identify high-value vs low-value customers.
Interpreted clusters as:
Cluster 0 → Budget Customers (Low income, low spending)
Cluster 1 → Luxury Customers (High income, high spending)
Cluster 2 → Balanced Customers (Moderate spending patterns)
5. Bonus: DBSCAN Clustering
Applied DBSCAN for density-based clustering.
Detected noise/outliers and compared with KMeans results.
DBSCAN is useful for finding irregular shapes in customer groups.

📊 Results & Insights
Customers were grouped into 3 main segments.
Business can:
Focus promotions on Luxury Customers (high income + high spending).
Design budget-friendly offers for Budget Customers.
Retain Balanced Customers with loyalty rewards.
Average spending visualization gave clear insight into customer value distribution.
🛠️ Tools & Libraries
Python
Pandas (data cleaning & manipulation)
Matplotlib (visualization)
Scikit-learn
StandardScaler (feature scaling)
KMeans (clustering)
DBSCAN (density-based clustering)
🚀 Conclusion
This project demonstrates how Unsupervised Learning can be applied to real-world business problems.
Customer segmentation helps businesses personalize marketing strategies, optimize product placement, and improve customer satisfaction.
Future improvements may include:
Using more features (Age, Gender, etc.) for deeper segmentation.
Trying hierarchical clustering.

Applying clustering results directly into a recommendation system.
