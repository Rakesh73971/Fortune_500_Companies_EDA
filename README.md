
# 📊 Fortune 500 Companies – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the Fortune 500 Companies dataset.

The goal is to analyze company performance, industry distribution, workforce size, and geographic spread using Python data analysis tools.

---

## 📂 Dataset Description

The dataset contains the following columns:

| Column Name | Description                            |
| ----------- | -------------------------------------- |
| Rank        | Company’s position in Fortune 500 list |
| Company     | Name of the company                    |
| Industry    | Industry sector                        |
| Revenue ($) | Annual revenue (in dollars)            |
| City        | City where company is located          |
| State       | State of company headquarters          |
| Zip         | Zip code                               |
| Website     | Official company website               |
| Employees   | Total number of employees              |
| CEO         | Chief Executive Officer                |

---

## 🛠️ Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Data Preprocessing

✔ Removed extra spaces from column names (e.g., `' City '` → `City`)
✔ Checked for missing values
✔ Verified data types
✔ Handled duplicates (if any)

Example:

```python
df.columns = df.columns.str.strip()
```

---

## 📊 Analysis Performed

### 1️⃣ Revenue Analysis

* Top revenue-generating companies
* Revenue distribution
* Industry-wise revenue comparison
* Revenue vs Employees relationship

### 2️⃣ Rank Analysis

* Revenue trends by rank
* Do top-ranked companies always have highest revenue?

### 3️⃣ Industry Analysis

* Number of companies per industry
* Largest industries by revenue
* Workforce distribution across industries

### 4️⃣ Geographic Analysis

* State-wise company distribution
* Top states with most Fortune 500 companies
* Revenue by state

### 5️⃣ CEO & Company Insights

* Unique CEO count
* Industry leadership distribution

---

## 📈 Visualizations Created

* Bar Charts – Industry & State distribution
* Histogram – Revenue distribution
* Scatter Plot – Revenue vs Employees
* Box Plot – Revenue by Industry
* Heatmap – Correlation analysis

---

## 📌 Key Insights

* A few industries dominate the Fortune 500 rankings.
* Revenue varies significantly across industries.
* States like California and Texas (if present in your analysis) host a high number of companies.
* Larger employee count does not always mean higher revenue efficiency.
* Rank correlates strongly with revenue.

---

## 📁 Project Structure

```
Fortune-500-EDA/
│
├── fortune500.csv
├── fortune_500_eda.ipynb
└── README.md
```

---

## 🚀 How to Run

1. Clone repository
2. Install requirements:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🎯 Skills Demonstrated

* Data Cleaning
* Pandas GroupBy & Aggregation
* Sorting & Ranking
* Correlation Analysis
* Business Insight Extraction
* Data Visualization

---
