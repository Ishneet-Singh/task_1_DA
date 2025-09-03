# task_1_DA
Data cleaning and preprocessing of a marketing campaign dataset using Python (pandas). Includes handling missing values, removing duplicates, standardizing text, formatting dates, and fixing data types.
# Marketing Campaign Data Cleaning

This project demonstrates **data cleaning and preprocessing** on a marketing campaign dataset using **Python (pandas)**.  
The goal is to prepare raw data for **exploratory data analysis (EDA)** and potential **machine learning applications**.

---

## 📌 Dataset
The dataset (`marketing_campaign.csv`) contains customer information such as demographics, education, marital status, spending, and campaign responses.  

Key columns include:
- `Year_Birth`
- `Education`
- `Marital_Status`
- `Income`
- `Dt_Customer`
- Various product spending features

---

## 🔧 Data Cleaning & Preprocessing Steps
The following steps were performed:

1. **Handle Missing Values**
   - Identified using `.isnull()`
   - Imputed or removed as necessary

2. **Remove Duplicates**
   - Used `.drop_duplicates()` to ensure unique records

3. **Standardize Text Values**
   - Unified categories (e.g., `Married`, `Together`)
   - Standardized gender, education, and country names

4. **Format Dates**
   - Converted `Dt_Customer` to proper `datetime` type (`dd-mm-yyyy`)

5. **Rename Columns**
   - Cleaned column headers to lowercase with underscores (e.g., `marital_status`)

6. **Fix Data Types**
   - `Income` → numeric
   - `Dt_Customer` → datetime
   - `Education`, `Marital_Status` → categorical
   - Added new column `Age` derived from `Year_Birth`

---

## 🚀 Tech Stack
- **Python 3**
- **pandas**
- **NumPy**

---



