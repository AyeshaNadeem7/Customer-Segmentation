# Customer-Segmentation
Customer segmentation project using K-Means to group shoppers based on income and spending behavior. Helps businesses target marketing strategies for different customer types.
🧩 Project Objective:
Segment customers into distinct groups based on their annual income and spending behavior using unsupervised machine learning techniques. This allows businesses to tailor marketing strategies and enhance customer experience.

📦 Dataset:
Mall Customer Segmentation Dataset (from Kaggle) with ~200 entries. Key features include:

💵 Annual Income (k$)

💳 Spending Score (1–100)

👤 Customer ID

🧍‍♂️ Gender

🎂 Age

🛠 Process:
📋 Data Preprocessing:
Data processing is not required in that dataset because on the basis of income and spending score the cluster form which are already in numerical form.

📐 Feature Scaling:
Applied StandardScaler or MinMaxScaler for normalization

Ensured features were scaled properly for distance-based clustering

🧪 Clustering with K-Means:
Applied K-Means clustering from Scikit-learn

Used Elbow Method to determine optimal number of clusters (typically 4–5)

Visualized the clusters using 2D scatter plots (e.g., Income vs Spending Score)

🔬 Other Algorithms:
Tried DBSCAN to detect non-spherical or noise-included clusters

Compared cluster structures to K-Means for robustness

📈 Technologies Used:
Python

Pandas (data manipulation)

Matplotlib & Seaborn (visualization)

Scikit-learn (clustering, scaling)
