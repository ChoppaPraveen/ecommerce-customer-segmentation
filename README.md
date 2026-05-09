# 🛒 E-Commerce Customer Segmentation Analysis

![Python](https://img.shields.io/badge/Python-3.14-blue)
![ML](https://img.shields.io/badge/ML-KMeans-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Problem Statement
E-commerce businesses lose revenue by treating all customers
the same. This project segments customers using RFM Analysis
and K-Means Clustering to enable targeted marketing strategies.

## 🎯 Objective
- Perform RFM Analysis on Indian e-commerce transaction data
- Apply K-Means Clustering to identify distinct customer groups
- Deliver actionable insights via Power BI dashboard

## 📊 Dataset
- **Source:** Indian E-Commerce Sales Dataset (Kaggle)
- **Size:** 1,500 transactions, 332 unique customers
- **Period:** April 2018 – March 2019

## 🔑 Key Findings
- **4 distinct customer segments** identified via K-Means
- **High Value Champions** (31 customers) avg spend ₹5,120
- **At Risk customers** (142) need urgent win-back campaigns
- **Churned customers** (88) inactive for 253+ days

## 📈 RFM Segments
| Segment | Customers | Avg Spend |
|---|---|---|
| High Value Champions | 31 | ₹5,120 |
| Recent Active Buyers | 71 | ₹1,318 |
| At Risk | 142 | ₹798 |
| Churned Inactive | 88 | ₹747 |

## 🛠️ Tech Stack
- **Language:** Python 3.14
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Dashboard:** Power BI
- **Version Control:** Git & GitHub

## 📁 Project Structure

ecommerce-segmentation/
├── notebooks/
│   ├── 01_EDA_India_Ecommerce.ipynb
│   ├── 02_RFM_Analysis.ipynb
│   └── 03_KMeans_Clustering.ipynb
├── outputs/             ← All plots
└── README.md

## 🚀 How to Run
```bash
git clone https://github.com/ChoppaPraveen/ecommerce-customer-segmentation.git
pip install -r requirements.txt
python -m jupyter notebook
```

## 📬 Contact
**Choppa Praveen** — github.com/ChoppaPraveen
