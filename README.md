# Employee Performance Analysis

## Project Overview
This project aims to analyze employee performance data and build a machine learning model to predict employee performance ratings. The objective is to identify key factors influencing employee performance and develop a reliable predictive model that can support organizational decision-making.

---

## Dataset Description
- **Dataset Name:** INX Future Inc Employee Performance Dataset  
- **Total Records:** 1200  
- **Target Variable:** PerformanceRating  
- **Description:**  
  The dataset contains employee demographic, job-related, experience-related, and satisfaction-related attributes used to evaluate employee performance.

---

## Methodology

### 1. Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Applied feature scaling
- Handled class imbalance using SMOTE

### 2. Exploratory Data Analysis (EDA)
- Analyzed department-wise employee performance
- Identified key factors affecting performance such as salary hike, work-life balance, and environment satisfaction
- Visualized patterns and trends in employee performance

### 3. Model Training and Evaluation
- Trained multiple machine learning models including Logistic Regression, Decision Tree, SVC, Random Forest, Gradient Boosting, ANN, and LightGBM
- Evaluated models using accuracy, precision, recall, and F1-score

### 4. Hyperparameter Tuning and Validation
- Performed hyperparameter tuning on Random Forest and LightGBM
- Applied cross-validation to ensure model stability and consistency

---

## Final Model Selection
The hyperparameter-tuned **Random Forest Classifier** was selected as the final model due to its high accuracy, robust performance, and stable cross-validation results.

---

## Recommendations
- Organizations should provide performance-linked salary hikes, as higher salary increments are associated with better employee performance.
- Improving work-life balance through flexible work policies can enhance employee productivity.
- Enhancing the work environment and employee satisfaction initiatives can lead to sustained high performance.

---

## Project Summary & Conclusion
In this project, employee performance data was analyzed to identify key factors influencing performance ratings. After preprocessing and exploratory analysis, multiple machine learning models were trained and evaluated. Hyperparameter tuning and cross-validation were applied to improve and validate model performance. The tuned Random Forest model was selected as the final model and successfully used to predict employee performance ratings, demonstrating readiness for real-world deployment.

---

## How to Run the Project
1. Run `data_preprocessing.ipynb` to preprocess the dataset
2. Run `eda.ipynb` to perform exploratory data analysis
3. Run `train_model.ipynb` to train and evaluate models
4. Run `predict_model.ipynb` to generate predictions using the saved model

---

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
- lightgbm
