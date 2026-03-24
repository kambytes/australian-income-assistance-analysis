# Australian Census Income & Assistance Analysis (2016 vs 2021)

## Overview
This project is a data analysis investigation exploring how personal income and core activity assistance needs vary across age groups using Australian Bureau of Statistics (ABS) Census data.

The analysis compares trends between the 2016 and 2021 Census datasets to examine the relationship between financial disadvantage and health-related vulnerability.

---

## Key Visual Insights

### Income Distribution by Age
![Income](figures/income_vs_age.png)

### Assistance Needs by Age
![Assistance](figures/assistance_vs_age.png)

---

## Project Objective
To analyse how income distribution and assistance needs vary across age groups and how these patterns have changed over time.

---

## Methodology
The project follows a structured data science workflow:

1. Data acquisition from ABS Census datapacks  
2. Data cleaning and preprocessing  
3. Exploratory data analysis  
4. Visualisation of demographic trends  
5. Comparative analysis between 2016 and 2021  

---

## Technologies & Skills

**Language:**
- Python  

**Libraries:**
- pandas  
- numpy  
- matplotlib  
- seaborn  
- jupyter  

**Skills Demonstrated:**
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Data visualisation  
- Working with real-world census datasets  
- Analytical reasoning and interpretation  

---

## Repository Structure
```
australian-income-assistance-analysis/
├── data/                                              (raw datasets, to be downloaded by user)
│   ├── 2016_GCP_AUS_for_AUS_short-header/        
│   │   ├── 2016_Census_GCP_Australia_for_AUS/     
│   │   ├── Metadata/                             
│   │   └── README/                                
│   ├── 2021_GCP_AUS_for_AUS_short-header/
│   │   ├── 2021_Census_GCP_Australia_for_AUS/         (CSV files with all tables of data)
│   │   ├── Metadata/                                  (summary spreadsheets of each table)
│   │   └── README/                                    (text files overviewing datapacks and terminologies used)
│   └── README.md                                      (instructions to download datasets)
├── notebook/
│   └── census-income-assistance-analysis.ipynb        (this jupyter notebook)
├── figures/                                           (saved graph images)
│   ├── assistance_vs_age.png                          
│   └── income_vs_age.png 
├── output/                                            
│   └── census-income-assistance-report.html           (saved html report)
├── .gitignore
├── README.md
└── requirements.txt
```

## Quick View (No Setup Required)

If you prefer not to run the notebook, you can view the full analysis directly:

Open the exported HTML report located in:
```
output/census-income-assistance-analysis.html
```

This contains the complete notebook with all outputs and visualisations.

---

## Setup & Usage

### 1. Clone repository

```bash
git clone <your-repo-url>
cd australian-income-assistance-analysis
```

### 2. Create virtual environment
```bash
python -m venv .venv
source .venv/bin/activate      # Run this if on Mac/Linux
.venv\Scripts\activate         # Run this if on Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the project
```bash
jupyter notebook
```

Inside Jupyter Notebook, open:
```
notebook/census-income-assistance-analysis.ipynb
```

## Dataset
Source: Australian Bureau of Statistics (ABS)
https://www.abs.gov.au/census/find-census-data/datapacks

Datasets used:
- G17B & G17C Total Personal Income (Weekly) by Age by Sex (2016 & 2021)
- G18 Core Activity Need for Assistance by Age by Sex (2016 & 2021)

Raw datasets are not included due to size. See data/README.md for instructions.

## Key Insights
- Assistance needs increase significantly with age
- Lower income groups are more likely to require assistance
- Trends appear more pronounced in 2021 compared to 2016

**Author:** Kamleshkumar Senthilkumar  
**Completed:** 24 September 2025