# Titanic Dataset Exploratory Data Analysis (EDA)

## Project Overview

This project aims to perform an exploratory data analysis (EDA) on the Titanic dataset. The goal is to understand the data, identify patterns, and extract meaningful insights that could potentially help in predictive modeling.

## Dataset Information

The Titanic dataset contains information about the passengers who traveled on the Titanic. The data includes attributes such as age, sex, ticket class, fare, and survival status.

- **train.csv**: The training set containing data points with known survival outcomes.
- **test.csv**: The test set for which we need to predict the survival outcomes (not used in this EDA).

## Objectives

- Perform data cleaning and preprocessing.
- Generate summary statistics.
- Visualize data distributions and relationships.
- Draw insights from the data analysis.

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Contains the Jupyter Notebook with the EDA.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python libraries.

## How to Run

1. Clone the repository: `git clone https://github.com/yourusername/Titanic_Exploratory_Data_Analysis.git`
2. Navigate to the project directory: `cd Titanic_Exploratory_Data_Analysis`
3. Install the required libraries: `pip install -r requirements.txt`
4. Open the Jupyter Notebook: `jupyter notebook notebooks/Titanic_EDA.ipynb`

## Summary of Findings

### Survival Count
- 342 passengers survived (38.38%)
- 549 passengers did not survive (61.62%)

### Survival Rate by Passenger Class
- 1st Class: 62.96% survived
- 2nd Class: 47.28% survived
- 3rd Class: 24.24% survived

### Survival Rate by Sex
- Female: 74.20% survived
- Male: 18.89% survived

### Age Distribution by Survival Status
- Mean age of survivors: 28.29 years
- Mean age of non-survivors: 30.03 years

### Fare Distribution by Survival Status
- Mean fare of survivors: $48.40
- Mean fare of non-survivors: $22.12

## Conclusions

The exploratory data analysis of the Titanic dataset provides several key insights:
- Survival rates varied significantly across different classes and genders. First-class passengers and females had notably higher survival rates.
- Socio-economic status, as indicated by passenger class and fare paid, played a critical role in survival.
- Age did not appear to be a major determinant of survival, though survivors were slightly younger on average.
- Most passengers traveled alone or with one family member.

These insights suggest that socio-economic status and gender significantly influenced the likelihood of survival on the Titanic. This analysis can guide further predictive modeling and deeper exploration into the factors affecting survival outcomes.

## License

This project is licensed under the MIT License.
