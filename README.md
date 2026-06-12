# Skin Disorder Prediction Using Machine Learning

## Project Overview

Skin diseases often exhibit similar clinical and histopathological characteristics, making accurate diagnosis a challenging task. This project aims to develop a machine learning-based system for predicting different types of skin disorders using dermatological attributes.

The proposed system analyzes clinical and histopathological features and classifies patients into one of six skin disease categories. Multiple machine learning algorithms were evaluated, and the Support Vector Machine (SVM) model was selected as the final model based on its superior performance.

---

## Problem Statement

Develop a predictive model capable of accurately classifying various skin disorders using clinical and histopathological attributes.

---

## Dataset Information

* **Domain:** Healthcare
* **Number of Records:** 366
* **Number of Features:** 34
* **Target Classes:** 6

### Diseases Included

1. Psoriasis
2. Seboreic Dermatitis
3. Lichen Planus
4. Pityriasis Rosea
5. Chronic Dermatitis
6. Pityriasis Rubra Pilaris

---

## Project Workflow

1. Data Loading
2. Dataset Exploration
3. Missing Value Analysis
4. Target Variable Analysis
5. Exploratory Data Analysis (EDA)
6. Feature and Target Separation
7. Data Preprocessing
8. Model Development
9. Model Evaluation
10. Model Comparison
11. Feature Selection Analysis
12. Confusion Matrix Analysis
13. Classification Report Analysis
14. Final Model Selection
15. Model Saving

---

## Machine Learning Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* AdaBoost
* Extra Trees
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost

---

## Model Performance Comparison

| Model                  | Accuracy |
| ---------------------- | -------- |
| Support Vector Machine | 97.3%    |
| Logistic Regression    | 95.9%    |
| Decision Tree          | 95.9%    |
| Random Forest          | 95.9%    |
| Extra Trees            | 95.9%    |
| Gradient Boosting      | 93.2%    |
| XGBoost                | 93.2%    |
| K-Nearest Neighbors    | 91.9%    |
| Naive Bayes            | 86.5%    |
| AdaBoost               | 55.4%    |

---

## Best Model

### Support Vector Machine (SVM)

* Accuracy: **97.3%**
* Precision: **97.7%**
* Recall: **97.3%**
* F1-Score: **97.3%**
* Cross Validation Score: **96.4%**

The SVM model demonstrated excellent predictive performance and strong generalization capability, making it the most suitable model for deployment.

---

## Feature Selection Analysis

Feature selection was performed using the SelectKBest technique with the ANOVA F-test.

However, reducing the feature set from 34 features to the top 10 features caused a significant reduction in prediction accuracy.

Therefore, all 34 features were retained in the final model.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Joblib
* Jupyter Notebook

---

## Model File

The trained Support Vector Machine model has been saved as:

`skin_disorder_svm_model.pkl`

---

## Future Scope

* Integration with Electronic Medical Records (EMR)
* Web-based clinical decision support systems
* Deep learning approaches using CNN models
* Explainable AI techniques
* Real-time healthcare applications

---

## Conclusion

The project demonstrates that machine learning techniques can effectively assist healthcare professionals in the early identification and classification of skin disorders. Among all the evaluated algorithms, the Support Vector Machine achieved the best performance with an accuracy of 97.3%, making it suitable for healthcare decision support applications.
