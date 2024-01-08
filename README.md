
# COVID Dataset Analysis Project

## Project Overview
This project involves a thorough analysis of a large COVID dataset, originally sourced from Kaggle. Due to the size of the dataset (over one million patient records), it is not included in the GitHub repository. Interested parties can access the dataset directly from [Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data).

### Key Objectives:
1. Data Exploration and Cleaning
2. Data Analysis and Visualization
3. Statistical Testing
4. Predictive Modeling

## Installation
Instructions on setting up the project locally.

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Data Analysis and Visualization
I have conducted a comprehensive analysis of the dataset, exploring key features like age, sex, comorbidities, and patient outcomes. The analysis includes:

- Distribution of age and sex.
- Prevalence of comorbidities like diabetes, COPD, asthma, etc.
- Visualization of patient outcomes (hospitalization, ICU admission).

## Advanced Analysis
The advanced statistical analysis and predictive modeling include:

- Chi-squared tests to examine the relationships between categorical variables and patient outcomes.
- A logistic regression model to predict patient outcomes, with an accuracy of 82.2%. The model demonstrates high precision and recall for predicting patients returning home, but lower effectiveness for predicting hospitalizations.

## Results
The analysis revealed significant associations between several factors and patient outcomes. Key findings include:

- Statistically significant relationships between patient demographics/comorbidities and the likelihood of hospitalization.
- Predictive modeling results, showcasing the potential of using patient data to forecast outcomes in a healthcare setting.
