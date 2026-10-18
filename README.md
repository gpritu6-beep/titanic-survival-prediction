 Titanic Survival Prediction

Predict whether a passenger survived the Titanic (binary classification).

 Key Findings
- Sex was the strongest signal (female 74% vs male 19% survival)
- Higher class meant higher survival (1st: 63%, 3rd: 24%)
- Missing `deck` was itself informative, so I kept it as a flag
- `fare` was right-skewed, fixed with a log transform

 1)Models
 Model & Test accuracy 

 Logistic Regression =  80.9% 
 Random Forest (tuned) = 80.9% 

2) Workflow
EDA, cleaning, encoding, train-test split, model training, cross-validation, tuning, feature importance

3) Files
- `Titanic_Survival_Prediction.ipynb`: full notebook
- `titanic_rf_model.pkl`: trained Random Forest

4) Tools
pandas, seaborn, matplotlib, scikit-learn
