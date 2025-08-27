# 📊 Rossmann Sales Forecasting (Capstone Project)

Forecasting daily sales for Rossmann drug stores using advanced **time-series models (SARIMAX, VAR, VECM)**, statistical tests (ADF, KPSS, Johansen), and feature engineering.  

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
[![Python](https://img.shields.io/badge/python-3.8%2B-brightgreen.svg)](https://www.python.org/)  

---

## ✨ About the Project  

Rossmann operates over **3,000 drug stores** across Europe. Store managers currently forecast sales subjectively, leading to inconsistency and errors.  

This project builds a **robust sales forecasting framework** using statistical and ML-based time-series techniques, leveraging historical **daily sales, customer, and promotion data**. The aim is to predict sales **6 weeks ahead**, helping the company optimize:  

- 🛒 **Inventory Management**  
- 👩‍💼 **Staff Scheduling**  
- 🚚 **Logistics Planning**  
- 💰 **Revenue Forecasting**  

Key Benefits:  

- **Improved Forecast Accuracy**: Replaces subjective store manager forecasts with data-driven predictions.  
- **Efficient Resource Planning**: Helps Rossmann allocate inventory, staff, and marketing spend effectively.  
- **Scalable Framework**: Designed to extend across all **1,115 stores**, not just the 9 key stores analyzed.  

Example Use Cases:  

- "What will be the expected sales for Store 25 in the next 6 weeks?"  
- "How much impact do promotions have on daily sales?"  

---

## 🔍 Key Features  

- 📊 **EDA & Visualization**: Trends, seasonality, promotions, and holiday effects on sales.  
- 📉 **Outlier Handling**: Winsorization at the 99th percentile for Sales & Customers.  
- 🔄 **Stationarity Tests**: ADF, KPSS, Johansen cointegration.  
- 🧮 **Baseline Models**: Naive & Seasonal Naive forecasting.  
- 📈 **Advanced Models**: SARIMAX with exogenous variables, VAR, and VECM.  
- 🧩 **Feature Engineering**: Log transforms, z-scores, exogenous regressors (Promo, Promo2, Holidays).  
- ✅ **Evaluation Metric**: MAPE (Mean Absolute Percentage Error) across all stores.  
- 📊 **Model Comparison**: Baselines vs SARIMAX vs VAR.  
- 🔍 **Impact Analysis**: Quantifies effect of Customers & Promotions using log-OLS.  

---

## 🛠️ Tech Stack  

- **Language**: Python (Jupyter Notebook)  
- **Frameworks/Libraries**: Pandas, Numpy, Statsmodels, Scikit-learn, Seaborn, Matplotlib  
- **Models Used**: SARIMAX, VAR, VECM  
- **Tools**: Jupyter Notebook, GitHub  

---

## 🚀 Getting Started  

### Prerequisites  

Ensure you have the following installed:  
- Python 3.8+  
- Jupyter Notebook  

### Installation  

1. Clone the repo:  
   ```bash
   git clone https://github.com/Arif1234/Capstone---Sales-Forecasting.git
   cd Capstone---Sales-Forecasting
