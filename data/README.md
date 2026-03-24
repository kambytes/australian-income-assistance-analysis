# Data Directory

This folder contains the raw Australian Bureau of Statistics (ABS) Census datasets used in this project.

## How to Obtain the Data

1. Go to the ABS Census Datapacks website: https://www.abs.gov.au/census/find-census-data/datapacks 
2. Select:
   - Census year: 2016 and 2021  
   - Datapack type: General Community Profile (GCP)  
   - Geography: Australia  

3. Download and unzip both datasets

## Expected Structure

After extraction, place the folders inside this directory as follows:

```
australian-income-assistance-analysis/
└── data/                                              (raw datasets)
│   ├── 2016_GCP_AUS_for_AUS_short-header/        
│   │   ├── 2016_Census_GCP_Australia_for_AUS/     
│   │   ├── Metadata/                             
│   │   └── README/                                
│   ├── 2021_GCP_AUS_for_AUS_short-header/
│   │   ├── 2021_Census_GCP_Australia_for_AUS/         (CSV files with all tables of data)
│   │   ├── Metadata/                                  (summary spreadsheets of each table)
│   │   └── README/                                    (text files overviewing datapacks and terminologies used)
│   └── README.md                                      (instructions to download datasets)
├── notebook/census-income-assistance-analysis.ipynb   (this jupyter notebook)
├── figures/                                           (saved graph images)
├── output/                                            (saved html report)
├── .gitignore
├── README.md
└── requirements.txt
```