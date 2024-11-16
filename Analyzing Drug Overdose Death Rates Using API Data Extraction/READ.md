# Analyzing Drug Overdose Death Rates Using API Data Extraction

## Overview
This project analyzes trends in drug overdose death rates across various demographic groups using data retrieved from the CDC's API. The goal is to identify patterns and provide insights into how drug overdose deaths have evolved over time, focusing on age, year, and substance categories.

---

## Key Features
- **API Data Retrieval**: Leveraged CDC's public API to automate data collection.
- **Dynamic Analysis**: Explored trends across demographics, including age and substance type.
- **Visualization**: Created clear and informative plots to communicate findings effectively.

---

## Dataset
- **Source**: CDC API
- **Size**: National data spanning multiple years.
- **Features**:
  - **Demographics**: Age, sex, race, and location.
  - **Substances**: Types of drugs contributing to overdose deaths.
  - **Time Period**: Yearly trends across decades.
- **Preprocessing**:
  - Filtered and cleaned raw data from the API response.
  - Standardized feature names for consistency.
  - Handled missing values by imputing median values for numerical data.

---

## Methodology
1. **Data Retrieval**:
   - Accessed CDC's API using Python's `requests` library.
   - Parsed JSON responses into a structured dataframe.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized trends using line plots, bar charts, and histograms.
   - Compared overdose rates across different age groups and substances.
3. **Insights Extraction**:
   - Analyzed demographic disparities in overdose deaths.
   - Focused on year-on-year changes to identify spikes or declines.

---

## Key Insights
- **Rising Trends**: Significant increase in overdose deaths, especially in younger age groups.
- **Substance Analysis**: Opioids and synthetic drugs showed the steepest rise over the years.
- **Demographic Impact**: Higher mortality rates observed in specific regions and age groups.

---

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- CDC API
- Data Visualization Tools (Tableau for additional dashboards)

---

## Applications
- **Public Health Policy**: Helps policymakers understand demographic vulnerabilities and focus resources effectively.
- **Healthcare Insights**: Assists healthcare providers in tailoring prevention and intervention programs.
- **Data Automation**: Demonstrates how APIs can streamline data analysis workflows.

---

## Future Directions
1. Extend analysis to include social determinants of health (e.g., income, education).
2. Automate updates to the dataset as new CDC data becomes available.
3. Develop predictive models for overdose trends using machine learning.

---

## References
1. Centers for Disease Control and Prevention (CDC). Public API for overdose data.
2. Research papers on drug addiction and overdose prevention.

---
