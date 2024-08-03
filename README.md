# TBIA_DataAnalysisContest
Using TBIA's open data and any other data source to construct a topic which is related to Ecology.

This repository contains data analysis projects for the TBIA (Taiwan Blue Industry Alliance) Data Analysis Contest. The project focuses on analyzing ocean temperature data and fish migration behavior in Taiwan's coastal areas.

## Notebooks

### 1. EU_Ocean_Tempt.ipynb

This notebook visualizes the temperature differences in the Taiwan Strait over the past 20 years using heat maps. It provides a clear visual representation of how ocean temperatures have changed over time in this specific region.

### 2. 烏魚分佈EDA.ipynb (Gray Mullet Distribution EDA)

This notebook performs Exploratory Data Analysis (EDA) on the distribution of Gray Mullet, using TBIA's open data. The main tasks in this notebook include:

- Aligning dates to a "standard date" format
- Cleaning missing values using representative descriptive statistics such as mean or mode
- Analyzing the distribution patterns of Gray Mullet in Taiwanese waters

### 3. 台灣沿海海溫觀測紀錄.ipynb (Taiwan Coastal Ocean Temperature Records)

This notebook focuses on analyzing coastal ocean temperature records in Taiwan. The main tasks include:

- Accessing data using the JSON library
- Creating line charts to visualize shore ocean temperature records
- Calculating the mean temperature during winter months

## Data Sources

- TBIA open data
  https://tbiadata.tw/zh-hant/search/occurrence?record_type=occ&name=%E7%83%8F%E9%AD%9A&page=1&from=search&limit=10
- EU ocean temperature data
  https://data.marine.copernicus.eu/products
- Taiwan coastal ocean temperature records
  https://www.cwa.gov.tw/V8/C/

## Requirements

- Python 3. or above
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, json (full list of dependencies can be found in each notebook)
