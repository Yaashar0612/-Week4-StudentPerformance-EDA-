1. The target variable `Attrition` is used to predict whether an employee will leave.
2. SMOTE ensures that the model is not biased toward the majority (non-leaving) class.
3. Label encoding converts text categories like `JobRole` and `OverTime` into numeric form.
4. The dataset is split into training and testing sets using `train_test_split()`.
5. Random state is set to ensure consistent results on every run.
6. XGBoost is configured with `use_label_encoder=False` to avoid deprecation warnings.
7. Evaluation focuses on **recall** to reduce false negatives in predicting attrition.
8. `seaborn` is used for attractive and informative visualizations like countplots.
9. Heatmap shows correlations between features such as age, salary, and attrition.
10. The project ends with a clean, commented notebook ready for GitHub submission.
