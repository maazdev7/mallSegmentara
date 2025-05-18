# 🛍️ Mall Customer Segmentation & Classification 📊

Welcome to the **Mall Customer Segmentation and Classification** project! 🚀  
This project explores the powerful combination of **unsupervised learning** (K-Means Clustering) and **supervised learning** (Decision Tree Classification) to analyze and classify mall customers based on their demographic and spending behavior. 🏪💸

---

## 📊 Project Overview

This project performs customer segmentation using **K-Means Clustering** followed by predicting the customer cluster with a **Decision Tree Classifier**. 🧑‍💼

1. **Unsupervised Learning** (K-Means) groups customers into segments based on their **Annual Income** and **Spending Score**.
2. **Supervised Learning** (Decision Tree) predicts the **Cluster Labels** based on customer features like **Age**, **Income**, and **Spending Score**.

By combining both techniques, we can better understand customer patterns and classify them for targeted marketing strategies. 🎯

---

### Prerequisites

You'll need the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🧑‍💻 Dataset

The dataset used for this project is the Mall Customers dataset. It contains information about mall customers, including their Age, Annual Income (in $k), and Spending Score (1-100).

Columns in the dataset:

Age: Age of the customer 👶👵

Annual Income (k$): Annual income of the customer 💰

Spending Score (1-100): Spending behavior on a scale of 1-100 💳

Genre: Gender of the customer (Male/Female) 👨‍🦰👩‍🦱

## 🔧 Data Preprocessing

Missing Values: Checked for any missing data.

### Normalization:

Scaled the features Age, Annual Income (k$), and Spending Score (1-100) using StandardScaler to ensure they are on the same scale. 📏

### Label Encoding:

Encoded the Genre column (Male/Female) into numerical values (0/1). 🎭

## 🔍 Unsupervised Approach: K-Means Clustering

We applied K-Means Clustering to group the customers into distinct clusters based on their Annual Income and Spending Score. 📦

### Elbow Method:

To determine the optimal number of clusters (K).

Cluster Visualization: Using PCA for dimensionality reduction, we visualized the 5 clusters.

Here’s the Elbow Method graph:

Clusters visualized using PCA:

## 🧠 Supervised Approach: Decision Tree Classification

We used a Decision 🌳 Classifier to predict customer clusters based on their Age, Annual Income, and Spending Score.

Split the data into training (70%) and testing (30%) sets.

Trained the Decision Tree on the training data and predicted cluster labels on the test data.

### 🙏 Acknowledgements

The dataset is publicly available at: Mall_Customers Dataset

Happy learning and exploring! ✨
