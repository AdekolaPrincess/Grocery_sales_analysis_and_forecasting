# Grocery Sales Forecasting

This project is an **end-to-end data science workflow** where we explore grocery sales data, generate insights, and build a machine learning model to predict **how much quantity of each product should be restocked weekly**.

## 🔍 Project Overview
- **Exploratory Data Analysis (EDA):**
  - Checked dataset info & summary statistics.
  - Handled missing values, outliers, and skewness.
  - Explored sales patterns using SQL & Python.

- **Key Insights:**
  - Quantity strongly influences revenue.  
  - Most revenue comes from high-demand products, but a few low-volume products still drive high revenue due to higher prices.  
  - Seasonal patterns: February shows peak demand; sales drop after March.  
  - Product category has the biggest impact on sales predictions, followed by week (seasonality). City/location contributes little.  

- **Modeling:**
  - Compared multiple regression models (Linear Regression, Random Forest, XGBoost).  
  - Selected **XGBoost Regressor** as the best-performing model for forecasting product restocking needs.  

## 📌 Conclusion & Recommendations

Our analysis shows that **sales are strongly driven by product demand and seasonality**.  
- Products with higher quantities sold consistently generate the most revenue.  
- A few niche products, even in lower quantities, bring in high revenue because of premium pricing.  
- Sales peak in **February**, followed by a decline after March — suggesting a seasonal influence.  
- Product category is the most important factor for predicting sales, while city/location contributes little.

**Recommendations:**  
- 📦 **Prioritize restocking** fast-moving products to meet demand without running out of stock.  
- 📈 **Plan inventory ahead of seasonal spikes** (e.g., February) and adjust after March to prevent overstocking.  
- 💰 **Maintain a balance** by keeping premium, low-volume products in stock since they bring high revenue margins.  
- 🏙️ **Reduce dependency on city/location** as a planning factor, and instead focus on product type and demand trends.
