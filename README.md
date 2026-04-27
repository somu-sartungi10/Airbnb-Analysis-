# 🏡 Airbnb NYC 2019 Data Analysis

## 📌 Project Overview
This project is a basic exploratory data analysis (EDA) of the Airbnb NYC 2019 dataset.

The main focus was to practice:
- data cleaning
- handling missing values
- working with pandas
- creating visualizations

---

## 📊 Dataset
- Airbnb NYC 2019 dataset
- Contains information about listings such as:
  - price
  - neighbourhood_group
  - room_type
  - reviews
  - availability

---

## 🧹 Data Cleaning
- Filled missing values (e.g., used "unknown" for some columns)
- Converted `last_review` column to datetime format
- Handled inconsistent formats in some columns
- Removed some outliers in price (filtered extreme values)

---

## 📈 Analysis Performed
- Checked distribution of price using histogram
- Identified skewness in price data
- Compared price across neighbourhood groups
- Compared room types with price
- Checked correlation between numeric features

---

## 📊 Visualizations
- Histogram (price distribution)
- Boxplot (to detect outliers)
- Bar plots (room_type vs price, neighbourhood vs price)
- Scatter plot (location using latitude & longitude)
- Interactive map using Plotly

---

## 🔍 Observations
- Price data is right-skewed
- Manhattan listings tend to have higher prices
- Entire homes/apartments are more expensive than private/shared rooms
- There are extreme outliers in price

---

## 🛠️ Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Missingno

---

## 🚀 How to Run
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly missingno
