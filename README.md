CUSTOMER CHURN PREDICTION USING MACHINE LEARNING

A complete end-to-end Machine Learning project that predicts whether a customer is likely to churn based on customer demographics and subscription details. The project covers the full ML pipeline, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, model serialization, and deployment through a Streamlit web application.

PROJECT OVERVIEW

Customer churn prediction helps businesses identify customers who are likely to discontinue their services. By predicting churn in advance, organizations can implement retention strategies and improve customer satisfaction.

This project demonstrates the complete machine learning lifecycle, from raw data preprocessing to deploying a trained model as an interactive web application.

FEATURES

- Data cleaning and preprocessing
- Missing value and duplicate handling
- Exploratory Data Analysis (EDA)
- Feature scaling using StandardScaler
- Model training with multiple Machine Learning algorithms
- Model performance evaluation
- Model serialization using Joblib
- Interactive Streamlit web application
- Real-time customer churn prediction

TECH STACK

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib
- Matplotlib
- Seaborn

PROJECT STRUCTURE

Customer-Churn-Prediction/
│── notebook.ipynb                                           # Complete ML workflow

│── app.py                                                   # Streamlit application

│── model.pkl                                                # Trained model

│── scaler.pkl                                               # StandardScaler object

│── customer_churn_data.csv # Dataset

│── requirements.txt

│── README.md

MACHINE LEARNING WORKFLOW

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering & Preprocessing
5. Train-Test Split
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Model Saving with Joblib
10. Streamlit Deployment

INPUT FEATURES

- Age
- Gender
- Tenure
- Monthly Charges

PREDICTION

The application predicts whether a customer is:

- Churn
- Not Churn

RUNNING THE PROJECT

Clone the repository

git clone https://github.com/yourusername/customer-churn-prediction.git

Navigate into the project

cd customer-churn-prediction

Install dependencies

pip install -r requirements.txt

Launch the Streamlit app

streamlit run app.py

FUTURE IMPROVEMENTS

- Hyperparameter tuning
- Feature importance visualization
- Cross-validation
- Probability score for predictions
- Cloud deployment
- Support for additional customer features

Author :

Abhirami Anand
