# 🚗 Summer Analytics 2025 – Week 1 Assignment: Data Grand Prix

Welcome to the Data Grand Prix, the Week-1 assignment for Summer Analytics 2025! This project explores an automobile dataset using fundamental data analysis and visualization techniques with Python.

---

## 📁 Dataset

- File Name: Cars.csv
- Description: The dataset contains technical specifications of 398 cars, including attributes such as mileage, horsepower, weight, acceleration, origin, and model year.

---

## 📌 Objectives

1. Perform basic data exploration using pandas.
2. Clean and preprocess data (e.g., handle missing values).
3. Create new computed columns and update indices.
4. Answer graded analytical questions using filtering and grouping.
5. Visualize insights using Matplotlib and Seaborn.
6. Identify consistent car models based on performance metrics.

---

## 🔧 Technologies Used

- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 🧪 Key Tasks Performed

### ✅ Data Cleaning
- Converted non-numeric entries in horsepower to NaN and dropped rows with missing critical data.

### ✅ Feature Engineering
- Created hp_to_weight ratio column to evaluate performance.
- Set custom DataFrame indices based on different features.

### ✅ Exploratory Analysis
- Found:
  - Car with highest horsepower.
  - Number of cars with MPG ≥ 35.
  - Common origins for specific conditions.
  - Year with highest average MPG.
  - Average acceleration for Japanese cars.

### ✅ Visualizations
- Line plot showing MPG trends over time by car origin.
- Scatter plot of horsepower vs weight, colored by origin and sized by MPG.

### ✅ Bonus Analysis
- Identified consistent car models produced over multiple years with low variation in MPG (std < 1.0).
- Reported car names, their average MPG, standard deviation, and number of appearances.

---

## 📊 Sample Visualization

![mpg_trend](assets/mpg_trend.png)

---

## 🚀 Getting Started

1. Clone the repository or download the notebook and dataset.
2. Install dependencies (if not using Colab):
   ```bash
   pip install pandas matplotlib seaborn
