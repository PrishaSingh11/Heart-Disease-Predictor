# Heart Disease Predictor

This repository contains a machine learning project aimed at predicting the presence of heart disease in patients based on a set of clinical attributes. The notebook (`heart-disease-predictor.ipynb`) provides a complete workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and interpretation of results.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Feature Summary](#feature-summary)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [License](#license)

---

## Project Overview

Heart disease is one of the leading causes of death globally. Early detection is critical to effective treatment and prevention. This project utilizes machine learning techniques to predict heart disease using various patient data. Multiple algorithms are explored, and performance metrics are analyzed to determine the most accurate and reliable model.

---

## Dataset Description

The dataset used in this project is derived from publicly available heart disease datasets, commonly used in academic and clinical studies. Each record represents a patient and includes features that capture both demographic and medical information.

- **Number of Instances**: [Insert number of rows]
- **Number of Features**: [Insert number of columns minus target]

---

## Feature Summary

| Feature         | Description                                             |
|-----------------|---------------------------------------------------------|
| Age             | Age of the patient in years                             |
| Sex             | Gender (1 = Male, 0 = Female)                           |
| cp              | Chest pain type (0-3 categories)                        |
| trestbps        | Resting blood pressure (mm Hg)                          |
| chol            | Serum cholesterol level (mg/dl)                         |
| fbs             | Fasting blood sugar > 120 mg/dl (1 = True, 0 = False)   |
| restecg         | Resting electrocardiographic results (0-2)              |
| thalach         | Maximum heart rate achieved                             |
| exang           | Exercise-induced angina (1 = Yes, 0 = No)               |
| oldpeak         | ST depression induced by exercise relative to rest      |
| slope           | Slope of the peak exercise ST segment (0-2)             |
| ca              | Number of major vessels colored by fluoroscopy (0-3)    |
| thal            | Thalassemia (1 = Normal; 2 = Fixed defect; 3 = Reversible defect) |
| target          | Heart disease (1 = Presence, 0 = Absence)               |

---

## Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling (standardization or normalization)

2. **Exploratory Data Analysis**
   - Correlation heatmaps
   - Distribution plots
   - Boxplots for outlier detection

3. **Model Training**
   - Algorithms tested: Logistic Regression, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), etc.
   - Hyperparameter tuning (GridSearchCV or RandomizedSearchCV)

4. **Model Evaluation**
   - Performance Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
   - Confusion Matrix analysis

---


## Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Libraries**:
  - Pandas, NumPy (data manipulation)
  - Matplotlib, Seaborn (visualization)
  - Scikit-learn (modeling and evaluation)

---

## License

This project is open-source and available under the [MIT License](LICENSE).
