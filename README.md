# 🚨 Arrest Analysis of 19 Indian Cities (NCRB 2019)

## 📌 Objective
To explore and visualize arrest patterns across 19 Indian metropolitan cities in 2019, analyzing variations across **gender**, **age groups**, and **cities** using NCRB data.

---

## 🧾 Dataset Overview

| Attribute        | Detail                                           |
|------------------|--------------------------------------------------|
| **Source**       | NCRB (National Crime Records Bureau), India      |
| **Data**         | Table 19B.2 – Persons Arrested by Age and Gender |
| **Cities**       | 19 Metropolitan Cities                           |
| **Variables**    | Age groups, Gender, Juvenile/Adult status, City  |
| **Year**         | 2019                                             |

---

## 🛠️ Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- CSV file for raw data
- Markdown for documentation

---

## 🧹 Data Cleaning Summary

- Renamed long, inconsistent column headers
- Removed total summary row (`"Total of 19 Metropolitan Cities"`)
- Converted numeric columns to integers
- Set `'City'` as index for easier filtering
- Created new columns for visualization (e.g., total arrests per city)

---

## 📊 Visual Explorations

### 1️⃣ Total Arrests by City

![Total Arrests by City](./Total%20Arrests%20by%20City%20(2019).png)

> **Delhi**, **Chennai**, and **Mumbai** recorded the highest number of arrests.

---

### 2️⃣ Gender-Wise Arrest Distribution

![Gender-wise Arrest Distribution](./Gender-wise%20Arrest%20Distribution.png)

> **Males account for 94.5%** of all arrests, highlighting a strong gender skew.

---

### 3️⃣ Age Group Distribution by City

![Age Group Distribution](./Age%20Group%20Distribution%20of%20Arrests%20by%20City.png)

> The **18–30** age group consistently has the highest arrest rates across cities.

---

### 4️⃣ Heatmap of Age Group Arrests

![Heatmap](./Heatmap%20of%20Age%20Group%20Arrests%20by%20City.png)

> Delhi clearly dominates every age category; older age groups remain very low overall.

---

### 5️⃣ Top 10 Cities by Juvenile Arrests

![Top 10 Juvenile](./Top%2010%20Cities%20by%20Juvenile%20Arrests.png)

> **Delhi** again tops the list in juvenile arrests, followed by **Chennai** and **Mumbai**.

---

## 🔍 Key Findings

- **Delhi** has the highest arrests across all categories.
- **94.5% of arrests** are of **male individuals**.
- The **18–30 age group** consistently dominates arrest stats in every city.
- **Juvenile arrests** are relatively low, but cities like Delhi and Chennai show higher numbers.
- Some cities like **Ghaziabad** and **Kozhikode** have very low arrest counts.

---

## 🚀 Next Steps / Ideas for Extension

- 📊 Build an interactive dashboard using **Streamlit** or **Power BI**
- 📅 Add historical comparison (2018, 2020) if more years are available
- 🧠 Cluster cities based on gender-age patterns using **KMeans**
- 📝 Publish as a blog post or portfolio article

---

## 📁 Project Structure

NCRB-Arrest-Analysis/
├── data/
│ └── NCRB_CII-2019_Table_19B.2.csv
├── notebooks/
│ ├── 1_data_cleaning.ipynb
│ └── 2_visual_analysis.ipynb
├── charts/
│ └── (all .png visualizations)
├── README.md

---
