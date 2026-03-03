# 🛒 SmartCart Customer Segmentation System

## 📌 Problem Statement

SmartCart is a growing e-commerce platform serving customers across multiple countries. 

The company has collected extensive customer data consisting of **2240 customer records and 22 attributes**, including:

- Customer demographics  
- Purchase behaviour  
- Website activity  
- Campaign response  

Currently, SmartCart uses generic marketing strategies for all customers without clearly understanding different customer behaviour patterns.

This results in:

- ❌ Inefficient marketing spend  
- ❌ Missed opportunities to retain high-value customers  
- ❌ Delayed identification of churn-prone users  

To solve this problem, SmartCart aims to build an **Intelligent Customer Segmentation System** using **Unsupervised Machine Learning**.

As an AI/ML Engineer, the goal is to:

- Discover hidden patterns in customer behaviour  
- Group customers into meaningful clusters  
- Support personalized marketing strategies  
- Enable data-driven decision-making  

---

## 📊 Dataset Description

Each row represents one customer and includes the following categories:

---

### 1️⃣ Customer Demographics

| Feature | Description |
|----------|-------------|
| ID | Unique customer identifier |
| Year_Birth | Year of birth |
| Education | Highest education level |
| Marital_Status | Marital status |
| Income | Yearly household income |
| Kidhome | Number of small children |
| Teenhome | Number of teenagers |
| Dt_Customer | Enrollment date |

---

### 2️⃣ Purchase Behaviour (Amount Spent)

| Feature | Description |
|----------|-------------|
| MntWines | Amount spent on wine |
| MntFruits | Amount spent on fruits |
| MntMeatProducts | Amount spent on meat |
| MntFishProducts | Amount spent on fish |
| MntSweetProducts | Amount spent on sweets |
| MntGoldProds | Amount spent on gold products |

---

### 3️⃣ Purchase Behaviour (Frequency)

| Feature | Description |
|----------|-------------|
| NumDealsPurchases | Purchases using discounts |
| NumWebPurchases | Purchases via website |
| NumCatalogPurchases | Purchases via catalog |
| NumStorePurchases | Purchases in physical stores |
| NumWebVisitsMonth | Website visits per month |

---

### 4️⃣ Customer Feedback & Activity

| Feature | Description |
|----------|-------------|
| Recency | Days since last purchase |
| Complain | 1 = Complained in last 2 years, 0 = No complaint |

---

## 🧠 Solution Approach

This project uses:

- Data Cleaning & Feature Engineering
- One Hot Encoding
- Standard Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Elbow Method
- Silhouette Score
- 3D Cluster Visualization
- Gradio Interface for live predictions

---

## 🎯 Business Impact

After clustering, customers can be categorized as:

- 🏆 High-Value Customers
- 💰 Regular Customers
- ⚠ At-Risk Customers
- ❄ Low Engagement Customers

This enables:

- Targeted promotions  
- Retention campaigns  
- Better resource allocation  
- Increased ROI  

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio

---

## 🚀 Future Improvements

- Deploy model using Streamlit / HuggingFace
- Add SHAP explainability
- Automate cluster labeling
- Build Marketing Recommendation Engine

---

## 🌐 Live Demo

🚀 Running on Public URL:  
https://23731cf21b424b5f57.gradio.live

## 👨‍💻 Author

Rushikesh Ramesh Lokhande  
AI/ML Engineer | Data Science Enthusiast
