# COVID-19 Economic Recovery Analysis

## 1. Problem & User
This project examines how different countries recovered economically after the COVID-19 pandemic using GDP data. It is designed for students and beginners who want a clear and straightforward comparison of recovery patterns across countries.

## 2. Data
Source: World Bank (GDP, current US$)  
Accessed: April 2026  

Key fields:
- Country Name  
- GDP (2018–2023)  

The dataset was downloaded from the World Bank and filtered to include 18 countries from different regions and levels of development. A cleaned version of the dataset is included in the data/ folder.

## 3. Methods
The analysis was carried out in Python using the following steps:
- Load data using pandas  
- Clean and format the dataset (set index, convert units to trillion USD)  
- Calculate GDP growth rates (2019–2023)  
- Rank countries based on growth rate  
- Visualise results using matplotlib (bar chart and multi-year trend chart)  

## 4. Key Findings
- All selected countries show recovery after COVID-19, but at different speeds  
- Emerging economies generally achieve higher growth rates  
- Developed economies show more stable but slower growth  
- Countries with larger economies tend to have lower percentage growth due to a higher starting base  
- The multi-year data shows a clear dip around 2020 followed by recovery  

## 5. How to run
- Open the notebook in Jupyter Notebook or JupyterLab  
- Make sure pandas and matplotlib are installed  
- Run all cells in order (Kernel → Restart & Run All)  
- Output charts will be saved in the figures/ folder  

## 6. Product link / Demo
GitHub Repository:  
https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis  

Notebook:  
https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis/blob/main/covid_recovery_analysis.ipynb  

## 7. Limitations & next steps
This project is based on a selected group of countries, which may limit how representative the results are. GDP is also the only indicator used, so it does not fully capture all aspects of economic recovery, such as employment, inflation, or sector-level performance.

In addition, the analysis uses nominal GDP (current US$), which may be influenced by inflation and exchange rate changes, so the results should be interpreted with some caution.

Future improvements could include:
- Expanding the dataset to include more countries and a longer time period  
- Adding additional indicators such as inflation or unemployment  
- Applying more advanced analytical methods for deeper insights  
