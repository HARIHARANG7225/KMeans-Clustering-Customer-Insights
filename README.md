🧩 Customer Segmentation using K-Means Clustering
📌 Project Overview
This project demonstrates the application of K-Means clustering to segment customers based on their Annual Income and Spending Score. The goal is to identify distinct customer groups that can be leveraged for targeted marketing strategies and business insights.

🔹 Methodology
- Data Preparation
- Imported dataset (kmeans.csv) using Pandas.
- Selected relevant features: Annual Income and Spending Score.
- Exploratory Visualization
- Plotted a scatter graph to observe the raw distribution of customers.
- Data Preprocessing
- Standardized features using StandardScaler to ensure fair clustering.
- Initial Clustering
- Applied K-Means with 5 clusters.
- Added cluster labels to the dataset for analysis.
- Elbow Method
- Ran K-Means for cluster counts from 1 to 9.
- Plotted inertia values to identify the optimal number of clusters.
- Final Clustering & Visualization
- Selected 4 clusters based on the elbow method.
- Visualized customer groups with distinct colors for clear interpretation.

🔹 Key Insights
- Customers can be grouped into distinct segments based on income and spending behavior.
- The Elbow Method helped determine that 4 clusters provide the best balance between accuracy and simplicity.
- Visualizations highlight patterns such as high-income low-spending customers and low-income high-spending customers, which are valuable for marketing decisions.

📊 Tools & Libraries
- Pandas – Data handling
- Matplotlib – Visualization
- Scikit-learn – StandardScaler & K-Means clustering

🌟 Business Impact
This project showcases how unsupervised learning can be applied to customer segmentation, enabling businesses to:
- Personalize marketing campaigns.
- Identify high-value customers.
- Improve customer retention strategies.
