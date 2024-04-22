# COVID Dataset Analysis Project

## Project Overview
This project involves a thorough analysis of a large COVID dataset, originally sourced from Kaggle. Due to the size of the dataset (over one million patient records), it is not included in the GitHub repository. Interested parties can access the dataset directly from [Kaggle](https://www.kaggle.com/datasets/meirnizri/covid19-dataset/data).

### Key Objectives:
- Data Exploration and Cleaning
- Data Analysis and Visualization
- Statistical Testing
- Predictive Modeling

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

## Predictive Modeling Results
The results of various predictive models on the dataset are summarized below:

| Model               | Accuracy | AUC      |
|---------------------|----------|----------|
| Linear Regression   | 0.809589 | 0.734158 |
| Random Forest       | 0.825930 | 0.779909 |
| Gradient Boosting   | 0.827156 | 0.781847 |
| K-Nearest Neighbors | 0.813261 | 0.704024 |

The accuracy graph for the Logistic Regression model over epochs is presented here:

![Model accuracy over epochs](https://github.com/MiriJ15/Covid19-Demographic-Analysis/blob/main/deep_learning.png)

## Results
The analysis revealed significant associations between several factors and patient outcomes. Key findings include:

- Statistically significant relationships between patient demographics/comorbidities and the likelihood of hospitalization.
- The Logistic Regression model's training and validation accuracies are plotted over the number of epochs, demonstrating the model's stability over time.
- Predictive modeling results, showcasing the potential of using patient data to forecast outcomes in a healthcare setting.
