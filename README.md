# Property-Price-Prediction-Kaggle-Challenge-
Machine learning pipeline developed for the RCBP Kaggle Challenge to predict property prices. Includes missing value handling, preprocessing of numerical and categorical features, feature scaling, model training, and evaluation using RMSE, cross-validation, and residual analysis.

## Kaggle-Challenge 
This competition, participants are provided with structured data describing residential properties, including location attributes, physical characteristics, and neighborhood features.
The task was to build a machine learning model to predict the final sale price of each property.
The target variable is continuous, making this a regression problem.

#### Participants are expected to:

  a)Perform exploratory data analysis
  b)Handle missing values
  c)Engineer meaningful features
  d)Build and validate regression models
  e)Optimize predictions based on the evaluation metric

#### Evaluation 
Primary Metric: Root Mean Squared Error (RMSE) and Mean RMSE
Lower RMSE = Better performance.

## Results
a)Achieved a mean 5-fold cross-validation RMSE scores: [16.17726002 16.36351354 15.81342896 16.11964252 15.60740072] and Mean RMSE: 16.016249150496243 consistent performance across folds.
b)Model performance was validated using cross-validation, RMSE evaluation, and error analysis before generating final competition submissions.
c)Developed an ensemble regression pipeline using XGBoost and LightGBM with automated preprocessing and feature engineering.
d)Applied log-transformation of the target variable to improve prediction accuracy and model stability.
