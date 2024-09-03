# Titanic Dataset Analysis and EDA

## Overview

This project analyzes the Titanic dataset, focusing on understanding the factors that contributed to passenger survival. The project includes data cleaning, exploratory data analysis (EDA), and visualizations to uncover insights about the passengers, survival rates, and influential features.

## Features

- **Data Cleaning**: Handling missing data, encoding categorical variables, and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Statistical analysis and visualizations to explore survival patterns, demographics, and other factors.
- **Survival Analysis**: Analysis of key factors influencing survival, such as gender, age, class, and fare.
- **Visualizations**: Bar charts, histograms, and other visual aids to illustrate insights.

## Dataset

The Titanic dataset contains information about the passengers aboard the Titanic, including whether they survived or not, their age, gender, class, and other details. 

- **Dataset Name**: Titanic.csv
- **Columns**:
  - `PassengerId`: Unique ID of the passenger
  - `Survived`: Whether the passenger survived (1 = Yes, 0 = No)
  - `Pclass`: Ticket class (1st, 2nd, or 3rd)
  - `Name`: Passenger's name
  - `Sex`: Gender of the passenger
  - `Age`: Age of the passenger
  - `SibSp`: Number of siblings/spouses aboard
  - `Parch`: Number of parents/children aboard
  - `Ticket`: Ticket number
  - `Fare`: Passenger fare
  - `Cabin`: Cabin number
  - `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data Analysis and EDA

### Data Cleaning

- Handled missing data in columns like `Age`, `Cabin`, and `Embarked`.
- Converted categorical variables such as `Sex` and `Embarked` into numerical formats for analysis.
- Filled in missing age values using the median, and assigned passengers without cabin numbers a placeholder value.

### Exploratory Data Analysis (EDA)

1. **Survival Distribution**:
   - Analyzed overall survival rates.
   - Compared survival rates by gender, passenger class, and embarkation point.

2. **Age Distribution**:
   - Visualized the age distribution of passengers.
   - Analyzed survival based on age groups (children, adults, elderly).

3. **Fare and Class Analysis**:
   - Investigated the relationship between fare prices and survival rates.
   - Explored the impact of passenger class (1st, 2nd, 3rd) on survival.

### Visualizations

- **Bar Charts**: Visualizing survival by class, gender, and embarkation point.
- **Histograms**: Showing the distribution of ages and fares.
- **Heatmaps**: Correlation between various features (e.g., age, class, fare) and survival.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pandas (for data manipulation)
- matplotlib or seaborn (for plotting)
- numpy (for numerical operations)
