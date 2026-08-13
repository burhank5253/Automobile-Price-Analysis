# 🚗 Automobile Price Analysis

## 📌 Project Overview

This project analyzes automobile data using Python to understand the factors that influence automobile prices, performance, and fuel efficiency.

The analysis was performed using **Pandas, Matplotlib, and Seaborn** in Jupyter Notebook.

## 🎯 Objectives

- Analyze automobile prices across different brands
- Identify factors strongly related to automobile price
- Compare fuel types and fuel efficiency
- Analyze body styles and drive-wheel configurations
- Study relationships between engine size, horsepower, price, and MPG
- Visualize important patterns using charts and graphs

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The dataset contains **205 automobile records and 15 variables**, including:

- Make
- Fuel Type
- Body Style
- Drive Wheels
- Engine Size
- Horsepower
- City MPG
- Highway MPG
- Width
- Height
- Price

## 🧹 Data Cleaning

The project includes:

- Handling missing values
- Replacing `?` values with missing values
- Converting numerical columns to appropriate data types
- Checking duplicate records
- Filling missing numerical values
- Checking data types

The final dataset contains **205 rows and 15 columns**.

## 📈 Key Findings

### Price Correlation

| Feature | Correlation with Price |
|---|---:|
| Engine Size | 0.853 |
| Horsepower | 0.747 |
| Width | 0.718 |
| Height | 0.132 |
| City MPG | -0.655 |
| Highway MPG | -0.679 |

Engine size has the strongest positive correlation with automobile price.

### Horsepower and Fuel Efficiency

Horsepower showed a strong negative relationship with fuel efficiency:

- Horsepower vs City MPG: **-0.802**
- Horsepower vs Highway MPG: **-0.771**

This indicates that higher-horsepower vehicles generally have lower MPG in this dataset.

### Brand Analysis

The analysis found substantial differences in average automobile prices between brands.

Jaguar had the highest average price among the brands analyzed.

### Fuel Type Analysis

The dataset contains:

- Gas: 185 vehicles
- Diesel: 20 vehicles

Diesel vehicles had a higher average price and higher average fuel efficiency than gas vehicles.

### Drive Wheels

The average prices were:

- RWD: **19,655.54**
- 4WD: **10,436.44**
- FWD: **9,365.70**

RWD vehicles had the highest average price.

## 📊 Visualizations

The project includes visualizations such as:

- Average automobile price by brand
- Fuel type analysis
- Body style price analysis
- Drive-wheel price analysis
- Correlation analysis
- Horsepower vs MPG
- Engine size vs MPG
- Price distribution
- Top expensive automobiles

## 📁 Project Files

- `Automobile_Price_Analysis.ipynb` — Jupyter Notebook containing the complete analysis
- `Automobile_data.csv` — Dataset used for the analysis

## 👤 Author

**Burhanuddin Khamerawala**

Aspiring Data Analyst

**Skills:** Python | SQL | Excel | Power BI | Tableau
