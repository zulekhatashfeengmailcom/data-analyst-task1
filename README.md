# Task 1 - Data Cleaning and Preprocessing

## 📌 Objective
Clean and prepare a raw dataset by handling nulls, duplicates, inconsistent formats, and incorrect data types.

## 📂 Dataset Used
**Mall Customer Segmentation Data** (sampled).

- Raw file: `data/mall_customers.csv`
- Cleaned file: `data/mall_customers_cleaned.csv`

## 🛠 Cleaning Steps
1. **Missing Values**  
   - Dropped rows with missing `CustomerID`  
   - Filled numeric columns with mean values  

2. **Duplicates**  
   - Removed duplicate rows  

3. **Standardization**  
   - Converted `Gender` values into lowercase (`male`, `female`)  

4. **Renaming Columns**  
   - `Annual Income (k$)` → `annual_income_k`  
   - `Spending Score (1-100)` → `spending_score`  

5. **Data Types**  
   - Ensured `CustomerID`, `Age`, `annual_income_k`, `spending_score` are integers  

## 📊 Deliverables
- ✅ Cleaned dataset ready for analysis
- ✅ Python script (`src/clean_data.py`)
- ✅ Notebook (`notebook/data_cleaning.ipynb`)

## 🚀 How to Run
```bash
# Run script
python src/clean_data.py
```

## ✨ Summary
The raw dataset had missing values, duplicates, inconsistent gender labels, and messy column names.  
After preprocessing, the cleaned dataset is structured, standardized, and analysis-ready.
