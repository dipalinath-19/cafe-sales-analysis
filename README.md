# Cafe Sales: Data Cleaning & Analysis

A practice project: cleaning a messy sales export and turning it into charts a cafe owner can use.

> The dataset is a **synthetic practice dataset**, not real business data.

## The problem
The sales spreadsheet had duplicate rows, dates in three formats, inconsistent spellings, missing values and impossible numbers.

## What I did
1. Explored the data (types, missing values, duplicates, value counts)
2. Cleaned a copy of the raw file and logged every change
3. Made 5 charts: revenue per month, top items by quantity and by revenue, payment methods, and day of the week

## Cleaning log
- Removed 25 duplicate rows
- Standardized item, category, and payment names
- Converted dates from 3 formats to one
- Treated 1 price of $75 as a typo; filled 35 missing prices with each item's usual price
- Removed 37 rows with a missing, negative, or extreme quantity
- Filled 25 missing staff names with "Unknown"
- Result: 625 rows became 563 clean rows

## Files
- Notebook: the full analysis
- `cafe_sales_raw.csv` and `cafe_sales_clean.csv`: before and after
- PNG files: the charts

## Tools
Python, pandas, matplotlib, Jupyter
