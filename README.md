# COVID-19 Data Analysis and Machine Learning

This project performs Exploratory Data Analysis (EDA) and applies machine learning techniques to a COVID-19 dataset to analyze patterns and predict outcomes. The dataset contains binary (Yes/No) features related to symptoms and conditions, with a target variable indicating COVID-19 diagnosis.

## Table of Contents

- Project Overview
- Dataset
- File Structure
- Installation
- Usage
- Visualizations
- Results
- Contributing
- License

## Dataset

- The dataset (Covid Dataset.csv) contains:
Features: Binary (Yes/No) columns such as Breathing Problem, Fever, Dry Cough, etc.
- Target: COVID-19 (Yes/No), indicating whether the individual tested positive.
- Size: Approximately 5,435 rows.

- Source: Not specified (assumed to be a public or custom dataset).

- Note: The dataset is imbalanced, with a high proportion of positive cases, which may require techniques like SMOTE for modeling.

covid-19-project/
│
├── Covid Dataset.csv          # Dataset with binary features and target
├── covid_eda.py               # Python script for EDA and visualizations
├── covid.ipynb                # Jupyter Notebook for EDA or ML analysis
├── README.md                  # Project documentation
├── feature_distributions.png  # Visualization of feature counts
├── correlation_heatmap.png    # Correlation matrix of features
├── feature_target_relationships.png  # Feature vs. COVID-19 relationships
├── covid_target_distribution.png    # Pie chart of target distribution
├── feature_correlations_target.png  # Correlations with COVID-19

## Clone the Repository:

git clone https://github.com/KHATEEB-ARMAN/COVID-19-Data-EDA-and-Machine-Learning-.git
cd COVID-19-Data-EDA-and-Machine-Learning-


- Run EDA Script: Execute the Python script to generate visualizations:
python covid_eda.py


# Visualizations

## The EDA script generates:

- Target Distribution: Pie chart showing the proportion of COVID-19 positive/negative cases (covid_target_distribution.png).
- Feature Distributions: Bar plots of Yes/No counts for each feature (feature_distributions.png).
- Correlation Heatmap: Matrix of feature correlations (correlation_heatmap.png).
- Feature-Target Relationships: Stacked bar plots showing feature impacts on COVID-19 outcome (feature_target_relationships.png).
- Feature Correlations with Target: Bar plot of correlations with COVID-19 (feature_correlations_target.png).


## Results

- The dataset is imbalanced, with a majority of positive COVID-19 cases.
- Features like Breathing Problem and Fever show strong correlations with the target.
- Visualizations highlight key patterns, useful for feature selection in machine learning.