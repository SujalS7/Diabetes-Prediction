# Diabetes-Prediction
This project focuses on building and comparing different machine learning models to predict the onset of diabetes based on diagnostic measurements. The dataset used is the Pima Indians Diabetes Database.

# Project Steps
The following steps were performed in this project:

# Data Loading and Exploration: The dataset was loaded and initial exploration was performed to understand the data distribution and identify potential issues like missing values (represented as zeros in this dataset).
# Data Preprocessing: Features were scaled using StandardScaler to ensure all features contribute equally to the model training. The data was split into training and testing sets (80-20 split).
# Model Training: Three different classification models were trained on the scaled training data:
Decision Tree Classifier
Support Vector Machine (SVM)
Random Forest Classifier
# Model Evaluation: The performance of each model was evaluated using various metrics, including:
Accuracy
Precision
Recall
F1-score
ROC AUC Score
Confusion Matrices were visualized for each model.
ROC curves were plotted to compare the trade-off between true positive rate and false positive rate.
# Model Comparison: The performance metrics of the three models were compared to identify the best-performing model for this dataset. The Random Forest model showed the best overall performance.
