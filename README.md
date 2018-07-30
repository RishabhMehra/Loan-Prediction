# Loan-Prediction

This notebook is an analysis for loan prediction problem on Analytics Vidhya.I have used various Data Exploration and Data Cleaning Techniques.The best accurany and cross-validation i achieved was using Random Forest with an accuracy of  83.062%

```

model = RandomForestClassifier(n_estimators=25, min_samples_split=25, max_depth=7, max_features=1)
predictor_var = ['TotalIncome_log','LoanAmount_log','Credit_History','Dependents','Property_Area']
classification_model(model, df,predictor_var,outcome_var)


Accuracy : 83.062%  
Cross-Validation Score : 81.274%


```
