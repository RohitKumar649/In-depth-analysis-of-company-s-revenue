# In-depth-analysis-of-company-s-revenue

## Dataset used 
- <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/In-depth%20analysis%20of%20%20company's%20revenue.csv">Dataset</a>

## Project Overview
- <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/In-depth%20analysis%20of%20%20company's%20revenue%20Pproject.ipynb">In-depth-analysis-of-company-s-revenue</a>

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


