# Project 1: Data Cleaning & Preparation
**Program:** DecodeLabs Data Analytics Internship 2026

## Overview
This project involves cleaning and preparing a raw order records dataset 
to make it ready for business analysis. The raw data contained missing values, 
inconsistent formats, and required standardization across multiple columns.

## Dataset
- **File:** Dataset_for_Data_Analytics.xlsx
- **Size:** 1,200 rows × 14 columns
- **Content:** Customer order records including products, prices, dates, and shipping info

## What Was Done
The cleaning process was completed in three phases:

- **Phase 1:** Handled 309 missing values in the CouponCode column by filling 
them with "NO_COUPON" to explicitly indicate no coupon was applied
- **Phase 2:** Audited the dataset for duplicate records. Zero duplicates found.
- **Phase 3:** Standardized all formats, dates converted to ISO 8601 (YYYY-MM-DD), 
whitespace trimmed from all text columns, and monetary columns rounded to 2 decimal places

## Tools Used
- Python 3.14.5
- pandas
- openpyxl
- Jupyter Notebook (VS Code)

## Files in this Repository
| File | Description |
|------|-------------|
| `Dataset_for_Data_Analytics.xlsx` | Original raw dataset |
| `Cleaned_Orders_Dataset.xlsx` | Final cleaned output |
| `cleaning.ipynb` | Annotated Jupyter notebook with all cleaning steps |
| `Change_Log.pdf` | Official change log documenting every modification made |

## Outcome
All 1,200 records preserved with zero data loss. Dataset passes all 
verification gates, zero duplicate OrderIDs and zero incorrectly formatted dates.
