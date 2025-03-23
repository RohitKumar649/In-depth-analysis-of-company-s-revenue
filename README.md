# In-depth-analysis-of-company-s-revenue

# Financial Data Cleaning Project

## Overview
This project focuses on cleaning and preprocessing a financial dataset using Python and Pandas. The dataset includes sales, discounts, and profit data across different segments, countries, and products. The goal is to ensure data accuracy, consistency, and readiness for further analysis.

## Dataset
- The dataset contains 700 rows and 16 columns.
- Key columns include `Segment`, `Country`, `Product`, `Discount Band`, `Units Sold`, `Manufacturing Price`, `Sale Price`, `Gross Sales`, `Discounts`, `Sales`, `COGS`, `Profit`, and `Date`.

## Cleaning Steps
1. **Handling Column Name Issues**
   - Removed leading and trailing spaces.
   - Standardized column names for consistency.

2. **Handling Missing and Incorrect Values**
   - Verified missing values (`df.isnull().sum()`).
   - Replaced `-` in `Discounts` and `Profit` columns with `0`.

3. **Data Type Corrections**
   - Removed `$` and `,` from numerical columns.
   - Converted numerical columns to appropriate data types (`float64`).
   - Converted `Date` column to `datetime` format.

4. **Dropping Unnecessary Columns**
   - Dropped `Month Name`, `Month Number`, and `Year` as they can be derived from the `Date` column.

5. **Standardizing Product Names**
   - Mapped product names to meaningful names (e.g., `Carretera` → `Road Bike`).

## Results
- The dataset is now cleaned and structured for further analysis.
- All numerical columns are in the correct format.
- The `Date` column is now a `datetime` object.
- Unnecessary columns have been removed.
