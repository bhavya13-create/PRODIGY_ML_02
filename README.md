# PRODIGY_ML_02
# 🛍️ Customer Segmentation using K-Means Clustering

This project demonstrates **Customer Segmentation** for a retail store using the **K-Means Clustering** algorithm.  
The dataset contains customers' **Annual Income** and **Spending Score**, and we use clustering to group them into distinct customer segments.

---

## 📌 Project Overview
Customer segmentation helps businesses understand different types of customers and target them with personalized marketing strategies.  
In this project:
- We use **K-Means Clustering** to segment customers.
- We find the **optimal number of clusters** using the **Elbow Method**.
- We visualize the clusters and their centroids.
- We test the model with **new customer data**.

---

## 📂 Dataset
The dataset contains:
- `Annual Income (k$)` – Annual income of the customer in thousands of dollars.
- `Spending Score (1-100)` – Score assigned by the store based on customer behavior.

> **Note:** The dataset is provided in a `.zip` file and is loaded directly from the archive.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data handling
- **Matplotlib** & **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning (K-Means Clustering)

---
## 📊 Visualizations

### 1. Elbow Curve
- Helps determine the **optimal number of clusters** by plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters.

### 2. Scatter Plot (Clusters with Centroids)
- Visualizes the **customer segments** in different colors.
- Shows **centroids** (cluster centers) labeled with their cluster number.

### 3. Line Plot (Annual Income vs Spending Score)
- Displays the **relationship** between a customer's annual income and spending score.
- Useful for spotting **spending trends** across income levels.

