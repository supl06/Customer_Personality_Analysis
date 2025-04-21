# Customer Personality Analysis - Data Cleaning & Preprocessing

##  Introduction
For the given Kaggle dataset on Customer Personality Analysis, I performed **data cleaning and preprocessing**.  
The goal of this task was to clean and prepare the raw dataset for further analysis or machine learning by handling missing values, duplicates, inconsistent formats, and standardizing data types.

---

##  Technical
- **Language:** Python  
- **File Type:** `.ipynb` (Jupyter Notebook)

---

##  Task: Data Cleaning & Preprocessing

###  Steps Performed:

1. **Loaded dataset** from the URL:  
   `https://raw.githubusercontent.com/arienugroho050396/Customer-Personality-Analysis/main/marketing_campaign.csv` using a tab separator.

2. **Handled missing values**:  
   - Identified 24 missing values in the `Income` column.
   - Imputed these missing values using the **median** of the `Income` column.

3. **Removed duplicates**:  
   - Checked and removed duplicate rows using `drop_duplicates()`.

4. **Standardized column names**:  
   - Renamed all column headers to lowercase and replaced spaces with underscores for consistency.

5. **Formatted date column**:  
   - Converted the `Dt_Customer` column to proper `datetime` format.

6. **Checked and fixed data types**:  
   - Ensured that numerical and date columns have the correct data types (e.g., `Income` as float, `Dt_Customer` as datetime).

7. **Standardized text columns**:  
   - Cleaned and standardized values in columns like `Education` and `Marital_Status` for consistency (e.g., removing extra spaces or casing issues if any).

---

##  Data Fields Overview

###  People

| Variable Name | Description |
|---------------|-------------|
| ID | Customer's unique identifier |
| Year_Birth | Customer's birth year |
| Education | Customer's education level |
| Marital_Status | Customer's marital status |
| Income | Customer's yearly household income |
| Kidhome | Number of children in customer's household |
| Teenhome | Number of teenagers in customer's household |
| Dt_Customer | Date of customer's enrollment with the company |
| Recency | Number of days since customer's last purchase |
| Complain | 1 if customer complained in the last 2 years, 0 otherwise |



##  Summary of Changes
- 24 missing income values imputed using the **median**
- Duplicates removed
- Columns renamed to be lowercase with underscores
- Dates converted to `datetime` format
- Data types verified and corrected
- Text values standardized

