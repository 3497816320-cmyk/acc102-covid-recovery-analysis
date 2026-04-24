# COVID-19 Economic Recovery Analysis

## **1. Problem & User**  
This project explores how different countries recovered economically after the COVID-19 pandemic using GDP data. It is intended for students and beginners who want to understand economic trends through clear and simple analysis.

## **2. Data**  
**Source:** World Bank (GDP, current US$)  
**Accessed:** April 2026  

The dataset includes GDP values for selected countries in 2019 and 2023, with key fields such as country name and GDP values for each year.  

The data was downloaded from the World Bank and then cleaned and organised into a simplified CSV file, which is included in the `data/` folder.


## **3. Methods**  
The analysis was carried out in Python using pandas and matplotlib. The main steps include loading the dataset, cleaning and formatting the data, calculating GDP growth rates, and ranking countries based on their recovery speed. Visualisations were created using bar charts and line charts to present the results more clearly.


## **4. Key Findings**  
- All selected countries show signs of economic recovery after COVID-19  
- Growth rates vary across countries rather than following a single pattern  
- Larger economies do not necessarily grow faster in percentage terms  
- Absolute GDP increase does not directly indicate faster recovery  


## **5. How to run**  
- Open the notebook in Jupyter Notebook or JupyterLab  
- Ensure pandas and matplotlib are installed  
- Run all cells (**Kernel → Restart & Run All**)  
- Output charts will be saved in the `figures/` folder  


## **6. Product link / Demo**  
**GitHub Repository:**  
https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis  

**Notebook:**  
https://github.com/3497816320-cmyk/acc102-covid-recovery-analysis/blob/main/covid_recovery_analysis.ipynb  

**Demo Video:**  
[Paste your video link here]


## **7. Limitations & next steps**  
The dataset includes only a limited number of countries, which may affect how representative the results are. GDP alone may not fully capture economic recovery, and as this analysis is based on nominal GDP (current US$), the results may also be influenced by factors such as inflation and exchange rate changes, so they should be interpreted with some caution.  

The data is also simplified and focuses on selected years rather than a full time period.  

**Future improvements:**  
- Include more countries and a longer time period  
- Add additional indicators such as inflation or unemployment  
- Apply more advanced analytical methods for deeper insights  
