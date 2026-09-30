# ChurnSense

ChurnSense is a machine learning project that predicts whether a bank customer is likely to leave the bank based on demographic, financial, and account-related information.

The project uses the **Churn Modelling dataset** and demonstrates the complete machine learning workflow, including data preprocessing, feature encoding, feature scaling, model training, and performance evaluation.(ML MODEL)

## 📌 Project Objective

Customer churn is an important business problem for banks. Identifying customers who are likely to leave can help banks take preventive actions and improve customer retention.

The objective of this project is to build a machine learning model that predicts the `Exited` status of a customer.

- `0` → Customer stayed with the bank
- `1` → Customer left the bank

## 📊 Dataset

The dataset contains information about bank customers, including:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Member Status
- Estimated Salary

### Target Variable

`Exited`

This is the target variable used for predicting customer churn.

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

## 🔄 Machine Learning Workflow

The project follows these major steps:

1. Data loading
2. Exploratory data analysis
3. Data preprocessing
4. Encoding categorical variables
5. Feature selection
6. Feature scaling
7. Train-test split
8. Neural network model creation
9. Model compilation
10. Model training
11. Model evaluation
12. Churn prediction

## 🧠 Model

An Artificial Neural Network (ANN) is used for binary classification.

The model uses:

- **ReLU** activation in hidden layers
- **Sigmoid** activation in the output layer
- **Adam** optimizer
- **Binary Cross-Entropy** loss function
- **Accuracy** as an evaluation metric

## 📁 Project Structure

```text
ChurnSense/
│
├── churn_prediction.ipynb
├── README.md
└── requirements.txt
