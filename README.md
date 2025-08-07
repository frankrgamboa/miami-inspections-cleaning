# 🧹 Miami-Dade Inspections Cleaning

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
- Prepare a clean DataFrame ready for exploratory data analysis (EDA)  
- Lay the foundation for business reporting and future machine learning  

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `cleaning_miami_dade.ipynb` | Main notebook with all cleaning steps explained |
| `.gitignore` | Ignores temporary and raw files (e.g. `.csv`, `__pycache__`, etc.) |
| `LICENSE` | MIT license |
| `report_summary.pdf` *(optional)* | Executive summary with charts and commentary |
| `README.md` | You are here |

---

## 🧼 Key Cleaning Steps

- Dropped irrelevant or empty columns  
- Standardized inspector names and formatted addresses  
- Grouped over 100+ inspection descriptions into 14 core categories  
- Removed or corrected outliers in `result` and `classification`  
- Created a clean and fully documented DataFrame: `Df_def`

---

## 📊 Sample Outcome (preview)

> *[Insert 1–2 images or tables if using `report.pdf`]*  
> Example: Distribution of results by inspector | Outlier detection in rejection rates

---

## 💡 Why This Matters

Having a clean and structured dataset enables:
- Accurate EDA and KPI generation  
- Fair performance comparisons across inspectors  
- Better reporting for management and public records  
- A foundation for predictive analytics (e.g. inspection outcomes)

---

## 🔗 Future Steps

This project sets the foundation for:

- **Project 2**: Statistical analysis and outlier detection in rejection rates  
- **Project 3**: A/B testing and hypothesis testing across inspection groups  
- **Project 4**: Interactive dashboard with KPIs in Power BI or Streamlit

---

## 🧑‍💻 About the Author

**Frank Gamboa de la Paz**  
Junior Data Analyst | Mathematician with specialization in statistics  
[LinkedIn](https://www.linkedin.com/in/frankgamboa) • Miami, FL

---

## 🚀 How to Use This Project

1. Clone the repository  
2. Open `cleaning_miami_dade.ipynb`  
3. Follow along or adapt the cleaning pipeline for your own inspection data
