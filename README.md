
# Task 1: Data Cleaning and Preprocessing

## Dataset: Mall Customer Segmentation Data (Kaggle)

### Objective
To clean and preprocess the raw dataset by handling missing values, duplicates, inconsistent formats, and incorrect datatypes.

### Steps Performed
1. **Removed duplicates** (CustomerID 5 duplicate removed).
2. **Handled missing values**: Filled missing Age values with the median (22).
3. **Standardized text values**: Gender column cleaned (all lowercase).
4. **Renamed columns**: Converted to lowercase, replaced spaces with underscores.
5. **Converted datatypes**: `customerid` and `age` converted to integer.

### Files in Repository
- `Mall_Customers_raw.csv` → Original raw dataset.
- `Mall_Customers_cleaned.csv` → Cleaned dataset ready for analysis.
- `data_cleaning.ipynb` → Jupyter notebook with cleaning code.
- `README.md` → Summary of the task.

### Tools Used
- Python (Pandas)
- Jupyter Notebook

---

**Author:** Nikita Shinde  
**Task:** Data Cleaning & Preprocessing  
