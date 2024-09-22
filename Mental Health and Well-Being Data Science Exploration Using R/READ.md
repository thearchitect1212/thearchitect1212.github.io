# The Rise of Mental Illness: Data Science to the Rescue
**Author**: Said Moussadeq  
**Date**: February 9, 2024  

## Overview
This project focuses on understanding the rise of mental illness using data science. By analyzing various datasets, the goal is to uncover potential environmental contributors to mental health, such as sleep, diet, substance use, social media, and isolation. The study seeks to provide insights into how these factors influence mental well-being and explores data-driven solutions to address the mental health crisis.

## Research Questions
The project aims to answer the following key questions:
- Is there a link between sleep quality, overall well-being, and mental health?
- How does diet influence mental health?
- Could the use of substances be a significant factor in the deterioration of mental health?
- Is there a connection between social media addiction and poor mental health?
- How does social isolation affect mental health?

## Approach
Using data science techniques such as covariance, correlation, and regression analysis, the project examines the relationship between environmental factors and mental health. Visualizations such as scatter plots, bar charts, and correlation matrices are employed to better understand the data and the relationships between variables.

## Data Sources
The following datasets were used in this project:

1. **Social Media and Well-being**  
   - Study on digital behavior on social media and its effects on mental health.
   - Year: 2022  
   - Location: Kisii University College Faculty of Health Sciences  
   - [Link to Dataset](https://data.mendeley.com/datasets/jxkcm7s638/1)

2. **Meaning in Life: Predictive Factor for Loneliness**  
   - Scores for predictors of loneliness, including health status and social connectedness.
   - Year: 2020  
   - Location: Universitat de Barcelona  
   - [Link to Dataset](https://data.mendeley.com/datasets/zy39mdzxpg/2)

3. **Getting More Sleep Linked to Higher Well-Being**  
   - Evaluates the relationship between sleep and well-being.  
   - Year: 2014  
   - Location: U.S.  
   - [Link to Dataset](https://news.gallup.com/poll/181583/getting-sleep-linked-higher.aspx)

4. **Mental Health Disorders and Substance Use**  
   - Prevalence of mental health and substance use disorders.  
   - Year: 2017  
   - [Link to Dataset](https://cdn.mdedge.com/files/s3fs-public/JFP06809400.PDF)

5. **Food and Mental Health**  
   - Relationship between food consumption, stress, and depressive symptoms among university students.  
   - Year: 2014  
   - Location: UK  
   - [Link to Dataset](https://www.semanticscholar.org/paper/Food-and-mental-health%3A-relationship-betweenfood-Ansari-Adetunji/7089d0982e871d4024e26d04a9e00d478c418e81)

## Libraries Used
- `readxl`
- `tidyverse`
- `ppcor`
- `readr`
- `dplyr`
- `ggplot2`
- `GGally`
- `reshape2`

## Key Visualizations
- Scatter Plot: Used to analyze relationships between variables such as sleep, loneliness, and exercise.
- Bar Chart: Used to represent data on food consumption and depressive symptoms.
- Correlation Matrix: Helps visualize the strength and direction of relationships between various factors.

## Findings
- **Loneliness and Mental Health**: A moderate negative correlation suggests that better mental health is associated with less loneliness.
- **Sleep and Well-being**: A strong positive correlation was observed between the number of hours slept and well-being index scores.
- **Substance Use and Mental Health**: Individuals with substance use disorders experience significantly higher rates of mental health conditions like schizophrenia and bipolar disorder compared to the general population.
- **Food and Mental Health**: Eating unhealthy foods such as fast food and sweets is associated with higher depressive symptoms, while healthier foods like fruits and vegetables are linked to better mental health.

## Future Steps
This project highlights the need for more comprehensive, longitudinal studies to explore causality in mental health. Additionally, the use of wearables and AI technology could revolutionize our understanding and management of mental health.

## How to Access the Report
- The full report is available in PDF format: [The_Rise_of_Mental_Illness_Report.pdf](./The_Rise_of_Mental_Illness_Report.pdf)

## Conclusion
Data science offers powerful tools to analyze and understand the factors contributing to mental illness. By leveraging these insights, we can develop more effective, data-driven strategies to improve mental well-being.

