# In-depth-analysis-of-company-s-revenue

## Dataset used 
- <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/In-depth%20analysis%20of%20%20company's%20revenue.csv">Dataset</a>

## Project Overview
- <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/In-depth%20analysis%20of%20%20company's%20revenue%20Pproject.ipynb">In-depth-analysis-of-company-s-revenue</a>
----
## 📂 Dataset Description  
The dataset used in this project contains **valuable sales data**, categorized by **market segment** and **country/region**. These insights help in:  
- **Understanding company performance**  
- **Identifying growth opportunities**  
- **Making data-driven decisions**  

The dataset includes key metrics such as **sales figures, profit margins, and cost analysis**, providing a comprehensive view of business performance.
----

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

  -----
  ## 📊 Inside the Project  

### 🌍 Country-Wise Analysis  
- **USA and Canada** have the highest sales, while **Mexico** has the lowest. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Sales%20wise%20Country.png">View Chart</a>
- **Sales exceed COGS**, indicating profitability. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/COGS%20Sales%20By%20Country.png">View Chart</a>  
- **France (21%)** and **Germany (21.5%)** generate the highest profit, whereas **Mexico (17.3%)** has the least. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Country%20wise%20Profit.png">View Chart</a> 

### 🚴 Product-Wise Analysis  
- **'All-Terrain Bike'** and **'Yellow Bike'** have **negative gross margins**, while **'Speed Bike'** has a **low margin**. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Product%20wise%20sales.png">View Chart</a> 
- **'Touring Bike'** is the **most profitable**, whereas **'Mountain Bike'** has lower profit. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Product%20of%20Profit.png">View Chart</a> 
- **'Touring Bike'** also has the **highest sales**, while **'Road Bike'** has the **lowest**. <a href="">View Chart</a> 
- **'Touring Bike'** is the **best-selling product** in terms of units sold. <a href="">View Chart</a> 

### 🏢 Segment-Wise Analysis  
- The **Government sector** generates the **highest profit**, while **Midmarket** has the **least**. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Segment%20wise%20Profit.png">View Chart</a> 
- The **Enterprise sector** has **low profit margins** as **sales and COGS are nearly equal**. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Sales%20and%20COGS%20By%20Segment.png">View Chart</a> 
- The **Government sector** sells the most units, followed by **Midmarket**, while **Small Business** has the lowest. <a href="https://github.com/RohitKumar649/In-depth-analysis-of-company-s-revenue/blob/main/Units%20Sold%20by%20segment%20.png">View Chart</a>
- ----
## Technologies Used
- 🐍 Python
- 📊 Pandas, NumPy
- 📉 Matplotlib, Seaborn
- 💾 Jupyter Notebook


