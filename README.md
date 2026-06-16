# 🛒 CPG Retail Analytics — Demand Forecasting & Sales Performance
**Tools Used:** Python | SQL | XGBoost | K-Means Clustering | Pandas | Matplotlib

---

## 📌 Business Problem
A Consumer Packaged Goods (CPG) retail chain operating 1,115 stores needed to:
- Improve demand forecasting accuracy for better inventory planning
- Identify high and low performing store segments
- Measure promotional effectiveness across the store network
- Understand monthly revenue trends for strategic planning

---

## 📊 Dataset
- **Source:** Rossmann Store Sales (Kaggle)
- **Size:** 844,338 daily sales records across 1,115 stores
- **Period:** 2013 — 2015
- **Features:** Sales, Customers, Promotions, Holidays, Store Type, Competition Distance

---

## 🏆 Key Results

| Metric | Result |
|--------|--------|
| Total Network Revenue | £5.87 Billion |
| Promotional Sales Uplift | 38.8% more sales on promo days |
| Peak Revenue Month | December 2013 — £232M |
| High Performing Stores | 192 out of 1,115 stores (17%) |
| Baseline Forecast Accuracy | 55.8% (simple average) |
| XGBoost Forecast Accuracy | 75.8% |
| Improvement over Baseline | +20.1 percentage points |
| Best Store Type | Type B — £10,231 avg daily sales |

---

## 📁 Project Structure
---

## 📈 Visual Results

### Revenue by Store Type
![Revenue by Store Type](outputs/chart1_revenue_by_store_type.png)

### Promotional Effectiveness
![Promotional Effectiveness](outputs/chart2_promo_effectiveness.png)

### Monthly Revenue Trend
![Monthly Revenue Trend](outputs/chart3_monthly_revenue_trend.png)

### Store Segmentation — K-Means Clustering
![Store Clusters](outputs/chart4_store_clusters.png)

### Actual vs Predicted Sales — XGBoost Model
![Actual vs Predicted](outputs/chart5_actual_vs_predicted.png)
