# Titanic Passenger Survival - Exploratory Data Analysis (EDA)

This repository contains my first portfolio project as an aspiring AI/ML Engineer. The goal of this project is to perform an Exploratory Data Analysis (EDA) on the classic Titanic dataset to investigate who survived and why.

## 🚀 Project Overview
The Titanic dataset is a classic data science benchmark. In this project, I loaded the data, analyzed its baseline state, resolved missing features, and engineered basic variables to expose key correlations.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** VS Code + Google Colab Runtime
* **Libraries:** Pandas, NumPy, Matplotlib

## 📋 Core Workflow

1. **Data Loading:** Fetched the live data directly via an open GitHub URL link into a Pandas DataFrame and inspected rows using `df.head()` and data schema via `df.info()`.
2. **Data Cleaning:** Investigated missing entries using `df.isnull().sum()`. Filled missing values inside the `Age` column using the calculated global mean.
3. **Feature Engineering:** Combined the `SibSp` (siblings/spouses) and `Parch` (parents/children) columns into a unified `Family` column to facilitate easier compute metrics.
4. **Data Visualization:** Plotted target distributions for total survivors vs. non-survivors, and analyzed survival patterns across passenger economic classes using Matplotlib bar charts.
5. **Storytelling:** Structured the findings and conclusions contextually inside the Jupyter Notebook.

## 📊 Conclusions Drawn
* **Survival Count:** A significantly higher number of passengers did not survive the incident compared to those who did.
* **Class Matrix Correlation:** Based on the generated statistical class distribution, passengers belonging to the **1st Class** had a distinctively higher survival chance compared to lower economic tiers on the vessel.

## 🏃‍♂️ How to Run This Project
The notebook is completely self-contained. Since the dataset is fetched live inside the code, you do not need to download separate CSV files manually.

1. Download the `Titanic_EDA.ipynb` file from this repository.
2. Open it inside VS Code, Jupyter, or Google Colab.
3. Run all cells sequentially.
