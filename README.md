# COVID-19 Patient Health Prediction Using Machine Learning
Overview
This project leverages machine learning techniques to predict the health status of COVID-19 patients. The goal is to optimize resource allocation in healthcare settings by accurately forecasting patient outcomes based on their clinical and demographic data.

## Key Features:
- Preprocessed data to handle missing and redundant entries.
- Implemented supervised and deep learning methods for classification.
- Conducted hyperparameter tuning to enhance model performance.
- Comprehensive analysis of feature importance and model results.

## Data Overview
The dataset includes features such as:
- Demographics: Age, sex, location.
- Medical history: Chronic diseases, previous conditions.
- COVID-19 specific data: Symptom onset date, hospital admission date, lab results.
- Outcome Labels: Recovered, hospitalized, deceased, etc.

## Data preprocessing involved:

- Removing or imputing missing data.
- Standardizing features for model compatibility.
-Encoding categorical variables.

## Methods
### Supervised Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- Naïve Bayes
- Ensemble methods (Adaboost, Bagging, Voting)

### Deep Learning Models
- Feedforward Neural Network

## Results

### Performance Metrics:
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

### Highlights:
Adaboost with Decision Tree base classifier achieved the best performance.
Extreme Gradient Boosting (XGBoost) showed robust results across all metrics.
Feedforward Neural Networks were effective for complex data patterns.
