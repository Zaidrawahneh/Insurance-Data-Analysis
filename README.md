# Project: Insurance Data Analysis

## 📝 Introduction
This project is an exploratory analysis of insurance data from Kaggle with the goal of understanding the key factors that influence medical insurance costs. The analysis specifically focuses on answering the question: **Does smoking affect medical insurance costs?**

## 📊 Data Source
The following dataset from Kaggle was used: [https://www.kaggle.com/datasets/mosapabdelghany/medical-insurance-cost-dataset?resource=download]

## 🛠️ Tools Used
- **ACL Desktop Application**
- **GitHub**

---

## 🔍 Analysis Process

### Step 1: Data Import
I imported the `insurance.csv` file into ACL, where the raw data was displayed.

<p align="center">
  <img src="https://raw.githubusercontent.com/Zaidrawahneh/Insurance-Data-Analysis/4c5b02e37120f5d2666bc3cc7769e4c3ac394084/1GIT.png">
</p>

### Step 2: Data Quality Check
Before starting the analysis, I checked the data quality in the **`smoker`** and **`charges`** columns.
- Using the `Classify` command, I confirmed that the `smoker` column does not contain incorrect values.

<p align="center">
  <img src="https://github.com/Zaidrawahneh/Insurance-Data-Analysis/blob/main/Classify.png?raw=true">
</p>

- Using the `Profile` command, I confirmed that the `charges` column contains only numeric data, which is essential for performing calculations.

<p align="center">
  <img src="https://github.com/Zaidrawahneh/Insurance-Data-Analysis/blob/main/profile.png?raw=true
">
</p>

### Step 3: Simplify the Data
To make the analysis faster and more focused, I created a new table using the `Extract` command in ACL. This table contains only the **`smoker`** and **`charges`** columns, which are the two key variables for this analysis.

<p align="center">
  <img src="https://github.com/Zaidrawahneh/Insurance-Data-Analysis/blob/main/extract.png?raw=true">
</p>

### Step 4: Analysis and Cost Comparison
To answer my research question, I used the `Summarize` command in ACL to compare the average insurance costs between smokers and non-smokers.

<p align="center">
  <img src="https://github.com/Zaidrawahneh/Insurance-Data-Analysis/blob/main/Avg.png?raw=true">
</p>

---

## 💡 Key Findings

The analysis showed that the average insurance cost for smokers is **$32,050.23**, while the average cost for non-smokers is **$8,434.29**.

**Conclusion:**
This analysis confirms that smoking is a significant factor in medical insurance costs, as smokers pay nearly four times more than non-smokers.

## 🚀 Future Steps
This analysis can be expanded to explore other questions, such as:
- The relationship between BMI and insurance costs.
- The effect of age and number of children on insurance costs.
