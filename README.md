# Titanic Survival Prediction

Predict whether a passenger survived (binary classification).

Key findings:
- Sex was the strongest signal (female 74% vs male 19% survival)
- Higher class meant higher survival
- Missing `deck` was itself informative, so I kept it as a flag

Models: Logistic Regression (80.9%), Random Forest tuned (80.9%)
Tools: pandas, seaborn, scikit-learn
