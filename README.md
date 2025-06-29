
# Commodity Price Forecasting (India)

This project forecasts future prices of essential commodities (like Wheat) across Indian states using time series modeling.

##  Project Overview

- **Dataset**: Multi-state daily commodity prices in India
- **Goal**: Forecast prices for top commodities to support analysis and decision-making
- **Approach**: Time series modeling using Facebook's Prophet

---

## 🔧 Key Steps

1. **Exploratory Data Analysis (EDA)**
   - Handled missing values and outliers
   - Checked for seasonality and trend

2. **Preprocessing**
   - Filtered top 6 commodities
   - Grouped data by `commodity`, `state_name`, and `date`

3. **Modeling**
   - Trained Prophet models for each commodity-state pair
   - Generated 30-day forecasts

4. **Result Storage**
   - Saved all forecasts (`ds`, `yhat`, `commodity`, `state_name`) into CSV for easy retrieval and visualization

---

## 📈 Visualization

- Plotted forecasted prices over time
- Highlighted trends and seasonal patterns

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Mohit-Nagraj/Commodity_price_forecasting.git
   
