# Customer Segmentation Using K-means Clustering
This project implements a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to segment customers into meaningful groups to allow personalized marketing and service strategies.

## 📁 Files in this Repository
`Prodigy_ML_Task_2.ipynb:` Jupyter Notebook containing the entire process of implementing K-means clustering for customer segmentation.<br>
`Mall_Customers.csv:` A dataset containing customer information such as age, gender, annual income, and spending score.
## 📊 Dataset Overview
The dataset used for this task, `Mall_Customers.csv`, consists of 200 entries and includes the following features:
**CustomerID:** Unique ID assigned to each customer.<br>
**Gender:** The gender of the customer.<br>
**Age:** The age of the customer.<br>
**Annual Income:** Annual income of the customer in thousands of dollars.<br>
**Spending Score:** A score between 1 and 100 assigned to customers based on their spending behavior in the store.<br>

## 🚀 Project Workflow
**Data Loading and Exploration:**
- Loaded and explored the dataset to understand its structure.
- Checked for any missing data or inconsistencies.

**Data Preprocessing:**
- Scaled the features using StandardScaler to ensure that all features are on the same scale, as K-means is sensitive to the scale of the data.

**K-means Clustering:**
- Implemented the K-means clustering algorithm.
- Determined the optimal number of clusters using the Elbow Method, plotting the sum of squared distances to identify where the curve bends.
- Fit the model on selected features (such as Annual Income and Spending Score).

**Cluster Visualization:**
- Visualized the clusters using scatter plots to show how the customers were grouped based on their income and spending patterns.

## 📈 Results
By using K-means clustering, the customer data was segmented into distinct groups based on their income and spending score. These insights can be used by retail stores for targeted marketing and improving customer relationships.

**Dataset Used:** - [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
