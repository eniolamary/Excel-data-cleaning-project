# 📊 Excel Data Cleaning Project (Retail Dataset)

## Introduction

This project focuses on cleaning and preparing a raw retail dataset using Microsoft Excel.  
The dataset initially contained several data quality issues such as missing values, duplicate records, inconsistent formatting, and incorrect calculations.

The goal of this project was to transform the raw dataset into a clean, structured, and analysis-ready format suitable for business insights and reporting.

---

## 2. Data Cleaning Process

To improve data quality and ensure accuracy, the following cleaning steps were performed:

- **Standardized data types**
  - Columns were converted into appropriate formats such as text, numeric, and date fields to ensure consistency in calculations and analysis.

- **Unified inconsistent values**
  - Standardized variations in categorical fields such as product categories, payment methods, and location names to maintain uniformity across the dataset.

- **Handled missing values**
  - Replaced non-critical missing values with `"Unknown"` where appropriate to preserve data integrity.
  - Estimated or reconstructed missing values where logical relationships allowed (e.g., deriving totals from available fields).

- **Removed duplicate records**
  - Identified and eliminated duplicate entries to prevent inflated or misleading analysis results.

- **Corrected calculation errors**
  - Recomputed incorrect values using business logic:
    - **Total Spent = Price × Quantity**

- **Removed unrecoverable records**
  - Rows with critical missing information that could not be logically or accurately reconstructed were dropped.

---

## 3. Handling Missing Values Strategy

Missing data was treated based on the importance of each field and its role in analysis:

- **Item names:** Replaced with `"Unknown"` when missing
- **Price or Quantity:** Recalculated where possible using related fields
- **Non-recoverable records:** Removed if multiple essential fields were missing
- **Total Spent:** Rows with missing or incorrect values that could not be derived were dropped

This approach ensured a balance between data completeness and analytical accuracy.

---

## 4. Data Validation & Quality Checks

After cleaning, several validation checks were performed to ensure data reliability:

- Verified that **Total Spent = Price × Quantity** across all records
- Checked for **negative, zero, or unrealistic values**
- Ensured consistency in categorical fields (e.g., product types, locations, payment methods)
- Validated date formats and ensured values fell within expected ranges
- Performed a final scan for duplicate and missing values

These checks ensured that the dataset was fully consistent and ready for analysis.

---

## 5. Conclusion

The dataset was successfully transformed from a raw and inconsistent format into a clean, structured, and analysis-ready dataset.

This cleaning process improved:
- Data accuracy
- Consistency
- Reliability
- Usability for business decision-making

The cleaned dataset now provides a strong foundation for further analysis, visualization, and insight generation.

---
