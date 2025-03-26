# Web-Scraping-and-Data-Analysis-of-Property-Data
Data Science Project

# 🏠 Real Estate Sales Analysis using Python

## 📌 Project Overview

This project focuses on the **end-to-end analysis of real estate property sales** data, using data preprocessing, visualization, and statistical analysis to extract meaningful insights. The project is divided into two Jupyter notebooks, as outlined in the assignment specification:

1. **EDA Notebook** – Initial exploration, visualization, and insight generation.
2. **Analytics Base Table (ABT) Notebook** – Preparation of a clean dataset for analytical use, transformation logic, and summarization.

---

## 🧩 Problem Statement

> **Objective**: To explore and analyze property sales data and draw actionable insights using Python.  
The goal is to prepare a cleaned and structured **Analytics Base Table (ABT)**, perform **Exploratory Data Analysis (EDA)**, and discuss the **impact of features like garden, garage, and location on sale price**.

---

## 📁 Project Structure


---

## ⚙️ Tools and Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regex (`re`)
- OS Module

---

## 🔍 Key Features of the Project

### ✅ Data Cleaning & Preprocessing
- Standardized inconsistent date formats (`Date Sold`)
- Removed prefixes like `"Sold "` from date strings
- Converted date strings to `datetime64` format
- Extracted sale year and month as new columns
- Handled missing and categorical values

### 📊 Exploratory Data Analysis (EDA)
- Trends in **number of properties sold per year and month**
- Insights into **seasonal patterns of sales**
- Analysis of **average sale price trends over time**
- Impact of **Garden**, **Garage**, and **First-Time Buyer status** on sale prices
- **Top 10 locations** with highest property sales
- Sale price distribution and **outlier detection**

### 📉 Distribution and Outlier Analysis
- Histograms and KDE plots to analyze price spread
- Boxplots to identify extreme values (outliers)

---

## 📌 Visual Examples

> **Note:** All plots are included in the notebook for clarity. Examples:
- Sales trend by year/month
- Average sale price by year
- Sale price distributions by features (e.g., Garden, Garage)

---

## 📊 Dataset Description

The dataset used (`property_sales.csv`) contains:
- `Date Sold`
- `Sale Price (€)`
- `Year Built`
- `Location`
- `Garden`, `Garage`
- `First Time Buyer` status

---

## 📘 Instructions to Run

1. Clone this repository:

   git clone https://github.com/your-username/real-estate-sales-analysis.git
   cd real-estate-sales-analysis

2. Open either notebook in Jupyter Lab, Jupyter Notebook, or VS Code.

3. Ensure the property_sales.csv file is in the same directory before running the ABT notebook.

## 💬 Discussion & Learnings
✅ Challenges Faced
Uneven date formats required custom regex preprocessing.

Categorical values like "Unknown" in columns such as Garage required thoughtful interpretation.

Some outliers in price (e.g., > €1.5M) skewed average-based visualizations.

## 💡 Key Insights
Property sales increased each year, peaking in 2024.

Summer months (May–July) consistently show higher sales volume.

Properties with gardens and garages tend to fetch higher median prices.

First-time buyers tend to purchase slightly cheaper properties than others.

## 🚀 Future Improvements
Add predictive modeling (e.g., regression) for estimating property prices.

Enrich the dataset using external APIs (e.g., economic indicators, interest rates).

Perform geospatial analysis using tools like geopandas or folium.

## 🔗 Related Resources
Pandas Documentation

Seaborn Gallery

Matplotlib Official

Kaggle: Real Estate Datasets

## 📌 Author
Shantanu Ramesh Bhute
LinkedIn | GitHub


