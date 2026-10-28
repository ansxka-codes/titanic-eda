# Titanic Survival — Exploratory Data Analysis

## Overview

This project explores the Titanic passenger dataset to understand which passenger characteristics were associated with survival.

The analysis uses Python, Pandas, NumPy, Matplotlib and Seaborn to inspect the data, investigate missing values, calculate summary statistics and visualize relationships between variables.

## Objectives

- Understand the structure and quality of the dataset.
- Investigate missing values and potential data-quality issues.
- Explore survival patterns by passenger class, gender, age and family size.
- Examine the relationship between passenger fare and survival.
- Communicate findings through clear visualizations.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings

*To be finalized after completing the analysis.*

- Overall survival rate: approximately 38.4%.
- Female passengers had a substantially higher survival rate than male passengers.
- Survival rates differed across passenger classes.
- Higher fare groups had higher overall survival rates, although this relationship was less consistent when passenger class was considered.

## Project Structure

- `titanic_eda.ipynb` — notebook containing the analysis and visualizations.
- `data/` — location for the dataset, if included.
- `images/` — selected visualizations.
- `requirements.txt` — Python dependencies.

## How to Run

1. Clone or download this repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Obtain the Titanic dataset from the [official Kaggle competition page](https://www.kaggle.com/competitions/titanic/data).
4. Place `train.csv` inside the `data/` folder, if your notebook is configured to read from that location.
5. Open `titanic_eda.ipynb` in Jupyter Notebook or VS Code and run the cells.

## Limitations

This is an exploratory analysis. Observed relationships do not establish causation. Some groups contain relatively few passengers, and missing data may affect certain comparisons.

## Data Source

[Kaggle — Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
