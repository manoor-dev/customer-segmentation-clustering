# Customer Segmentation and Business Insights

##  Project Overview
This project focuses on customer segmentation using unsupervised machine learning techniques. The goal is to group customers based on behavioral and demographic features to extract meaningful business insights. These insights can help businesses improve targeted marketing, customer retention, and personalized strategies.

---

##  Dataset Information
The dataset contains customer demographic and spending behavior data including features such as age, income, and spending score. It is used to understand customer patterns and segment them into meaningful groups.

---

##  Objective
- Identify meaningful customer segments using clustering techniques  
- Understand customer behavior patterns  
- Generate actionable business insights for decision-making  

---

##  Methodology

### Data Preprocessing
- Handled missing values  
- Checked and removed duplicates (if any)  
- Encoded categorical variables (if applicable)  
- Scaled numerical features for clustering  

---

### Exploratory Data Analysis (EDA)
- Analyzed distribution of key features  
- Studied relationship between income, age, and spending behavior  
- Visualized customer patterns using graphs  

---

### Clustering Technique
- K-Means Clustering  
- Optimal number of clusters determined using Elbow Method  

---

### Evaluation
- Elbow Method used to find optimal clusters  
- Silhouette Score used to evaluate cluster quality  
- PCA used for 2D visualization of clusters  

---

##  Results and Findings
- Customers were segmented into distinct groups based on income and spending behavior  
- Identified different customer types such as:
  - High income, high spending customers (premium segment)  
  - High income, low spending customers (potential growth segment)  
  - Low income, high spending customers (impulsive buyers)  
  - Low income, low spending customers (low engagement segment)  
- PCA visualization clearly showed separation between clusters  

---

##  Business Impact
- Helps in designing targeted marketing campaigns  
- Improves customer retention strategies  
- Enables personalized product recommendations  
- Supports data-driven decision-making for business growth  

---

##  Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

##  How to Run This Project
```bash
git clone https://github.com/manoor-dev/customer-segmentation-clustering.git
cd customer-segmentation-clustering
pip install -r requirements.txt
jupyter notebook
