# Customer Churn Prediction

A Machine Learning project that predicts whether a customer is likely to **churn (leave the company)** or **remain with the company** based on customer information. This project demonstrates the complete machine learning workflow, from data preprocessing to model evaluation and prediction.

---

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their services. By predicting churn in advance, companies can take preventive actions to improve customer retention.

This project covers:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Feature encoding
* Model training
* Model comparison
* Hyperparameter tuning
* Model evaluation
* Feature importance analysis
* Saving the trained model
* Predicting churn for new customers

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

The dataset contains customer information including:

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

* **Exited**

  * `0` → Customer Stays
  * `1` → Customer Churns

---

## Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── Churn_Modelling.csv
├── churn_model.pkl
├── label_encoder.pkl
├── README.md
└── requirements.txt
```

---

## Machine Learning Workflow

1. Import required libraries
2. Load the dataset
3. Explore and understand the data
4. Clean and preprocess the data
5. Encode categorical features using LabelEncoder
6. Split the dataset into training and testing sets
7. Train a Logistic Regression model
8. Train a Random Forest model
9. Compare both models
10. Perform hyperparameter tuning using GridSearchCV
11. Evaluate the model using multiple performance metrics
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

## Installation

Clone this repository:

```bash
git clone https://github.com/your-username/Customer-Churn-Prediction.git
```

Go to the project folder:

```bash
cd Customer-Churn-Prediction
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Customer_Churn_Prediction.ipynb
```

Run all cells from top to bottom.

---

## Output

The project predicts whether a customer is likely to churn and compares different machine learning models to determine the best-performing model. It also identifies the most important factors influencing customer churn.

---

## Future Improvements

* Deploy the model using Flask or Streamlit
* Improve feature engineering
* Use One-Hot Encoding
* Handle class imbalance using SMOTE
* Try advanced algorithms such as XGBoost or LightGBM
* Build a user-friendly web application

---

## Author

**Bhawani Singh**

