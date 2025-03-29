# Spotify Skip Prediction

## Project Description

This project develops a machine learning model to predict whether a user will skip a track in a Spotify listening session. It utilizes a dataset of user listening behavior and track features to train and evaluate predictive models.

=
## Libraries Used

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `imblearn` (SMOTE)
* `xgboost`
* `lightgbm`
* `boruta`

## Data Preprocessing

* Handling missing values and duplicates.
* Type conversions for boolean columns.
* Creation of a target variable (`skip`).
* One-hot encoding of categorical variables.
* Merging track features with session data.
* Scaling of numerical data.

## Feature Selection

* Used Boruta for feature selection to identify the most relevant features.

## Model Training and Evaluation

* Implemented Logistic Regression, Random Forest, XGBoost, and LightGBM models.
* Used SMOTE to address class imbalance.
* Evaluated model performance using accuracy, classification reports, and confusion matrices.

## Results

* The LightGBM model achieved the best performance in predicting track skips.
* saved the models using pickle.

