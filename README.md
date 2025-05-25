# 🌍 World Happiness Report – Data Analytics Project

This project explores and analyzes the **2017 World Happiness Report**, aiming to uncover global trends and factors that influence happiness. Using powerful Python libraries, we cleaned, analyzed, and visualized key insights from the dataset.

---

## 📌 Project Objective

To understand what makes countries happier by analyzing attributes like GDP per capita, health, social support, and freedom. This project walks through essential steps of the data analytics pipeline, from cleaning to visualization.

---

## 📁 Dataset Overview

The dataset, compiled by the **United Nations Sustainable Development Solutions Network**, evaluates countries based on:

- GDP per capita
- Healthy life expectancy
- Social support
- Trust in government/business
- Freedom to make life choices
- Generosity
- Dystopia (baseline index)

Each country is ranked by a composite Happiness Score.

---

## 🧠 Analytics Workflow & Features

### 1️⃣ Cleaning and Handling Missing Values
- Removed or imputed `NaN` values
- Checked for completeness using `.info()` and `.isnull()`
- Verified dataset quality before proceeding

### 2️⃣ Feature Selection and Engineering 
- Chose relevant features impacting happiness
- Created new variables (e.g., log GDP)
- Removed redundant columns

### 3️⃣ Ensuring Data Integrity and Consistency
- Validated data types and corrected mismatches
- Removed duplicates
- Standardized formats and scales

### 4️⃣ Summary Statistics and Insights
- Used `.describe()` to summarize data
- Highlighted key metrics and outliers
- Compared happiness scores regionally

### 5️⃣ Identifying Patterns, Trends, and Anomalies 
- Analyzed correlation matrix and heatmaps
- Identified countries with anomalous scores
- Found trends among top and bottom performers

### 6️⃣ Handling Outliers and Data Transformations 
- Detected extreme values via Z-score and boxplots
- Normalized skewed data (e.g., log-transform)
- Improved data quality and model-readiness

### 7️⃣ Initial Visual Representation of Key Findings 
- Used `matplotlib` and `seaborn` for charts
- Presented bar plots, scatter plots, and histograms
- Visualized happiness by region, GDP, and trust

---

## 📦 Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/world-happiness-report
cd world-happiness-report
jupyter notebook
