# ⚠ Accident Severity Prediction

This project predicts accident severity based on driver, vehicle, and environmental factors using machine learning. It helps identify high-risk accidents to support road safety decisions.

## 📂 Dataset

Includes driver demographics, vehicle info, road conditions, and accident details.
Target: Accident_severity (Slight Injury, Serious Injury, Fatal Injury)

## 🚀 Key Features

Feature Engineering: Extracted Hour and Time_of_day (Morning, Noon, Evening, Night).

Preprocessing Pipeline:

Median imputation (numeric)

Most frequent imputation (categorical)

Standard scaling

One-hot encoding

Data Balancing: SMOTE + Random Oversampling.

Models Tested: Logistic Regression, Decision Tree, Random Forest, XGBoost, LightGBM, KNN, Naive Bayes.

Evaluation: Weighted F1-score and ROC-AUC.

Model Explainability: Feature importance from tree-based models.

## 📊 Key Findings

LightGBM performed best (F1-score = 0.79, ROC-AUC = 0.69).

Most influential features:

Number of casualties

Number of vehicles involved

Vehicle service year

Driver age band

Day of the week, junction type

Light and lane conditions

Accident severity depends on human, vehicle, and environmental factors combined.

## 📈 Results

Model	F1-Score

Logistic Regression	0.58

Decision Tree	0.75

Random Forest	0.78

XGBoost	0.79

LightGBM	0.79

KNN	0.36

Naive Bayes	0.21

## 🖊 Conclusion: 
LightGBM is the most reliable model for predicting accident severity.

## 🙋‍♀️Author:
Sonia Firdous
soniafirdous1985@gmail.com

