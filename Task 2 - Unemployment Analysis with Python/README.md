# Unemployment Analysis with Python

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on unemployment data in India to identify regional and temporal trends, with particular focus on changes during the COVID-19 period.

The analysis uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to clean, analyse, and visualise the unemployment dataset.

## 🎯 Objective

The main objectives of this project are:

- Analyse unemployment rates across different regions of India.
- Study month-wise changes in unemployment rates.
- Compare unemployment trends across major regions.
- Identify the top 10 regions with the highest average unemployment rates.
- Analyse the relationship between unemployment rate, employment, and labour participation rate.
- Compare unemployment conditions between the Pre-COVID and Post-COVID periods.
- Generate meaningful observations and insights from the data.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset

The project uses the **Unemployment in India** dataset recommended in the Oasis Infobyte Data Science internship task.

The dataset contains information including:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## 🔄 Project Workflow

1. Import required Python libraries.
2. Load the unemployment dataset.
3. Inspect the dataset shape and structure.
4. Check data types and missing values.
5. Clean text and convert the date column.
6. Remove rows containing missing values.
7. Perform region-wise unemployment analysis.
8. Analyse month-wise unemployment trends.
9. Compare unemployment rates across three major regions.
10. Identify the top 10 regions with the highest average unemployment rate.
11. Analyse correlations between unemployment, employment, and labour participation.
12. Compare Pre-COVID and Post-COVID unemployment conditions.
13. Generate insights and conclusions.
14. Save the cleaned dataset.

## 📊 Analysis and Visualisations

### 1. Region-wise Average Unemployment Rate

A bar chart is used to compare the average unemployment rate across different regions.

### 2. Month-wise Unemployment Trend

A line chart shows how the average unemployment rate changed month by month over time.

### 3. Regional Time-Series Analysis

A time-series line chart compares unemployment-rate trends for three major regions.

### 4. Top 10 Regions

A horizontal bar chart identifies the 10 regions with the highest average unemployment rates.

### 5. Correlation Heatmap

A heatmap examines the relationships between:

- Estimated Unemployment Rate
- Estimated Employed
- Estimated Labour Participation Rate

### 6. Pre-COVID vs Post-COVID Comparison

The dataset is divided into two periods:

- **Pre-COVID:** Before March 2020
- **Post-COVID:** March 2020 onwards

The mean values of unemployment rate, employment, and labour participation rate are compared between the two periods.

## 🔍 Key Insights

The analysis helps identify:

- Differences in unemployment rates between Indian regions.
- Changes in unemployment over time.
- Regions experiencing relatively high average unemployment.
- Relationships between unemployment, employment, and labour participation.
- Changes in unemployment conditions during the COVID-19 period.

The exact numerical findings are available in the Jupyter Notebook.

## 📁 Project Files

```text
Task 2 - Unemployment Analysis with Python/
│
├── Task 2 - Unemployment Analysis.ipynb
├── Unemployment in India.csv
├── unemployment_india_cleaned.csv
└── README.md
```

## ✅ Task Requirements Completed

- [x] Dataset loading
- [x] Shape inspection
- [x] Null value check
- [x] Data type conversion
- [x] Region-wise average unemployment analysis
- [x] Month-wise trend analysis
- [x] Time-series line chart for three major regions
- [x] Top 10 regions by average unemployment rate
- [x] Correlation heatmap
- [x] Pre-COVID vs Post-COVID comparison
- [x] Written observations
- [x] Clean and commented Jupyter Notebook

## 👨‍💻 Author

**Udith Krishna**

Data Science Intern — Oasis Infobyte