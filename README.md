# AI-ENGINEERING-WITH-GOMYCODE

🛍️ Customer Segmentation and Targeted Marketing Campaign Using Clustering & Association Rules
📌 Project Overview

Businesses often struggle to understand their customers' purchasing behavior, making it difficult to create personalized marketing campaigns. This project applies unsupervised machine learning and market basket analysis to uncover hidden customer patterns and generate actionable business insights.

Using K-Means Clustering, customers are grouped according to their purchasing behavior and spending patterns. The project also leverages Association Rule Mining (Apriori Algorithm) to identify products that are frequently purchased together, enabling businesses to create targeted promotional campaigns and increase sales.

🎯 Business Problem

Marketing the same products to every customer is inefficient and often results in poor conversion rates. Businesses need a data-driven approach to:

Identify different customer segments.
Understand customer spending habits.
Recommend relevant products.
Improve marketing campaign performance.
Increase customer retention and revenue.
🎯 Objectives
Segment customers based on their spending behavior.
Discover meaningful customer groups using clustering techniques.
Identify frequently purchased product combinations.
Generate association rules for product recommendations.
Provide actionable insights for targeted marketing campaigns.
📊 Dataset

The dataset contains customer information such as:

Customer ID
Age
Gender
Annual Income
Spending Score
Purchased Products (for association rule mining)
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Mlxtend
Jupyter Notebook
📈 Machine Learning Techniques
1. Customer Segmentation

Algorithm Used

K-Means Clustering

Process

Data Cleaning
Feature Selection
Data Scaling
Elbow Method to determine the optimal number of clusters
K-Means Model Training
Cluster Visualization
2. Market Basket Analysis

Algorithm Used

Apriori Algorithm

Metrics Evaluated

Support
Confidence
Lift

The generated association rules help identify products that customers are likely to purchase together.

📊 Project Workflow
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Scaling
        │
        ▼
K-Means Clustering
        │
        ▼
Customer Segmentation
        │
        ▼
Association Rule Mining (Apriori)
        │
        ▼
Targeted Marketing Recommendations
📷 Visualizations

The project includes visualizations such as:

Customer distribution
Spending Score Analysis
Income Distribution
Correlation Heatmap
Elbow Curve
Customer Cluster Plot
Association Rule Metrics

💡 Key Insights
Customers can be divided into distinct spending groups.
High-income customers do not always have high spending scores.
Certain customer segments respond better to premium product promotions.
Several products are frequently purchased together, making them ideal candidates for bundle offers.
Personalized marketing campaigns are likely to outperform generic promotions.

📢 Business Recommendations
Design personalized marketing campaigns for each customer segment.
Reward high-value customers through loyalty programs.
Bundle products frequently purchased together.
Recommend complementary products during checkout.
Target low-spending customers with promotional discounts.
Focus premium campaigns on high-spending customer segments.
