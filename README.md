# 🧹 Cleaning and structuring operational data from municipal inspections in Miami-Dade: from raw to usable

**Status**: Completed | **Type**: Data Cleaning + Preparation for Analysis  
**Tools**: Pandas, , Google Colab  

---

## 🧠 Project Overview

This project focuses on cleaning and structuring raw municipal inspection data from Miami-Dade County. The dataset includes over 7800 inspections performed by 82 inspectors over the course of one week. The goal was to prepare the data for analysis by eliminating inconsistencies, standardizing values, and creating structured categories that can be used in visualizations, dashboards, and predictive models.

---

## 🎯 Objectives

- Remove or correct inconsistent and duplicate records  
- Standardize and format key variables (e.g. inspector names, results, categories)  
- Group detailed inspection types into functional categories
- Integrate data from a Google API to obtain missing data  
- Prepare a clean DataFrame ready for exploratory data analysis (EDA)  
- Lay the foundation for business reporting and future machine learning  

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `cleaning_inspections.ipynb` | Main notebook with all cleaning steps explained |
| `geocoding-public.ipynb` | Technical notebook explaining the geocoding process through an API |
| `Inspections.csv` | Original dataset with raw data |
| `solo_address.csv` | Dataset with the exported address column |
| `addresss_ZIP.csv` | Dataset obtained with the API containing addresses and zip codes |
| `inspections-cleaned.csv` | Final dataset after data cleaning |
| `.gitignore` | Ignores temporary and raw files (e.g. `.csv`, `__pycache__`, etc.) |
| `LICENSE` | MIT license |
| `README.md` | You are here! |

---

## 🧼 Key Cleaning Steps

- Dropped irrelevant or empty columns  
- Standardized inspector names and formatted addresses  
- Grouped 45 inspection descriptions into 11 core categories
- Getting missing values in addresses through the use of an API
- Removed or corrected outliers in `disp_description` and `inspection_description`  
- Created a clean and fully documented DataFrame `inspections-cleaned.csv`

---


## 💡 Why This Matters

Having a clean and structured dataset enables:
- Accurate EDA and KPI generation  
- Fair performance comparisons across inspectors  
- Better reporting for management and public records  
- A foundation for predictive analytics (e.g. inspection outcomes)
- Inspection behavior and results across the county (using zip codes)

---

## 🔗 Future Steps

This project sets the foundation for:

- **Project 2**: Statistical analysis with explanatory capacity and study of rejection rates by inspector, by area, and by type of permit.
- **Project 3**: `A/B` testing and hypothesis testing across inspection groups  
- **Project 4**: Interactive dashboard with KPIs in Power BI.

---

## 🧑‍💻 About the Author

**Frank Gamboa**  
Jr. Data Analyst | Mathematician & Statistician  
[LinkedIn](https://www.linkedin.com/in/frank-gamboa) • Miami, FL

---

## 🚀 How to Use This Project

1. Clone the repository  
2. Open `cleaning_inspections.ipynb`  
3. Follow along or adapt the cleaning pipeline for your own inspection data
