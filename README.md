# **Project Overview:**
This project focuses on customer segmentation using unsupervised machine learning techniques. The goal is to group customers based on behavioral and demographic features in order to extract meaningful business insights. These insights can help businesses improve targeted marketing, customer retention, and personalized customer strategies.

## Dataset Information:
Source: Kaggle (https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
The dataset contains customer demographic and behavioral attributes such as age, income, and spending score.
These features are used to understand customer patterns and segment them into distinct groups.

## Objective:
● Identify meaningful customer segments using clustering techniques

● Understand customer behavior patterns

● Generate business insights for marketing and strategy decisions


## Methodology:
1. Data Preprocessing
● Handled missing values

● Checked and removed duplicates 

● Encoded categorical variables 

● Scaled numerical features for clustering

3. Exploratory Data Analysis (EDA)

● Distribution analysis of key features

● Relationship between income, age, and spending behavior

●Visualization of customer patterns

5. Clustering Techniques

● K-Means Clustering

● Hierarchical Clustering                                                                         

7. Model Evaluation

● Elbow Method to determine optimal number of clusters

● Silhouette Score for cluster quality evaluation

● Visual inspection of cluster separation

9. Dimensionality Reduction

PCA used for visualization of clusters in 2D space
<img width="847" height="548" alt="image" src="https://github.com/user-attachments/assets/44e1b920-4185-4624-a2c6-6f52edb9cd0e" />


11. Key Insights

● Customers can be grouped into distinct segments based on spending behavior and income levels

● High-income, high-spending customers represent premium target groups

● Low-spending customers may require retention strategies

● Mid-segment customers present opportunities for targeted promotions

12. Business Impact

● Enables targeted marketing campaigns

● Helps improve customer retention strategies

● Supports personalized product recommendations

● Improves decision-making for pricing and promotions

14. Tools & Technologies

● Python

● Pandas, NumPy

● Matplotlib, Seaborn

● Scikit-learn

● Jupyter Notebook


## 11. Results 
● The optimal number of clusters was determined using the Elbow Method, suggesting a suitable value of K = 3 

● Silhouette Score was used to evaluate cluster quality, showing reasonably well-separated customer groups.

● Customers were successfully segmented into distinct behavioral groups based on income and spending patterns:

● Cluster 1: High income, high spending customers (premium segment)

● Cluster 2: High income, low spending customers (potential growth segment)

● Cluster 3: Low income, high spending customers (impulsive buyers)

● Cluster 4: Low income, low spending customers (low engagement segment)

● PCA visualization helped clearly separate clusters in a 2D space.

● Clustering results provide meaningful segmentation for targeted marketing strategies 



