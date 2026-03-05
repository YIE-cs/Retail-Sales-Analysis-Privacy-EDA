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

## How to run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/coursework-eda-anonymisation.ipynb
