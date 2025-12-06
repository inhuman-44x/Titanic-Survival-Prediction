# Titanic Survival Prediction
This project is my end-to-end solution to the classic Kaggle Titanic: Machine Learning from Disaster challenge. My goal with this project was to build a clean and reproducible pipeline workflow to handle data preprocessing, model selection, and prediction without any manual shortcuts or leakage.

### What I Did

I built a fully reproducible ML pipeline that handles preprocessing, model training, and prediction end-to-end.

- **Preprocessing:** Automated missing-value imputation, categorical encoding with `OneHotEncoder`, and feature scaling using a `ColumnTransformer` inside a `Pipeline`.
- **Model Comparison:** Evaluated multiple classifiers (`LogisticRegression`, `RandomForestClassifier`, `SVC`) within a unified pipeline.
- **Hyperparameter Tuning:** Applied `GridSearchCV` with `StratifiedKFold` to optimize model-specific hyperparameters and select the best estimator.
- **Evaluation & Submission:** Validated the final model on a held-out set and generated the final predictions using the same fitted pipeline.

### Kaggle Result

The final submission achieved a **public score of 0.76315**.
