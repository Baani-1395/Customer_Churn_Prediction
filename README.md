# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to **churn (leave the company)** or **stay with the company** based on customer information. This project demonstrates the complete machine learning pipeline, from data preprocessing to model evaluation and prediction.

---

## Overview

Customer churn prediction helps businesses identify customers who are likely to leave their services. By identifying these customers early, companies can take appropriate actions to improve customer retention.

This project includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature encoding
* Machine Learning model training
* Model comparison
* Hyperparameter tuning
* Model evaluation
* Feature importance analysis
* Model saving and prediction

---

## Features

* Customer churn prediction using Machine Learning
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Logistic Regression model
* Random Forest Classifier
* Hyperparameter tuning using GridSearchCV
* ROC Curve and AUC Score evaluation
* Feature Importance visualization
* Save trained model using Joblib
* Predict churn for new customer data

---

## Technologies Used

* Python
* Jupyter Notebook

### Python Libraries

* pandas
* matplotlib
* seaborn
* scikit-learn
* joblib

---

## Dataset

**Dataset:** `Churn_Modelling.csv`

The dataset contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

### Target Variable

**Exited**

* **0** → Customer Stays
* **1** → Customer Churns

---

## Project Structure

Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb      # Jupyter Notebook
├── Churn_Modelling.csv                  # Dataset
├── Churn_model.pkl                      # Trained Machine Learning model
├── label_encoder.pkl                    # Saved Label Encoder
├── README.md                            # Project documentation
├── requirements.txt                     # Required Python libraries
└── Screenshots/
   
---

## Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Clean and preprocess the data
5. Encode categorical features
6. Split data into training and testing sets
7. Train Logistic Regression model
8. Train Random Forest model
9. Compare both models
10. Tune Random Forest using GridSearchCV
11. Evaluate model performance
12. Analyze feature importance
13. Save the trained model
14. Predict churn for new customer data

---

## Machine Learning Models

* Logistic Regression
* Random Forest Classifier

---

## Evaluation Metrics

The models are evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* AUC Score

---



## How to Run

1. Open Jupyter Notebook.

```bash
jupyter notebook
```

2. Open the notebook:

```text
Customer_Churn_Prediction.ipynb
```

3. Run all cells sequentially using **Shift + Enter**.

4. The notebook will:

* Load the dataset
* Perform data preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Train Logistic Regression and Random Forest models
* Compare model performance
* Perform hyperparameter tuning
* Evaluate the trained models
* Save the trained model (`churn_model.pkl`)
* Save the label encoder (`label_encoder.pkl`)
* Predict whether a customer will churn or stay

---

## Output

The project predicts whether a customer is likely to churn and compares multiple Machine Learning models to identify the best-performing model. It also highlights the key factors influencing customer churn.

---

## Future Improvements

* Deploy the model using Flask or Streamlit
* Improve feature engineering
* Use One-Hot Encoding
* Handle class imbalance using SMOTE
* Experiment with advanced models such as XGBoost and LightGBM
* Build a web application for real-time predictions

---

## Author

**Bhawani Singh**

