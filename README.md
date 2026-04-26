# 🛍️ Customer Segmentation using RFM Analysis & Machine Learning

## 📌 Project Overview

This project performs **Customer Segmentation** using transactional retail data to identify different types of customers based on purchasing behavior.

Instead of treating all customers equally, businesses can use this analysis to understand customer value and design **targeted marketing strategies**.

The project applies **Data Analysis, Feature Engineering, Visualization, and Machine Learning** to uncover hidden customer patterns.

---

## 🎯 Objectives

* Clean and preprocess real-world retail transaction data
* Create meaningful customer behavior features
* Perform **RFM Analysis**
* Apply **Clustering Algorithms** for segmentation
* Visualize customer groups for business insights

---

## 📊 Dataset

**Online Retail Dataset**

Contains:

* Invoice information
* Product details
* Quantity purchased
* Transaction timestamps
* Customer IDs
* Country information

---
<img width="1259" height="394" alt="image" src="https://github.com/user-attachments/assets/51bc60a3-0c33-43ef-9ce1-cb42c45aa7ea" />


## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 🧠 Methodology

### 1️⃣ Data Cleaning

* Removed missing Customer IDs
* Removed cancelled transactions
* Converted datetime formats
* Created Total Price feature

```
TotalPrice = Quantity × UnitPrice
```
HeatMaps:

<img width="527" height="418" alt="heatmap" src="https://github.com/user-attachments/assets/1c3d1bb8-b009-4e82-a407-a4713e05242f" />

PairPlots:

<img width="741" height="741" alt="pairplot" src="https://github.com/user-attachments/assets/05cac3b3-0f27-477b-a38a-648c7d00cb19" />


---

### 2️⃣ Feature Engineering — RFM Analysis

**RFM Features:**

* **Recency** → How recently a customer purchased
* **Frequency** → Number of purchases
* **Monetary** → Total money spent

These features summarize customer behavior into measurable metrics.

---
<img width="531" height="314" alt="Screenshot 2026-04-26 213017" src="https://github.com/user-attachments/assets/04367352-a759-4fc6-8175-52df9547d08a" />

### 3️⃣ Data Scaling

Standardization applied to normalize RFM values before clustering.

---

### 4️⃣ Exploratory Visualization

* Distribution plots
* Correlation analysis
* Cluster visualization using PCA

---
3D Graph:
<img width="403" height="399" alt="cluster3d" src="https://github.com/user-attachments/assets/a78e088f-34a5-4adf-92a8-bc5ca9ca900e" />

2D Graph:
<img width="546" height="413" alt="clusters2d" src="https://github.com/user-attachments/assets/416052fb-24e4-4503-bd52-f8844b287cef" />



### 5️⃣ Customer Segmentation (K-Means Clustering)

K-Means algorithm grouped customers into **4 clusters** based on purchasing patterns.

---


## 📈 Results — Customer Segments

| Cluster | Customer Type              | Business Meaning                        |
| ------- | -------------------------- | --------------------------------------- |
| 0       | Loyal High-Value Customers | Frequent buyers generating high revenue |
| 1       | At-Risk Customers          | Long time since last purchase           |
| 2       | Regular Customers          | Moderate purchase behavior              |
| 3       | Potential Customers        | Can be converted into loyal users       |

---

## 💡 Business Impact

This segmentation helps businesses:

✅ Personalize marketing campaigns
✅ Improve customer retention
✅ Identify high-value customers
✅ Reduce churn
✅ Increase revenue using data-driven decisions

---

## 📊 Machine Learning Pipeline

```
Data Cleaning
      ↓
Feature Engineering (RFM)
      ↓
Scaling
      ↓
Visualization
      ↓
K-Means Clustering
      ↓
Customer Insights
```

---

## 🚀 Future Improvements

* Try DBSCAN / Hierarchical Clustering
* Build Customer Lifetime Value model
* Deploy dashboard using Streamlit
* Real-time customer segmentation API

---

## ✨ Key Learning Outcomes

* Practical Data Science workflow
* Feature engineering for business problems
* Unsupervised Machine Learning
* Data visualization & interpretation
* Translating analytics into business decisions

---

## 🤝 Connect

If you found this project useful or have suggestions, feel free to connect and discuss Data Science ideas!

⭐ Star the repository if you like the project.
