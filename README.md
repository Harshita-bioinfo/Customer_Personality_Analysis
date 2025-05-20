

# Customer Personality Analysis: Data Preprocessing & Visualization

## 📊 Overview

This project demonstrates the **preprocessing and exploratory visualization of marketing campaign data**. The objective is to clean, preprocess, and visualize customer personality data to derive meaningful insights for business decisions.

The workflow includes data cleaning, feature engineering, and exploratory data analysis (EDA) through various visualizations (boxplots, heatmaps, pie charts, etc.).

---

## 📁 Repository Contents

| File Name                               | Description                                                                 |
|-----------------------------------------|-----------------------------------------------------------------------------|
| `marketing_data_preprocessing.ipynb`    | Jupyter Notebook for cleaning and preprocessing the raw marketing data.     |
| `marketing_data_visualization.ipynb`    | Jupyter Notebook for performing EDA and visualizing customer insights.      |
| `marketing_data.csv`            | Input CSV file containing the raw marketing dataset.  |
| `cleaned_marketing_data.csv`            | Output CSV file containing the cleaned and preprocessed marketing dataset.  |
| `cleaned_marketing_data_summary.txt`    | Text summary of all cleaning steps performed and final dataset columns.     |
| `README.md`                             | Documentation file for this project workflow.                               |

---

## 🎯 Objectives

- Perform data cleaning and preprocessing on customer marketing campaign data.
- Handle outliers, missing values, and standardize inconsistent entries.
- Engineer new features for time-based and categorical analysis.
- Visualize customer segments, spending habits, and campaign responses through EDA.

---

## 🛠️ Tools Used

- **Python 3.10+**
- **Jupyter Notebook (Google Colab or Local Jupyter)**
- **Pandas, NumPy, Matplotlib, Seaborn**

---

## ✅ Step-by-Step Procedure

### 🔹 Step 1: Data Cleaning & Preprocessing
- File Used: `marketing_data_preprocessing.ipynb`
- Key tasks performed:
  - Outlier detection and capping (IQR method).
  - Handling missing values and removing redundant columns.
  - Standardizing categorical anomalies.
  - Date transformation & feature extraction (`Year`, `Month`, `Period`, `Day`).
  - Dropping low-variance or non-informative columns.
- Result: Cleaned dataset saved as `cleaned_marketing_data.csv`.
- Summary of preprocessing steps in `cleaned_marketing_data_summary.txt`.

### 🔹 Step 2: Data Visualization & EDA
- File Used: `marketing_data_visualization.ipynb`
- Key visualizations performed:
  - Distribution plots, count plots, and histograms.
  - Correlation heatmaps.
  - Spending pattern analysis with bar and pie charts.
  - Customer segmentation visualized through boxplots and scatter plots.
- Insights extracted for marketing strategy refinement.

---

## 🔍 Results Summary

- Data cleaned to eliminate outliers and inconsistencies.
- Key customer groups identified based on income, family size, and product purchases.
- Spending patterns visualized across product categories.
- Visual cues for campaign response and visit frequency derived.

---

## 🔁 How to Reproduce

1. Clone this repository:
   ```bash
   git clone https://github.com/Harshita-bioinfo/Customer_Personality_Analysis.git
   cd Customer_Personality_Analysis
   ```

2. Install necessary Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

3. Run the preprocessing notebook:
   - Open `marketing_data_preprocessing.ipynb` in Jupyter or Colab.
   - Execute all cells to generate `cleaned_marketing_data.csv`.

4. Run the visualization notebook:
   - Open `marketing_data_visualization.ipynb`.
   - Execute all cells to view EDA visualizations and insights.

---

## 🔄 Workflow Summary

The workflow follows a standard **Data Science pipeline**:

1. Data Loading → Cleaning → Feature Engineering
2. Exploratory Data Analysis (EDA)
3. Insight Derivation & Visualization

