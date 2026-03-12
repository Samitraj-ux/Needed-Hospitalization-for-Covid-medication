# Needed-Hospitalization-for-Covid-medication
Prediction of need of hospitalization of covid patient
# COVID Hospitalization Prediction

This project uses patient data (age, body temperature, chronic disease, breathing issues, blood oxygen levels) to predict whether hospitalization is needed.

## Dataset
- Source: `Covid_Data_new.xlsx`
- Features: age, body_temperature, chronic_disease, breathing_issue, Blood O2 Level
- Target: Needed Hospitalization (Yes/No)

## Workflow
1. **Preprocessing**: Handle missing values, encode categorical features.
2. **Modeling**: Logistic Regression baseline.
3. **Evaluation**: Precision, Recall, F1, Accuracy, Confusion Matrix.

## Results
- Logistic Regression
- KNeighborsClassifier
- GaussianNB
- Confusion Matrix showed perfect classification:

- After anaylsis KNeighborsClassifier is best classifier above all with:
- Precision:  0.8823529411764706
- Recall:  1.0
- F1 score:  0.9375
- Accuracy:  0.9428571428571428
- CM:  [[18  2]
-   ,  [ 0 15]]
