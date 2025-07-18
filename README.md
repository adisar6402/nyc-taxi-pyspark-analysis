# 🚕 NYC Taxi Data Analysis with PySpark

A mini project for analyzing New York City taxi trip data using **PySpark**, simulating a **Databricks** environment via **Google Colab**. The project showcases data engineering, cleaning, analysis, and visualization techniques for large-scale datasets.

---

## 📌 Project Overview

**Goal:** Analyze a sample of NYC Taxi trip and fare data to extract insights about trip duration, payment types, peak hours, and fare trends.

**Tools Used:**
- PySpark (on Colab)
- Pandas
- Matplotlib / Seaborn (optional)
- Git & GitHub

---

## 🧹 Data Pipeline Steps

### ✅ Step 1: Environment Setup
- Simulated Azure Databricks using Google Colab
- Generated mock CSV data for `trip_data` and `trip_fare`

### ✅ Step 2: Data Loading
- Loaded CSVs into PySpark DataFrames
- Explored schema, sample rows, and null/missing values

### ✅ Step 3: Data Cleaning
- Simulated datetime and distance columns
- Removed invalid entries
- Created new column: `trip_duration`

### ✅ Step 4: Data Joining
- Joined `trip_data` and `trip_fare` on a dummy `medallion` key

### ✅ Step 5: Data Analysis
- Average trip duration and fare amount
- Most popular payment method
- Peak taxi trip hours

### ✅ Step 6: Visualization
- Trip distribution by hour (peak hours)
- Payment type breakdown
- Scatter plot of fare vs. distance

### ✅ Step 7: Output & Reporting
- Saved key results as CSV files
- Simulated Azure Blob Storage upload
- Created this summary report

---

## 📂 Output Files

| Filename                        | Description                             |
| ------------------------------ | --------------------------------------- |
| `peak_hours.csv`               | Hourly distribution of taxi trips       |
| `payment_type_distribution.csv`| Count of trips per payment type         |
| `trip_distance_vs_fare.csv`    | Data for scatter plot of fare vs. distance |
| `Abdulrahman_Adisa_Amuda_of_module_6_mini_project.ipynb` | Complete notebook |

---

## ✅ Results Summary

- ⏱️ Average trip duration: ~15 minutes (simulated)
- 💰 Fare increases with distance
- 🕔 Peak Hours: 5 PM – 7 PM
- 💳 Most used payment: **Credit Card**

---

## 📥 Usage

```bash
git clone https://github.com/<your-username>/nyc-taxi-pyspark-analysis.git
cd nyc-taxi-pyspark-analysis
