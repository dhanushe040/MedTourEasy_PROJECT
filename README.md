# MedTourEasy_PROJECT
🔍 Blood Donor Prediction: Model Comparison Summary
In this project, I built and evaluated two models to predict blood donation behavior using the transfusion dataset:

✅ Models Trained
TPOTClassifier: Used automated machine learning to discover the best pipeline optimized for AUC score.

Logistic Regression: Served as a baseline model after applying log normalization to high-variance features.

📊 Performance Comparison
Calculated AUC scores for both models using roc_auc_score.

Sorted the models using Python’s operator.itemgetter to identify the best performer.

🏆 Result
The models were ranked from highest to lowest AUC score, helping guide model selection based on predictive performance.
