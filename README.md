# Data Cleaning – Marketing Campaign Dataset

This project is part of Elevate Lab's data analysis training.  
The objective was to clean and prepare a raw dataset that contained missing values, inconsistent formatting, and other common data quality issues.

---

## ✅ Objective:
Clean and prepare a raw dataset (`marketing_campaign.csv`) for analysis by:
- Handling missing values
- Ensuring consistency in formatting
- Removing redundant or unhelpful data
- Preparing the dataset for further analysis

---

## 🔧 Cleaning Steps Done:

1. **Separated columns** – The original dataset had all data in a single column. I split it into proper columns using text-to-columns in Excel.
2. **Validated categorical values** – Applied data validation to `Marital_Status` and `Education` columns to ensure clean input.
3. **Added new column** – Created `Total_Children` = `Kidhome` + `Teenhome` to summarize children at home.
4. **Handled date formatting** – Standardized inconsistent date alignments in the file.
5. **Dropped constant-value columns** – Removed `Z_Revenue`, `Z_CostContact`, and `Complain` because their values didn’t vary.
6. **Handled missing income values** – Replaced missing values in `Income` column using the **Median**.
7. **Replaced blanks** – Replaced blank or special missing entries with `"Missing"` text label.

---

## 📁 Files Included:

- `marketing_campaign.csv`: Cleaned version of the dataset

---

## 🧠 Tools Used:
- Microsoft Excel

---

## 🧩 Next Steps:
This cleaned dataset is now ready for exploration and analysis.
