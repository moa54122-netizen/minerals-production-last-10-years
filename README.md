# 🪨 Global Minerals Production & Refining Dashboard

An end-to-end analysis of the production and refining of the top 24 minerals worldwide — built by cleaning and structuring the data with SQL, transforming it with Power Query, and modeling and visualizing it in Power BI.

---

## 📌 Project Overview

This project delivers an interactive analysis of global mineral production, reserves, demand, and pricing from 2015 to 2026, highlighting the leading producing countries, market trends, and supply-chain disruptions.

## 🎯 Objectives

- Identify the most produced and most in-demand minerals globally.
- Determine which countries have the greatest influence on the minerals market in terms of production and reserves.
- Highlight the highest-value minerals by price.
- Track demand growth over the years and compare it against production and reserves.
- Analyze supply-chain disruptions by year, country, and mineral.

---

## 🛠️ Workflow

### 1. Data Cleaning & Structuring (SQL)
- Split and filtered the raw data using SQL to prepare clean, transformation-ready tables.

### 2. Transformation (Power Query)
- Imported the cleaned data and applied additional transformation steps (column adjustments, table merges, handling missing values, etc.).

### 3. Data Modeling
- Built a data model schema in Power BI to establish relationships between tables (minerals, countries, years).

### 4. Calculations (DAX Measures)
- Created the required measures and calculations (Overall Fortune, Production, Reservation, Demand Growth, etc.) using DAX.

### 5. Dashboard & Insights
- Designed multiple interactive pages, each answering a different analytical question.

---

## 📊 Dashboard Pages

| Page | Content |
|---|---|
| **Summary** | Top 9 key insights from across the dashboard |
| **Overview** | High-level KPIs: overall fortune, production, reservation, mineral count, producing countries, top-priced minerals |
| **By Year** | Price, production, and refining trends over time (2015–2026) |
| **By Country** | Production, reserves, and number of minerals produced per country |
| **Mineral Fortune** | Market value of minerals by year and by country |
| **Demand Growth** | Demand growth by year and by country |
| **Disruption** | Supply-chain disruption analysis by year/country/mineral |

---

## 🔑 Key Insights

1. **Manganese and Copper** are the most produced minerals.
2. **Graphite, Manganese, Cobalt, and Nickel** show the highest demand growth.
3. **Platinum and Palladium** have by far the highest prices among all minerals.
4. **China** has the greatest diversity of minerals produced (around 20 minerals).
5. **Reserve levels far exceed current production** volumes.
6. **China** is the most dominant country in the minerals market (production and refining).
7. **South Africa** has the highest production and reserve amounts.
8. **Chile** is the richest country in terms of total mineral market value (Mineral Fortune).
9. **Africa** is the continent that imports the most minerals.

### Key Figures
- 💰 Overall Fortune: **173.87 trillion**
- ⛏️ Overall Production: **936.87 million tons**
- 🛡️ Overall Reservation: **31 billion tons**
- 🔢 Minerals Tracked: **24** (including **7** rare minerals)
- 🌍 Producing Countries: **35**
- ⚠️ Total Recorded Disruptions: **71**, the majority occurring in **2021** (57 disruptions)

---

## 🧰 Tools Used

- **SQL** – Data cleaning, structuring, and filtering
- **Power Query** – Data transformation
- **Power BI (Data Model + DAX)** – Relationship modeling and analytical measures
- **Power BI Desktop** – Interactive dashboard design

---

## 👤 Author

Prepared as part of a data analysis project using SQL and Power BI.

---

*Last updated: August 2026*
