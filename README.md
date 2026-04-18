# Manual EDA on Diamonds Dataset

This project presents manual exploratory data analysis (EDA) on the Seaborn `diamonds` dataset using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview

The notebook explores the structure, data types, summary statistics, and feature distributions of diamond-related variables such as carat, cut, color, clarity, depth, table, and price.  
It is intended as a step-by-step practice of a typical manual EDA workflow on a tabular dataset.

## Objectives

- Understand the key features of the diamonds dataset and their distributions.
- Explore relationships between numerical and categorical variables (e.g., carat vs price, cut/color/clarity vs price).
- Practice a clear, reproducible EDA process using Python data science tools.

## Tech Stack


- ![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C%3F?style=for-the-badge) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0%3F?style=for-the-badge)  
- ![Diamonds Dataset](https://img.shields.io/badge/Dataset-Diamonds-0ea5e9?style=for-the-badge) ![EDA](https://img.shields.io/badge/Project-Manual%20EDA-22c55e?style=for-the-badge) ![Jupyter](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
- ![Status](https://img.shields.io/badge/Status-Completed-16a34a%3F?style=for-the-badge)

## Dataset

- Source: Seaborn built-in `diamonds` dataset
- Rows: 53,940
- Columns: 10

Main columns include: `carat`, `cut`, `color`, `clarity`, `depth`, `table`, `price`.

## Features of the Analysis

- Dataset inspection (head, info, missing values)
- Shape and column analysis
- Data type analysis and basic cleaning (if needed)
- Descriptive statistics for numerical and categorical variables
- Visual EDA:
  - Histograms and distribution plots
  - Boxplots to study price vs categorical features (cut, color, clarity)
  - Scatter plots for relationships like carat vs price
  - Correlation analysis for numerical features

## Sample Insights (from the EDA)

- Higher carat values are generally associated with higher diamond prices.
- Price rises steeply with carat, with a strong positive correlation and visible non-linear pattern.
- Cut, color, and clarity categories show noticeable differences in price distributions.
- Some numerical features are correlated, which can be useful for future modeling.

## Files

- `manual-eda-diamonds-dataset.ipynb` – main Jupyter notebook with the complete EDA.
- `README` - for description of project
- `images/` – optional screenshots/plots exported from the notebook.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/adiratna89/Manual-EDA-Diamond-Dataset.git
   cd Manual-EDA-Diamond-Dataset
   ```

2. (Optional) Create and activate a virtual environment.

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `manual-eda-diamonds-dataset.ipynb` and run the cells in order.

## Author

Adiratna Kamble
