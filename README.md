Diabetes Prediction using Support Vector Machine (SVM)

Project Overview

This project aims to build a machine learning model to predict diabetes based on the Pima Indians Diabetes Dataset. The model uses the Support Vector Machine (SVM) classifier, which is trained and tested using a variety of preprocessing steps and hyperparameter tuning techniques. The final model’s performance is evaluated using different metrics, including accuracy, precision, recall, and F1-score.

Dataset

The dataset used for this project is the Pima Indians Diabetes Database, which consists of 768 instances with 8 input features and a binary output label (0: No Diabetes, 1: Diabetes). The features include:

Pregnancies: Number of pregnancies
Glucose: Plasma glucose concentration
BloodPressure: Diastolic blood pressure (mm Hg)
SkinThickness: Skin fold thickness (mm)
Insulin: 2-Hour serum insulin (mu U/ml)
BMI: Body Mass Index
DiabetesPedigreeFunction: A function that scores the likelihood of diabetes based on family history
Age: Age in years
Key Steps in the Project

Data Preprocessing:
Loaded and examined the dataset.
Handled missing values and performed exploratory data analysis (EDA).
Visualized the distribution of features using histograms and correlation heatmaps.
Model Selection:
Used Support Vector Machine (SVM) as the classifier.
Applied StandardScaler for feature scaling to standardize the input data.
Hyperparameter Tuning:
Implemented GridSearchCV to tune the hyperparameters of the SVM model, including C, kernel, and gamma.
Model Evaluation:
Split the dataset into training and testing sets using train_test_split.
Evaluated the model's performance using accuracy, precision, recall, and F1-score.
Reported confusion matrix and classification report to understand model performance on both classes (diabetes vs. no diabetes).
Performance Metrics

Accuracy: 73.37%
Precision: 0.77 (for class 0), 0.65 (for class 1)
Recall: 0.83 (for class 0), 0.56 (for class 1)
F1-Score: 0.80 (for class 0), 0.60 (for class 1)
Conclusion

This project successfully demonstrates the use of SVM for predicting diabetes based on clinical data. The model’s performance could be further improved by exploring additional feature engineering, using different machine learning models, and applying more advanced techniques such as cross-validation or neural networks.
