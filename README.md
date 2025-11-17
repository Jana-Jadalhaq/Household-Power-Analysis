# Household Power Consumption Analysis — Lab 2

This project analyzes the **Individual Household Electric Power Consumption Dataset** from the UCI Machine Learning Repository. The notebook demonstrates a full data science workflow including data cleaning, missing-value handling, time-series preprocessing, feature engineering, and visualizations that reveal electricity usage trends.

---

## 📊 Dataset Information

**Source:** UCI Machine Learning Repository  
🔗 https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

The dataset contains more than **2 million measurements** collected between 2006 and 2010, sampled every minute.  

Key variables include:

- Global active power  
- Global reactive power  
- Voltage  
- Global intensity  
- Sub-metering values  
- Date & time fields  

---

## 📂 Project Structure

household-power-analysis/
│
├── Lab2.ipynb
├── household_power_consumption.txt
├── README.md
└── images/
├── dataset-preview.png
├── missing-values.png
├── histogram-global-active.png
├── power-distribution.png
├── month-week-plot.png
└── violin-distribution.png


---

## 🧠 Learning Objectives

- Load and clean a large dataset  
- Convert date + time into a single datetime column  
- Handle missing and corrupted data  
- Create new time-based features (Month, Day of Week)  
- Perform exploratory data analysis  
- Visualize consumption patterns  
- Understand seasonal and weekly behavior  

---

## 🔧 Methods Used

### ✔ Data Cleaning
- Replaced `"?"` with NaN  
- Dropped invalid rows  
- Converted date/time fields into `Datetime`  

### ✔ Feature Engineering
- Extracted Month  
- Extracted Day of Week  
- Aggregated energy usage  

### ✔ Visualizations
- Histogram of Global Active Power  
- Histogram of daily consumption  
- Month × Day-of-Week frequency plot  
- Violin plot of monthly consumption  

---

## 📈 Key Insights

- Electricity usage displays a **right-skewed distribution**, with most values concentrated at lower power levels.  
- Seasonal trends show that winter months have greater variance in power consumption.  
- Weekday vs weekend patterns highlight differences in household behavior.  
- Monthly violin plots reveal fluctuations in energy demand throughout the year.  

---

## ▶ How to Run

Install required libraries:

```sh
pip install pandas numpy matplotlib seaborn
Open the notebook in:
Google Colab
Jupyter Notebook
VS Code
