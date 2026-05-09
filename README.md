# 🛒 E-Commerce Customer Segmentation Analysis

![Python](https://img.shields.io/badge/Python-3.14-blue)
![ML](https://img.shields.io/badge/ML-KMeans-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Problem Statement
E-commerce businesses lose revenue by treating all customers
the same. This project segments customers using RFM Analysis
and K-Means Clustering to enable targeted marketing strategies.

## 🎯 Objective
- Perform EDA on Indian e-commerce sales data
- Calculate RFM scores for 332 unique customers
- Apply K-Means Clustering to identify distinct customer groups
- Deliver actionable business insights via Power BI dashboard

## 📊 Datasets Used

### 1. Indian E-Commerce Sales Dataset (Kaggle)
- **Files:** List of Orders, Order Details, Sales Target
- **Size:** 1,500 transactions, 332 unique customers
- **Period:** April 2018 – March 2019
- **Used For:** RFM Analysis, Customer Segmentation, Sales Trends

### 2. Flipkart Products Dataset (Kaggle)
- **Size:** 20,000 products, 15 attributes
- **Used For:** Product category analysis, pricing trends
- **Link:** https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products

> Datasets not included due to size. Download from Kaggle and place in `data/raw/`

## 🔑 Key Findings
- **4 distinct customer segments** identified via K-Means (K=4)
- **High Value Champions** (31 customers) avg spend ₹5,120 — 4x more than At Risk
- **At Risk customers** (142) need urgent win-back campaigns
- **Churned customers** (88) inactive for 253+ days on average
- **Electronics** drives highest revenue among all categories

## 📈 RFM Customer Segments
| Segment | Customers | Avg Spend | Avg Recency |
|---|---|---|---|
| 👑 High Value Champions | 31 | ₹5,120 | 56 days |
| 🟢 Recent Active Buyers | 71 | ₹1,318 | 44 days |
| ⚠️ At Risk | 142 | ₹798 | 113 days |
| ❌ Churned Inactive | 88 | ₹747 | 253 days |

## 🛠️ Tech Stack
- **Language:** Python 3.14
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Dashboard:** Power BI
- **Version Control:** Git & GitHub

## 📁 Project Structure

ecommerce-segmentation/
├── notebooks/
│   ├── 01_EDA_India_Ecommerce.ipynb   ← Sales EDA
│   ├── 02_RFM_Analysis.ipynb          ← RFM Scoring
│   └── 03_KMeans_Clustering.ipynb     ← Customer Clusters
├── outputs/                           ← All 9 plots
└── README.md

## 🚀 How to Run
```bash
git clone https://github.com/ChoppaPraveen/ecommerce-customer-segmentation.git
pip install -r requirements.txt
python -m jupyter notebook
# Run notebooks in order: 01 → 02 → 03
```

## 📬 Contact
**Choppa Praveen** — github.com/ChoppaPraveen
