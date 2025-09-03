# Retail-Inventory-Optimization-Demand-Forecasting


##  Overview
This project focuses on **retail inventory optimization and demand forecasting** using machine learning and data analysis techniques.  
It leverages a synthetic dataset with daily records of multiple stores and products, including **inventory levels, sales, promotions, weather, and holidays**.  

The project addresses:
- **Demand Forecasting**
- **Dynamic Pricing Adjustments**
- **Holiday/Promotion Impact Analysis**
- **Stockout Risk Classification**
- **Retail Inventory Optimization (Reorder Levels, Dead Stock, etc.)**

---

##  Dataset Features
- **Date** – Daily records from start to end date  
- **Store ID & Product ID** – Unique identifiers  
- **Category** – Product categories (Electronics, Clothing, Groceries, etc.)  
- **Region** – Geographic region of the store  
- **Inventory Level** – Stock available at the start of the day  
- **Sales (Units Sold)** – Units sold during the day  
- **Demand Forecast** – Predicted demand from past trends  
- **Weather Condition** – Weather factors impacting sales  
- **Holiday/Promotion** – Indicators for special events  

---

##  Key Tasks & Outputs

###  Demand Forecasting
- Implemented **Random Forest Regressor**
- Evaluated with **MAE, RMSE, and MAPE**
- Provided accurate demand forecasts for each product/store

###  Dynamic Pricing Adjustments
- Analyzed price sensitivity to **sales & promotions**
- Suggested optimal price adjustments for maximizing revenue

###  Holiday/Promotion Impact
- Visualized **average sales during holidays vs. normal days**
- Measured uplift in demand due to events

###  Stockout Risk Classification
- Classified products into **High / Medium / Low stockout risk**
- Provided insights to prevent lost sales

###  Retail Inventory Optimization
- Visualized:
  - **Stock Levels**
  - **Reorder Points**
  - **Dead Stock Analysis**

---

##  Visual Outputs
The following visualizations were generated:
- 📈 Demand Forecasting Plots  
- 💰 Dynamic Pricing Effect Graphs  
- 🎉 Holiday/Promotion Impact Charts  
- ⚠️ Stockout Risk Report  
- 📦 Inventory Optimization (Reorder, Dead Stock, Trends)

---
##  Project Report
All results, graphs, and insights are compiled in a PDF report:  
 `Retail_Inventory_Optimization_Report.pdf`

---

##  Tech Stack
- **Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)**
- **Machine Learning** – Random Forest Regressor, Classification models
- **Data Visualization** – Matplotlib, Seaborn
- **PDF Report Generation** – ReportLab

---

##  Future Enhancements
- Integration with **real-world retail datasets**
- Deployment of forecasting model as an **API**
- Addition of **Reinforcement Learning for dynamic pricing**
- Real-time dashboards for inventory & sales

---

##  Author **Pooja Potnurwar**  

---
