# Retail Sales Analysis – Privacy & Ethical Data Handling

**Coursework 2 – Data Analytics / Machine Learning module**

**Objective**  
Process and anonymise a retail transaction dataset, perform exploratory data analysis, and discuss ethical implications (privacy, fairness, EDI).

## Dataset
- **Original file**: `retail_store_sales.csv` (~12.5k rows)
- Contains: transaction info, customer category purchases, payment methods, discounts, etc.
- **Sensitive fields removed**: `Transaction ID`, `Customer ID`

## What I did
1. Anonymisation (direct identifier removal)
2. Basic data cleaning & exploration
3. Visual comparison: average spend per category — normal vs high-value customers
4. Ethical discussion (section still in progress)

## Key Visualisations

<p align="center">
<img width="1325" height="552" alt="image" src="https://github.com/user-attachments/assets/ce4dd4a2-ee80-4f0b-af5d-783f82acb0da" />
  <br><em>Direct identifiers removed</em>
</p>

<p align="center">
<img width="727" height="475" alt="image" src="https://github.com/user-attachments/assets/c0833ca5-caa1-49bd-8eee-1346eb7e15be" />
  <br><em>Higher spend in most categories for high-value customers</em>
</p>

## Technologies used
- Python, pandas, matplotlib, seaborn
- Visualisation experiment: Bokeh (interactive plots)

## Dataset
- **File**: `data/retail_store_sales.csv`
- **License**: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
- **Source**: [Insert original source here — e.g. "Provided for university coursework" / Kaggle link / etc.]
- **Original creator**: [Name/organization if known, or "Original dataset authors" if unknown]
- **Changes made in this repo**:
  - In `coursework2`: Removed direct identifiers (`Transaction ID`, `Customer ID`) → see `data/retail_store_sales_anonymised.csv`
  - Minor cleaning, feature engineering, and analysis in notebooks

This dataset is redistributed here in compliance with CC BY-SA 4.0.  
You may share and adapt it, provided you give appropriate credit and license any modifications under CC BY-SA 4.0 (or compatible later version).  
Full license: https://creativecommons.org/licenses/by-sa/4.0/legalcode

**Note**: The derived/anonymized file is a modification and is therefore also licensed under CC BY-SA 4.0.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/coursework-eda-anonymisation.ipynb
