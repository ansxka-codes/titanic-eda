

# Titanic Dataset – Exploratory Data Analysis

## Project Overview

This project explores the Titanic passenger dataset to understand the factors associated with passenger survival. It uses Python, Pandas, Matplotlib, and Seaborn to perform data cleaning, statistical analysis, and data visualization.

The objective is to identify patterns in survival based on passenger characteristics and explore relationships between multiple features.

## Dataset

The project uses the Titanic dataset containing information about 891 passengers, including:

- Passenger class
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket fare
- Cabin information
- Port of embarkation
- Survival status

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### 1. Data Cleaning and Exploration
- Inspected dataset structure and dimensions.
- Identified missing values.
- Checked for duplicate records.
- Created additional features such as `FamilySize` and `HasCabin`.

### 2. Univariate and Bivariate Analysis
Explored survival patterns based on:
- Gender
- Passenger class
- Age
- Family size
- Fare
- Port of embarkation
- Cabin information

### 3. Multivariate Analysis
Investigated relationships between multiple passenger characteristics and survival:
- Gender and passenger class vs survival
- Age and gender vs survival
- Age and passenger class vs survival

## Key Findings

- The overall survival rate was approximately **38.38%**.
- Female passengers had a considerably higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second- and third-class passengers.
- Survivors were generally younger than non-survivors.
- Passengers travelling in small family groups and those paying higher fares generally showed higher survival rates.
- Multivariate analysis showed that female passengers had higher survival rates across all passenger classes.
- Survivors had a lower average age than non-survivors across all three passenger classes.

## Project Structure

```text
titanic-eda/
│
├── data/
│   └── train.csv
│
├── titanic_eda.ipynb
├── titanic_practice.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd titanic-eda
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the notebook:

   ```bash
   jupyter notebook titanic_eda.ipynb
   ```

## Limitations

- The dataset contains missing values, particularly in the Age and Cabin columns.
- Some passenger groups have relatively few observations.
- The analysis identifies associations but does not establish causation.
- Some passenger characteristics may be related to one another.

## Conclusion

This project provided an opportunity to explore a real-world dataset through data cleaning, statistical analysis, and visualization. It helped identify important survival patterns and understand how multiple passenger characteristics were associated with survival.

