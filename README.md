# Task 15: End-to-End Machine Learning Pipeline

## Objective
Build a complete end-to-end machine learning pipeline that includes preprocessing, model training, evaluation, and model saving.

## Dataset
Breast Cancer Dataset (Scikit-learn built-in dataset)

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn (Pipeline, ColumnTransformer)
- Joblib

## Workflow
1. Loaded dataset and separated features and target.
2. Identified numerical and categorical features.
3. Applied feature scaling using ColumnTransformer.
4. Created a complete ML Pipeline combining preprocessing and Logistic Regression.
5. Split data into train and test sets.
6. Trained the pipeline.
7. Evaluated using Accuracy, Precision, Recall, and F1-score.
8. Saved the trained pipeline model.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

## Deliverables
- Jupyter Notebook with ML pipeline
- Evaluation metrics
- Saved pipeline model (`end_to_end_pipeline.pkl`)

## Conclusion
This task demonstrates how to build a structured and reusable end-to-end machine learning pipeline. Combining preprocessing and model training into a single pipeline ensures consistency and makes the workflow production-ready.
