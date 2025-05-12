# TASK1_ELEVATELABS
## 📌 Objective
The goal of this task was to clean and prepare a raw dataset (Netflix Movies and TV Shows)
## 🧹 Steps Performed

1. **Loaded the dataset** using Pandas.
2. **Handled missing values**:
   - Filled `director` and `cast` with `"Not Available"`.
   - Filled `country` with "unknown", `rating`, and `duration` with the **most frequent value (mode)**.
   - Dropped rows with missing `date_added` (only 10).
3. **Standardized text columns** (`type`, `country`, `rating`) by stripping spaces and applying consistent casing.
4. **Converted `date_added`** to proper datetime format using `pd.to_datetime()`.
5. **Verified and fixed data types** (e.g., `release_year` as integer, `date_added` as datetime).
