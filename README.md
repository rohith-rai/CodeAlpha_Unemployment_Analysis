# CodeAlpha_Task2_Unemployment_Analysis
# Unemployment Analysis with Python

This project is part of my Data Science Internship at **CodeAlpha**.

## About
The goal is to analyze unemployment rate trends in India, study the impact of Covid-19 on unemployment, and identify patterns across regions and time that could inform policy decisions.

## Dataset
The dataset (`Unemployment_in_India.csv`) contains monthly unemployment data with the following features:
- Region (Indian state)
- Date
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area (Rural / Urban)

## Steps Followed
1. Loaded and explored the dataset
2. Cleaned the data (fixed column name spacing, removed empty rows, converted dates)
3. Plotted the national unemployment rate over time
4. Compared unemployment trends between Rural and Urban areas
5. Compared average unemployment rate across regions
6. Checked for monthly/seasonal patterns

## Results
Unemployment in India spiked sharply around April 2020, coinciding with the Covid-19 lockdown. Rural and urban areas were affected differently, and some regions consistently show higher unemployment than others regardless of the pandemic. This points to both a short-term shock (Covid-19) and longer-term regional differences worth addressing through policy.

## Tools Used
- Python
- Pandas
- Matplotlib & Seaborn

## How to Run
1. Open the notebook `CodeAlpha_Task2_Unemployment_Analysis.ipynb` in [Google Colab](https://colab.research.google.com)
2. Upload `Unemployment_in_India.csv` when prompted
3. Run all cells in order

## Internship
This project was completed as part of the **Data Science Internship at CodeAlpha**.
