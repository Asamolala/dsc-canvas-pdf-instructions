
# Data-Driven Insights for Predicting Vaccine Uptake

## Overview

This project analyzes factors influencing H1N1 vaccine uptake using a structured data science approach. 
It identifies key predictors of vaccination behavior and develops predictive models to guide public health strategies. 

## Project Structure

1. **Business Understanding**
   - Defines the problem and objectives for analyzing H1N1 vaccine uptake.

2. **Data Understanding**
   - Examines the dataset, including variables like health status, risk perception, and opinions about vaccine effectiveness.

3. **Data Preparation**
   - Preprocessing steps include:
     - Dropping irrelevant columns (`respondent_id`, `seasonal_vaccine`).
     - Encoding categorical variables using OneHotEncoder.
     - Handling missing data with Iterative Imputer.
     - Encoding high-cardinality features with CountEncoder.
     - Splitting the dataset into training and testing sets.
     - Using pipelines for streamlined processing.

4. **Exploratory Data Analysis (EDA)**
   - Key findings include:
     - Strong correlation between doctor recommendations and vaccination.
     - Impact of health insurance on vaccine uptake.
     - Influence of belief in vaccine effectiveness and risk perception on vaccination behavior.

5. **Modeling**
   - Models developed include:
     - Decision Tree Classifier (AUC = 0.84)
     - Logistic Regression (AUC = 0.84)
   - Both models provide insights but face challenges with low precision and F1 scores.

6. **Evaluation**
   - Models outperform baseline metrics but require improvement in precision and recall.

7. **Conclusions, Recommendations, and Next Steps**
   - Key recommendations for public health include:
     - Promoting doctor recommendations.
     - Addressing healthcare access barriers.
     - Enhancing educational outreach to improve vaccine perceptions.
   - Next steps include analyzing recent data and extending the scope to include seasonal flu vaccination.

## Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Usage

1. Clone this repository.
2. Open the Jupyter Notebook file in your preferred environment.
3. Follow the steps outlined in the notebook for analysis, modeling, and evaluation.

## Results

The project highlights key factors influencing H1N1 vaccination and demonstrates the use of machine learning models for prediction. 
While the models require further refinement, the insights gained can guide public health policies and interventions.

## Future Work

- Incorporate more recent survey data to refine predictions.
- Extend analysis to include seasonal flu vaccination behavior.
- Conduct additional feature engineering to enhance model performance.

---
