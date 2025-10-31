# 🛩️ Aircraft Safety Analysis — Phase 1 Project

Welcome to the **Aircraft Safety Analysis Project**, conducted as part of Phase 1 of the Data Science Bootcamp. This repository contains the exploratory data analysis (EDA), visualizations, insights, and recommendations based on aviation incident data. The goal of this project was to guide a business seeking to diversify into aviation by providing data-driven insights into risk exposure, model safety performance, and strategic procurement considerations.

---

## 🧭 Overview

This project leverages Aviation_Data.csv to uncover patterns in aircraft safety and identify risk factors across manufacturers and aircraft types. The key objective is to **support business strategy and procurement decisions** in aviation by:

- Understanding accident trends over time
- Evaluating performance of top aircraft models
- Quantifying injury severity across manufacturers
- Supporting operational decisions using visual analytics

---

## 💼 Business Understanding

### 👥 Stakeholder
A business expanding into the aviation sector, particularly interested in **procurement strategy** and **operational risk**.

### ❓ Key Business Questions

1. What aircraft types (make + model) are most frequently involved in accidents?
2. How do accident trends vary by year and aircraft category?
3. Which aircraft models show the highest rates of serious injuries or fatalities?
4. What recommendations can reduce risk exposure during fleet expansion?

---

## 📊 Data Understanding and Analysis

### 🔍 Source of Data

- **Dataset**: U.S. NTSB Aviation Accident Database
- **Format**: CSV file
- **Columns Used**: Event Date, Aircraft Make, Model, Category, Injury Severity, etc.

### 📦 Description of Data

The dataset comprises over 83,000 accident records from various countries, spanning more than 30 columns, covering aircraft specifications, incident details, weather conditions, and outcomes (injuries/fatalities).

Key preprocessing steps included:

- Cleaning null values in injury columns
- Creating a combined `Make_Model` identifier
- Grouping and summarizing data for visualization
- Filtering top 15 aircraft types for relevance

---

### 📈 Visualizations

#### 1. Accidents by Year  
This bar chart shows annual accident counts to help understand **overall industry trends** and external risk factors.

![Accidents by Year](accidents_by_year.png)

---

#### 2. Top 15 Aircraft by Accident Count  
This horizontal bar chart ranks aircraft by accident frequency, helping prioritize **risk assessments** in procurement.

![Top 15 Aircraft by Accident Count](top15_aircraft_accidents.png)

---

#### 3. Injury Severity Distribution (Top 15 Aircraft)  
A stacked bar chart comparing fatalities, serious injuries, minor injuries, and uninjured across top aircraft models.

![Injury Severity Distribution](injury_distribution_top15_aircraft.png)

---

## ✅ Conclusion

### Key Findings

1. **Cessna models** (especially 172 and 182) show high accident frequency but a relatively higher number of uninjured outcomes — suggesting they are safer within light aircraft classes.
2. **Homebuilt or amateur-built aircraft**, including experimental models, show **significantly higher injury severity**, making them a **procurement risk**.
3. Accident counts have **declined over time**, but certain commercial categories (e.g., multi-engine land aircraft) still pose systemic risks requiring robust safety checks.

---

## 📌 Final Recommendation

For aviation diversification, the business should:

- **Favor certified light aircraft** (e.g., Cessna 172) for initial fleet acquisition.
- **Avoid experimental/amateur-built models**, especially those with high fatality-to-accident ratios.
- Use trend data to **inform insurance modeling and pilot training priorities**, especially for high-risk models.

---

> 🚀 *All visualizations, Jupyter Notebook code, and this README are hosted in this repository. Explore `student.ipynb` for full analysis.*
