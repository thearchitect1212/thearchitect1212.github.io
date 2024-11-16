# Analyzing the Rise in Drug Overdose Death Rates Using API Data Extraction

## Overview
This project analyzes the alarming rise in drug overdose death rates across various demographic groups using real-time data from the CDC's API. By focusing on patterns over time, it sheds light on the growing public health crisis and highlights demographic disparities and substance trends.

---

## Key Features
- **API Integration**: Automated data extraction from the CDC's API for up-to-date information.
- **Trend Analysis**: Explores year-over-year changes in overdose deaths.
- **Demographic Insights**: Identifies how overdose rates differ by age, gender, and region.
- **Substance Trends**: Analyzes the prevalence of specific drugs contributing to deaths.

---

## Dataset
- **Source**: CDC API for drug overdose mortality data.
- **Size**: National and state-level data across decades.
- **Features**:
  - Year
  - Age Group
  - Gender
  - Substance Type
  - Mortality Rates
- **Preprocessing**:
  - Filtered out incomplete or irrelevant data fields.
  - Standardized feature names for consistency.
  - Addressed missing values by imputing median values for numerical data.

---

## Methodology
1. **Data Retrieval**:
   - Accessed the CDC’s API using Python’s `requests` library.
   - Extracted data as JSON and converted it into a structured DataFrame.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized trends using line plots and bar charts.
   - Compared rates across age groups and substances.
3. **Insights Extraction**:
   - Focused on identifying sharp increases or decreases over time.
   - Explored regional variations to determine high-risk areas.

---

## Key Insights
- **Rising Trends**: Overdose deaths have increased steadily, particularly among younger age groups.
- **Opioid Epidemic**: Synthetic opioids like fentanyl contribute significantly to the rise in mortality rates.
- **Regional Disparities**: Certain regions, such as the Midwest and Appalachia, have been disproportionately affected.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **API Integration**: CDC's RESTful API

---

## Applications
- **Public Health**:
  - Helps policymakers allocate resources effectively.
  - Assists in identifying high-risk populations for targeted interventions.
- **Healthcare**:
  - Aids providers in understanding substance abuse trends.
  - Supports prevention and treatment initiatives.

---

## Future Directions
1. Expand analysis to include socioeconomic factors like income and education.
2. Automate periodic data updates to track real-time trends.
3. Integrate machine learning to predict future overdose trends.

