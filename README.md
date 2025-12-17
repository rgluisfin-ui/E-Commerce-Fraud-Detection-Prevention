# 🔍 Fraud Detection Analysis Project

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-blue)
![Tableau](https://img.shields.io/badge/Tableau-2023+-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Project Overview

A comprehensive fraud detection analysis system for e-commerce transactions, featuring exploratory data analysis, SQL-based analytics, and interactive Tableau dashboards.

### Key Features
- ✅ **10,000+ transactions analyzed** across multiple dimensions
- ✅ **Python EDA** with statistical insights and visualizations
- ✅ **PostgreSQL queries** for deep-dive analysis
- ✅ **Interactive Tableau dashboard** for real-time monitoring
- ✅ **Actionable insights** for fraud prevention strategies

---

## 🎯 Business Problem

Our e-commerce platform is experiencing financial losses due to fraudulent transactions. This project aims to:
- Identify high-risk transaction patterns
- Analyze fraud across merchant categories, countries, and time periods
- Develop risk scoring frameworks
- Create monitoring dashboards for real-time fraud detection

---

## 📊 Dataset

- **Source:** Synthetic fraud transaction data
- **Records:** 10,000 transactions
- **Features:** 10 columns including transaction details, risk scores, and fraud labels
- **Time Period:** Various hours (0-23)

### Data Schema
| Column | Type | Description |
|--------|------|-------------|
| transaction_id | Integer | Unique transaction identifier |
| user_id | Integer | User identifier |
| amount | Float | Transaction amount in USD |
| transaction_type | String | Type of transaction |
| merchant_category | String | Merchant business category |
| country | String | Transaction country |
| hour | Integer | Hour of transaction (0-23) |
| device_risk_score | Float | Device-based risk score (0-1) |
| ip_risk_score | Float | IP-based risk score (0-1) |
| is_fraud | Integer | Fraud label (0=Legitimate, 1=Fraud) |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- PostgreSQL 13+
- Tableau Desktop 2023+ (for dashboard)
- Git


