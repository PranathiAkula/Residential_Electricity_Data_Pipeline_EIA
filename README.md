# Residential_Electricity_Data_Pipeline_EIA

# ⚡ Residential Electricity Consumption Analysis (EIA API)

## 📌 Overview

This project analyzes **U.S. residential electricity consumption trends** using publicly available data from the U.S. Energy Information Administration (EIA) API.

The objective is to build a **data extraction, cleaning, and exploratory analysis workflow** to uncover patterns in electricity usage across time and geography.

---

## 🎯 Objective

* Analyze historical electricity consumption trends
* Identify seasonal and regional patterns
* Prepare structured data for downstream analytics or forecasting

---

## 📊 Data Source

* Source: U.S. Energy Information Administration (EIA) Open Data API
* Dataset: Electricity Retail Sales
* Frequency: Monthly
* Sector: Residential

---

## ⚙️ Tech Stack

* Python
* Pandas
* Requests (API integration)
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Extraction

* Retrieved data from EIA API using Python
* Parsed JSON response into tabular format

### 2. Data Cleaning & Preparation

* Converted data types (date → datetime, sales → numeric)
* Checked and handled:

  * Missing values
  * Duplicate records
  * Invalid values
* Standardized time-series format

### 3. Data Validation

* Verified chronological order of records
* Checked for missing time intervals (monthly continuity)
* Confirmed data consistency across states

### 4. Exploratory Data Analysis (EDA)

* Analyzed consumption trends over time
* Compared electricity usage across states
* Identified seasonal patterns and variability

---

## 📈 Key Insights

* Residential electricity usage shows **clear seasonal patterns**
* Consumption varies significantly across states due to geographic and climatic factors
* Monthly time-series data provides a strong foundation for **trend analysis and forecasting models**

---

## 📂 Project Structure

```id="structure1"
├── data/
├── notebooks/
│   ├── 01_data_extraction.ipynb
│   ├── 02_data_cleaning.ipynb
│   └── 03_eda.ipynb
├── outputs/
│   └── plots/
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```id="clone1"
git clone https://github.com/PranathiAkula/Residential_Electricity_Data_Pipeline_EIA.git
```

2. Install dependencies:

```id="install1"
pip install pandas requests
```

3. Launch Jupyter Notebook:

```id="run1"
jupyter notebook
```

---

## 🔑 Notes

* Requires an API key from EIA (not included in repository)
* Data is publicly available for analysis and educational use

---

## 📌 Future Improvements

* Add time-series forecasting (ARIMA / Prophet)
* Build interactive dashboard (Power BI / Tableau)
* Automate data pipeline for periodic updates

---

## 👤 Author

Pranathi Akula
