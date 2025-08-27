# Maximizing Taxi Driver Revenue through Payment Type Analysis

## 📌 Project Overview
This project explores how different payment types (cash vs credit card) impact taxi driver revenue.  
Using **Python, Exploratory Data Analysis (EDA), and Hypothesis Testing**, I analyzed NYC Yellow Taxi trip data to discover whether drivers earn more from certain payment methods.

## 🎯 Objective
- Investigate the relationship between fare amount and payment method.  
- Perform hypothesis testing (t-test) to check if fare differences are statistically significant.  
- Provide business recommendations to help maximize taxi driver revenue.  

## 📊 Dataset
- Source: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- Original January dataset size: ~600MB (too large for GitHub).  
- This repo includes a **sample of 5,000 rows** → `yellow_taxi_sample.csv` for reproducibility.  

⚠️ To reproduce full results, download the complete dataset from the link above.

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy, Statsmodels  

## 📈 Analysis Workflow
1. Data cleaning & feature engineering (trip duration, payment type formatting).  
2. Exploratory Data Analysis (EDA) with descriptive statistics and visualizations.  
3. Hypothesis testing (t-test) to compare fare amounts by payment method.  
4. Insights & business recommendations for taxi drivers.  

## 🔎 Key Findings
- Credit card payments generally have **higher average fares** compared to cash.  
- Hypothesis testing confirms the difference is **statistically significant**.  
- **Business Insight**: Encouraging riders to use credit cards can help drivers increase revenue.  

## 📂 Repository Structure
- `project.ipynb` → Main Jupyter notebook with full analysis.  
- `yellow_taxi_sample.csv` → Sample dataset (5,000 rows).  
- `requirements.txt` → List of dependencies.  

## 🚀 How to Run
Clone this repo and install dependencies:
```bash
pip install -r requirements.txt
jupyter notebook project1.ipynb
