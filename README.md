# COVID-19 Economic Recovery Analysis

## 1. Problem & User

This project analyses which countries recovered the fastest economically after the COVID-19 pandemic using GDP data. The target users are students and beginners who want to understand economic recovery trends through simple and interpretable data analysis.

## 2. Data

Source: World Bank (GDP, current US$)
Accessed: April 2026

Key fields:

* Country Name
* GDP (2019)
* GDP (2023)

The dataset was downloaded from the World Bank and cleaned for analysis. A processed CSV file is included in the data/ folder for reproducibility.

## 3. Methods

The analysis was conducted using Python with the following steps:

* Data loading using pandas
* Data cleaning and formatting (column renaming, unit conversion to trillion USD)
* Calculation of GDP growth rates
* Sorting and ranking countries by recovery speed
* Data visualisation using matplotlib (bar chart and line chart)

## 4. Key Findings

* All selected countries show economic recovery after COVID-19
* Emerging economies (e.g. India and China) demonstrate higher growth rates
* Developed economies (e.g. USA and Germany) show more stable but slower growth
* Absolute GDP increase does not equal faster recovery due to different economic bases

## 5. How to run

1. Open the notebook in Jupyter Notebook or JupyterLab
2. Ensure required libraries are installed (pandas, matplotlib)
3. Run all cells in order (Kernel → Restart & Run All)
4. Output charts will be saved in the figures/ folder

## 6. Product link / Demo

GitHub Repository: https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis

Notebook: https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis/blob/main/covid_recovery_analysis.ipynb

Demo Video: [Paste your video link here]

## 7. Limitations & next steps

The dataset includes a limited number of countries, which may affect how representative the results are. GDP alone may not fully capture economic recovery, as it does not reflect factors such as employment, inflation, or industry performance. In addition, this analysis is based on nominal GDP (current US$), which may be affected by inflation and exchange rate changes, so the results should be interpreted with some caution.

The data is also simplified and focuses on selected years rather than a full time series.

Future improvements:

Include more countries and a longer time period
Add additional indicators such as inflation, unemployment, or sector-level data
Apply more advanced analytical methods for deeper insights
