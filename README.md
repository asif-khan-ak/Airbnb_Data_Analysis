# Airbnb_Data_Analysis
# 📚 Plagiarism Detection Web App using Machine Learning & Flask

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data--Analysis-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualizations-red)
![Seaborn](https://img.shields.io/badge/Seaborn-StatisticalPlots-cyan)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

This project is a complete **Data Science case study** built on **Airbnb listing data**. It showcases **data cleaning**, **data visualization**, and **feature engineering** to uncover insights and predict listing prices based on various features.

---

## 📁 Dataset Preparation

- Dataset used: `airbnb_open_data.csv`
- Shape: `102,593 rows × 26 columns`
- Data includes:
  - Listing details (name, description, price, availability)
  - Host information
  - Location data
  - Review scores
  - Number of amenities, etc.
  
---

## 🧠 Machine Learning Overview

The following classification models were trained and evaluated:

### 📊 Features Engineered

- **Description sentiment score** (using TextBlob)
- **Host tenure in days**
- **Number of amenities**
- **Length of description**
- **Review scores and listing availability**
- One-hot encoded categorical variables (neighbourhood, room type)

---

## 📊 Data Visualization

Extensive visual exploration was performed using:

- 📌 **pandas & numpy** – Statistical summaries and aggregations
- 📌 **matplotlib & seaborn** – High-quality plots for analysis
- 📌 **Histogram** – For price, review scores, and availability distribution
- 📌 **Bar Graphs** – To compare average prices across neighborhoods and room types
- 📌 **Counterplot** – For visualizing category frequency distribution
- 📌 **Boxplots & Violin plots** – To identify outliers and price spread
- 📌 **Heatmaps** – Correlation between features and target variable

These visual tools helped uncover:
- Price outliers and skewness (log transformations applied)
- Neighborhoods with the highest/lowest average prices
- Feature correlations that guided model building

### 📁 📁 Key Files

| File                            | Description                                      |
|---------------------------------|--------------------------------------------------|
| `Airbnb_Data_Analysis.ipynb`    | Main notebook with EDA, feature engineering, ML  |
| `airbnb_open_data.csv`          | Cleaned Airbnb listings dataset                  |
| `README.md`                     | This readme file                                 |

---

## 🧰 Technologies Used

- **Python** (3.9)
- **pandas** – Data manipulation
- **numpy** – Numerical computing
- **matplotlib & seaborn** – Data visualization

---

