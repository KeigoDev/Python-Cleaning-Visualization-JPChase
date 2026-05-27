
# 📊 Bank Branch Deposit Analysis (2010–2016)

## 📌 Overview

This project analyzes historical bank branch deposit data from 2010 to 2016 to uncover trends in financial performance, geographic distribution, and branch-level growth. The dataset is sourced from Kaggle and is attributed to JPMorgan Chase & Co..

The goal is to transform raw financial data into actionable insights that can support strategic decision-making in areas such as branch expansion, optimization, and risk management.


## 🎯 Business Objectives

This analysis aims to answer the following key questions:

* Which branches generate the highest total deposits?
* Which branches show the strongest and weakest growth?
* How do deposits trend over time?
* Which geographic regions (State/City) contribute the most?
* Are there branches with declining or unstable performance?



## 🗂️ Dataset Description

The dataset contains branch-level information, including:

* **Institution Name**
* **Branch Name / Branch Number**
* **Established Date / Acquired Date**
* **Location**: City, County, State, Zipcode
* **Coordinates**: Latitude, Longitude
* **Deposits**: 2010–2016 annual values


## 🧹 Data Preparation

Data cleaning and preprocessing steps included:

* Converting date fields (`Established Date`, `Acquired Date`)
* Handling missing values
* Ensuring deposit columns are numeric
* Removing duplicates
* Creating a clean dataset for analysis



## ⚙️ Feature Engineering

The following metrics were created:

* **Branch Age** → from Established Date
* **Years Since Acquisition** → from Acquired Date
* **Total Deposits** → sum of 2010–2016 deposits
* **Growth %** → (2016 vs 2010)
* **CAGR** → annualized growth rate



## 📈 Exploratory Data Analysis

### 📊 Deposit Trend Over Time

* Overall deposits increased steadily from 2010 to 2015
* A noticeable decline appears in 2016

### 🏦 Branch Performance

* Identified top-performing and underperforming branches
* Significant variation in branch-level growth rates

### 🌎 Geographic Insights

* Certain states dominate total deposit contributions
* Regional differences in growth patterns observed

### ⚠️ Risk Indicators

* Several branches show negative growth
* Potential indicators of operational inefficiencies or closures



## 📊 Visualization

Key visualizations include:

* 📈 Line chart: Total deposits over time
* 📊 Bar chart: Top 10 branches by performance
* 📉 Bar chart: Top 10 declining branches
* 🌎 Geographic map (Tableau) using latitude/longitude


## 🛠️ Tools & Technologies

* **Python** (Pandas, Matplotlib)
* **Jupyter Notebook**




## 🧠 Key Insights

* Deposit growth is consistent across most years, with a notable drop in 2016
* A small number of branches contribute a large portion of total deposits
* Some branches exhibit sustained decline, indicating potential risk areas
* Geographic concentration suggests opportunities for expansion and optimization



## 🚀 Future Improvements

* Predictive modeling for future deposit trends
* Branch clustering (high vs low performance)
* Automated dashboards for real-time monitoring
* Deeper analysis of 2016 anomalies


## 📌 Conclusion

This project demonstrates how raw banking data can be transformed into meaningful insights through data cleaning, feature engineering, and visualization. The findings highlight key performance trends and provide a foundation for data-driven decision-making in the banking sector.



## 👤 Author

**Matthew Ferrer**
 Data Analyst | Data Analytics | Automation | AI Strategy

