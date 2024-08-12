
# TransJakarta-Data-Analysis

This repository contains the analysis of the TransJakarta Bus Rapid Transit (BRT) system, focusing on issues like sexual harassment, overcrowding, and peak hour congestion. The goal is to provide data-driven insights to improve user experience and operational efficiency.

## Problem Statement

TransJakarta, the first BRT system in Southeast and South Asia, faces significant challenges as it operates 24/7 across Jakarta. Key issues include:

- **Sexual Harassment:** Incidents against female passengers, as reported in various news outlets.
- **Overcrowding:** Increased passenger numbers lead to uncomfortable and often unsafe conditions during peak hours.

This analysis aims to identify the underlying factors contributing to these problems and propose actionable solutions.

## Analysis Objectives

The analysis is structured around several key questions:

### User Demographics by Gender:

- What is the gender distribution of TransJakarta users?
- Which corridors are most frequently used by female passengers?

### Peak Hour Analysis:

- When do peak usage times occur, leading to overcrowding?
- Which corridors and bus stops are most congested during peak hours?

## Data

The analysis is based on data collected from TransJakarta, including details on user demographics, travel times, and route utilization. The dataset contains various features such as:

- **payCardBank:** Bank issuing the payment card
- **payCardName:** Name of the cardholder
- **payCardSex:** Gender of the cardholder
- **payCardBirthDate:** Birth year of the cardholder
- **corridorID:** Route code
- **tapInStops:** Entry bus stop details
- **tapOutStops:** Exit bus stop details
- **payAmount:** Payment amount

## Methodology

The analysis was conducted using Python, leveraging libraries like Pandas, Matplotlib, Seaborn, Plotly, and Folium for data manipulation, visualization, and geospatial analysis. Statistical tests such as the Chi-Square Test, Mann-Whitney U Test, and T-Test were used to draw significant insights.

## Findings and Recommendations

### Key Findings:

- **Overcrowding:** Certain corridors and bus stops experience significant congestion during specific hours.
- **Gender-Based Usage:** Female passengers tend to use specific routes more frequently, raising safety concerns.

### Recommendations:

- **Enhanced Safety Measures:** Implementing stricter security protocols, especially on routes frequently used by female passengers.
- **Improved Bus Frequency:** Increasing bus frequency during peak hours on congested corridors to reduce overcrowding.

## How to Use This Repository

- **Notebook:** The Jupyter Notebook (`Capstone Kia Final.ipynb`) contains the full analysis, including code and visualizations.
- **Data:** The cleaned dataset (`Cleaned_TJ.csv`) used in this analysis is available for further exploration.
- **Visualizations:** Interactive dashboards created with Plotly and Folium can be found in the notebook and Tableau file (`Capstone Kia.twbx`).

## Conclusion

This analysis provides a data-driven approach to understanding and addressing the challenges faced by TransJakarta. By leveraging these insights, TransJakarta can enhance passenger safety, improve user experience, and optimize operations.
