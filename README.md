# Customer Churn Prediction with Machine Learning

This project aims to predict **customer churn** for a telecom company using machine learning.  
Customer churn refers to the number of customers who stop using a company’s services during a given time period.  
Predicting churn is crucial for improving customer retention and increasing revenue.

---

##  Methodology

The project includes the following steps:

1. **Data Cleaning & Preprocessing**  
   - Handled missing values and outliers  
   - Removed inconsistencies

2. **Exploratory Data Analysis (EDA)**  
   - Visualized data trends and patterns  
   - Analyzed relationships between features and churn

3. **Feature Engineering**  
   - Created new features to improve model performance

4. **Model Selection**  
   - Trained models like Decision Tree, Logistic Regression, and Random Forest

5. **Hyperparameter Tuning**  
   - Used `RandomizedSearchCV` and `GridSearchCV` to find optimal parameters

6. **Model Evaluation**  
   - Evaluated models using accuracy and error metrics on test data

---

## Results

- The **Decision Tree** model exhibited overfitting.
- **Random Forest** (with `RandomizedSearchCV`) performed best:
  - **Accuracy**: 87%
  - **Incorrect Predictions**: 243 out of 2000
- **GridSearchCV** also achieved 87% accuracy with 246 incorrect predictions.

---

## Conclusion

The final machine learning model enables the telecom company to:

- Predict churn with high accuracy  
- Take proactive steps to retain customers  
- Make informed, data-driven decisions

---

##  Future Work

- Incorporate additional data sources to improve accuracy  
- Enhance feature engineering  
- Build a web-based application for real-time predictions  
- Deploy the model to a cloud platform for scalability and accessibility

---


