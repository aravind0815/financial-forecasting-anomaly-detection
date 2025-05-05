
# 📊 Financial Forecasting + Anomaly Detection Dashboard

An end-to-end interactive dashboard that leverages **Python**, **SQL**, and **Streamlit** to analyze, forecast, and detect anomalies in time-series financial data.

## 🚀 Project Highlights

- 🔢 **Revenue & Profit KPIs**: Live key performance indicators computed from sales data.
- 📆 **Yearly and Monthly Trends**: Interactive line and bar charts using `matplotlib` and `Streamlit`.
- 🌍 **Geographic Insights**: Country-wise sales rankings.
- 🚨 **Anomaly Detection**: Identifies unusual drops in sales and profit using rule-based methods.
- 🐘 **PostgreSQL Integration**: Data is stored and queried from PostgreSQL (locally or cloud-ready).
- 📊 **Streamlit Dashboard**: Deployed on [Streamlit Cloud](https://financial-forecasting-anomaly-detection-007.streamlit.app/).

## 🧰 Tech Stack

- **Frontend:** Streamlit
- **Backend/Data:** Pandas, SQL (PostgreSQL), pg8000, SQLAlchemy
- **Visualization:** Matplotlib, Streamlit native charts
- **Deployment:** Streamlit Cloud
- **Data Source:** Cleaned financial sales dataset with regional, product-wise revenue and cost breakdown [click here to see the dataset](https://www.kaggle.com/datasets/atharvaarya25/financials)

## 📁 Folder Structure

```
financial-forecasting-anomaly-detection/
├── data/
│   └── Financials_CLEAN.csv
├── dashboard/
│   └── app.py
├── notebooks/
│   ├── 01_data_cleaning_EDA.ipynb
│   ├── 02_sql_kpis_extraction.ipynb
│   ├── 03_forecasting_arima_prophet.ipynb
│   └── 04_anomaly_detection.ipynb
├── sql/
│   ├── create_tables.sql
│   ├── kpi_queries.sql
│   └── anomaly_detection_queries.sql
├── requirements.txt
└── README.md
```

## ✅ How to Run Locally

1. Clone the repo:
```bash
git clone https://github.com/aravind0815/financial-forecasting-anomaly-detection.git
cd financial-forecasting-anomaly-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the app:
```bash
streamlit run dashboard/app.py
```

## 🧠 Skills Demonstrated

- Data Engineering with PostgreSQL
- Time Series Forecasting
- Anomaly Detection Techniques
- KPI Design & Dashboarding
- Full Stack Data Science Project Development
- GitHub Collaboration & Streamlit Deployment

## 🔗 Live App

👉 [Streamlit App](https://financial-forecasting-anomaly-detection-007.streamlit.app/)  
👉 [GitHub Repo](https://github.com/aravind0815/financial-forecasting-anomaly-detection)

---

### 📌 Author

**Aravind Kalyan Sivakumar**  
Data Science @ NJIT | Python • SQL • ML • Cloud  
[LinkedIn](https://www.linkedin.com/in/aravindkalyan007/)
