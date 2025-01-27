

# **eCommerce Transactions Analysis**

## **Overview**
This repository contains the solution to a data science assignment focused on analyzing an eCommerce transactions dataset. The tasks include exploratory data analysis (EDA), building a lookalike model for customer similarity, and performing customer segmentation using clustering techniques.

---

## **Tasks and Deliverables**

### **Task 1: Exploratory Data Analysis (EDA)**
- **Objective**: Analyze the provided datasets to uncover trends, patterns, and insights.
- **Datasets**:
  - **Customers.csv**: Contains customer profiles (e.g., region, signup date).
  - **Products.csv**: Includes product details (e.g., category, price).
  - **Transactions.csv**: Logs of customer transactions (e.g., quantity, total value).
- **Deliverables**:
  - `FirstName_LastName_EDA.pdf`: Report with 5 key business insights.
  - `FirstName_LastName_EDA.ipynb`: Notebook with EDA code.

### **Task 2: Lookalike Model**
- **Objective**: Recommend 3 similar customers for the first 20 customers in `Customers.csv` based on profile and transaction data.
- **Methodology**:
  - Use customer and product information for similarity calculations.
  - Assign a similarity score to each recommendation.
- **Deliverables**:
  - `FirstName_LastName_Lookalike.csv`: Contains customer recommendations with similarity scores.
  - `FirstName_LastName_Lookalike.ipynb`: Notebook with the lookalike model.

### **Task 3: Customer Segmentation (Clustering)**
- **Objective**: Segment customers into clusters using their profiles and transaction history.
- **Approach**:
  - Choose a clustering algorithm (e.g., K-means).
  - Evaluate using metrics like the Davies-Bouldin Index (DBI).
  - Visualize clusters for interpretation.
- **Deliverables**:
  - `FirstName_LastName_Clustering.pdf`: Report on clustering results.
  - `FirstName_LastName_Clustering.ipynb`: Notebook with clustering code.

---

## **Requirements**
Install the necessary Python libraries before running the notebooks:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
