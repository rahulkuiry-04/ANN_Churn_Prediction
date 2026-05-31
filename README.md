# 🚀 Customer Churn Prediction using Artificial Neural Networks (ANN)

## 📌 Project Overview

Customer retention is a critical challenge for businesses. This project uses a Deep Learning-based Artificial Neural Network (ANN) to predict whether a customer is likely to leave a bank based on demographic and financial information.

The model is deployed as an interactive Streamlit web application where users can input customer details and receive real-time churn predictions.

---

## 🎯 Business Problem

Acquiring new customers is often more expensive than retaining existing ones.

This project helps businesses identify customers at risk of churning so that proactive retention strategies can be implemented.

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* Scikit-Learn
* Pandas
* NumPy
* Streamlit
* Pickle

---

## 📊 Features Used

The model predicts churn using:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary

---

## 🔄 Data Preprocessing

✔ Label Encoding

✔ One-Hot Encoding

✔ Feature Scaling using StandardScaler

✔ Train-Test Split

---

## 🧠 ANN Architecture

Input Layer

⬇

Hidden Layer (ReLU)

⬇

Hidden Layer (ReLU)

⬇

Output Layer (Sigmoid)

The model outputs a probability score indicating the likelihood of customer churn.

---

## 🌐 Streamlit Application

The application allows users to:

* Select customer demographics
* Enter financial details
* Predict churn probability instantly
* Receive churn classification results

---

## 📷 Application Live Demo

-->https://annchurnprediction-c6qrmt4tonjuhfwk5tokjp.streamlit.app/




## 📂 Project Structure

```text
ANN_Churn_Prediction/
│
├── app.py
├── experiments.ipynb
├── prediction.ipynb
├── model.h5
├── requirements.txt
├── scaler.pkl
├── onehot_encoder_geo.pkl
├── label_encoder_gender.pkl
├── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/rahulkuiry-04/ANN_Churn_Prediction.git
cd ANN_Churn_Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📈 Model Output

The model returns:

* Churn Probability
* Customer Churn Prediction (Yes/No)

Example:

```text
Churn Probability: 0.82

The customer is likely to churn.
```

---

## 🚀 Future Improvements

* Hyperparameter Tuning
* Model Explainability (SHAP)
* Docker Deployment
* CI/CD Pipeline
* Cloud Deployment (AWS/GCP/Azure)

---

## 👨‍💻 Author

Rahul Kuiry

GitHub: https://github.com/rahulkuiry-04

If you found this project useful, consider giving it a ⭐.
