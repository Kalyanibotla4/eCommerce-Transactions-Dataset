# **eCommerce Transactions Analysis**

## **Overview**
This repository contains the solution to a data science assignment focused on analyzing an eCommerce transactions dataset. The tasks include exploratory data analysis (EDA), building a lookalike model for customer similarity, and performing customer segmentation using clustering techniques.

---

## **Tasks and Deliverables**

### **Task 1: Exploratory Data Analysis (EDA)**
- **Objective**: Analyze the provided datasets to uncover trends, patterns, and actionable insights.
- **Datasets**:
  - **Customers.csv**: Contains customer profiles (e.g., region, signup date, and tenure).
  - **Products.csv**: Includes product details (e.g., category, price).
  - **Transactions.csv**: Logs customer transactions (e.g., quantity, revenue, and transaction date).
- **Deliverables**:
  - `EDA_Report.pdf`: A comprehensive report summarizing 5 key business insights.
  - `EDA_Notebook.ipynb`: Jupyter notebook containing the EDA code and visualizations.

### **Task 2: Lookalike Model**
- **Objective**: Recommend 3 similar customers for the first 20 customers in `Customers.csv` using profile and transaction data.
- **Methodology**:
  - Features such as purchase history, region, and tenure were used to calculate similarity.
  - A similarity score is assigned to each recommended customer.
- **Deliverables**:
  - `Lookalike_Recommendations.csv`: A file with top 3 recommendations and similarity scores for each customer.
  - `Lookalike_Model.ipynb`: Jupyter notebook with the implementation of the lookalike model.

### **Task 3: Customer Segmentation (Clustering)**
- **Objective**: Segment customers into clusters based on spending, transaction frequency, and recency.
- **Approach**:
  - Used K-Means clustering to identify customer segments.
  - Evaluated the clustering quality using the Davies-Bouldin Index (DBI), Silhouette Score, and Inertia.
  - Visualized the clusters for easier interpretation and actionable insights.
- **Deliverables**:
  - `Clustering_Report.pdf`: A detailed report on clustering results and business recommendations.
  - `Clustering_Notebook.ipynb`: Jupyter notebook containing the clustering implementation and visualizations.

---

## **Requirements**
To run the notebooks, install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn 
