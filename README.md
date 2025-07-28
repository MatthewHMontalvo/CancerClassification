# CancerClassification
This project uses Scikit-Learn (sklearn) to build and evaluate machine learning models that classify breast cancer cells as malignant or benign. The dataset is derived from digitized images of fine needle aspirate (FNA) of breast masses and includes 30 numerical features computed from each image.


# Objective
To develop a supervised machine learning model that accurately predicts cancer type (malignant vs. benign) based on FNA-derived features.

# Project
[ cancerClassification_scikitML.ipynb ] 
Jupyter Notebook containing:

-Data loading and exploration

-Model training (Gaussian Naive Bayes, Logistic Regression, Random Forest)

-Evaluation (accuracy, ROC-AUC, confusion matrix)

-Visualization of performance metrics


# Dataset
Source: Breast Cancer Wisconsin (Diagnostic) Data Set (Imported from sklearn)

Samples: 569

Classes:

-Malignant (212)
-Benign (357)


# Machine Learning Models Used

-GaussianNB (Gaussian Naive Bayes)

-LogisticRegression

-RandomForestClassifier



Each model is trained and evaluated using:

-Train/Test split (80/20)

-Accuracy Score

-Classification Report (Precision, Recall, F1-score)

-Confusion Matrix

-ROC Curve and AUC score
