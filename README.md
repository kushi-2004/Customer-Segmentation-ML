Customer Segmentation Analysis 🚀

Leveraging Machine Learning for Targeted Marketing Strategies

📌 Project Overview

This project focuses on grouping customers based on their purchasing behavior using K-Means Clustering. By analyzing RFM (Recency, Frequency, Monetary) metrics, we identify distinct customer segments, allowing businesses to tailor their marketing strategies, improve customer retention, and maximize revenue.

🛠️ Tech Stack

Language: Python

Libraries: * Pandas (Data Manipulation)

NumPy (Numerical Computing)

Scikit-learn (Machine Learning & Preprocessing)

Matplotlib & Seaborn (Data Visualization)

📊 Methodology
1. Data Generation: Created a synthetic dataset of 200 customers featuring Recency (days since last purchase), Frequency (total transactions), and Monetary (total spend).
2. Feature Scaling: Applied StandardScaler to ensure all features contribute equally to the distance-based clustering algorithm.
3. Elbow Method: Conducted a Within-Cluster Sum of Squares (WCSS) analysis to determine the optimal number of clusters ($k=3$).
4. Clustering: Implemented the K-Means algorithm to segment the customer base.
5. Export: Generated a labeled CSV file (Customer_Segments.csv) for business use.

📈 Key Insights & Customer Segments


Based on the analysis, the customers were divided into three main groups:

Cluster 0 (VIP/High Value): Frequent shoppers who spend significantly. Strategy: Loyalty rewards and early access.

Cluster 1 (At-Risk/Churn): High spenders who haven't visited recently. Strategy: Personalized discount codes to win them back.

Cluster 2 (New/Average): Newer customers with moderate spending habits. Strategy: Upselling through bundled offers.

🚀 How to Run

1. Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`
2. Run the Python script or Notebook.
<img width="787" height="707" alt="Screenshot 2026-05-06 165819" src="https://github.com/user-attachments/assets/f5cad222-4945-4431-b833-c6c545b336f0" />
