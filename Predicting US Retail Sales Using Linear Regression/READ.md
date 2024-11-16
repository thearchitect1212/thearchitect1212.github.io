# Predicting US Retail Sales Using Linear Regression

## Overview
This project analyzes historical US retail sales data and builds a predictive model to forecast future trends. By focusing on time-series patterns and economic events, the project highlights the impact of external factors such as the COVID-19 pandemic and the Great Recession on retail sales.

---

## Key Features
- **Trend Analysis**: Visualized historical sales data over decades.
- **Predictive Modeling**: Applied linear regression to forecast future sales.
- **Economic Context**: Analyzed sales anomalies during major economic events.

---

## Dataset
- **Source**: Public US retail sales dataset.
- **Size**: Monthly sales data spanning multiple decades.
- **Features**:
  - Year
  - Month
  - Retail Sales (in millions)
- **Preprocessing**:
  - Combined year and month columns into a single date feature.
  - Handled missing values and normalized sales data.

---

## Methodology
1. **EDA**:
   - Visualized monthly and yearly sales trends.
   - Identified deviations caused by events like the 2008 recession and 2020 pandemic.
2. **Modeling**:
   - Trained a linear regression model to predict sales based on historical trends.
   - Evaluated performance using metrics such as R-squared and RMSE.
3. **Forecasting**:
   - Predicted monthly retail sales for the test period.
   - Visualized forecasts alongside actual data to assess accuracy.

---

## Key Insights
- Retail sales show a steady upward trend, disrupted by external economic shocks.
- The COVID-19 pandemic caused a significant dip, followed by rapid recovery.
- Linear regression captured long-term trends effectively but struggled with short-term fluctuations.

---

## Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Linear Regression)
- Time-Series Analysis Tools

---

## Applications
- **Economic Analysis**: Helps businesses and policymakers understand retail trends.
- **Forecasting**: Provides a baseline model for retail sales prediction.
- **Decision Support**: Assists in resource planning for retail organizations.

---

## Future Directions
1. Incorporate additional features such as inflation and unemployment rates.
2. Apply advanced models like ARIMA or LSTMs for improved short-term forecasting.
3. Develop an interactive dashboard to visualize trends and forecasts dynamically.

---

## References
1. Federal Reserve Economic Data (FRED) on US Retail Sales.
2. Scikit-learn Documentation for Linear Regression.
3. Research on Time-Series Modeling.

---
