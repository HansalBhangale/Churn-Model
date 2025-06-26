
# 🧠 Customer Churn Prediction App

🔗 **Live Demo**: [Streamlit App](https://churn-model-c7q6z6rcubmrvimqtspa96.streamlit.app/)

This project is a deployed deep learning model built to predict whether a customer will churn from a bank. It uses customer data like age, credit score, balance, and more to make a prediction using a deep learning model trained in TensorFlow.

---

## 🚀 Features

- Interactive Streamlit interface
- Predicts **churn probability**
- Provides a **clear decision** (likely to churn or not)
- Preprocessing pipeline includes:
  - StandardScaler
  - LabelEncoder
  - OneHotEncoder
- Accepts the following user inputs:
  - Geography
  - Gender
  - Age
  - Balance
  - Credit Score
  - Estimated Salary
  - Tenure
  - Number of Products
  - Has Credit Card
  - Is Active Member

---

## 📦 Project Structure

```
├── app.py                      # Streamlit application script
├── model.h5                   # Trained TensorFlow model
├── scaler.pkl                 # StandardScaler for feature normalization
├── label_encoder_geo.pkl      # LabelEncoder for gender
├── ohe_geo.pkl                # OneHotEncoder for geography
├── experiments.ipynb          # Jupyter notebook for training and evaluation
```

---

## 🧪 Model & Preprocessing

The model is a neural network built with TensorFlow/Keras and trained on customer banking data. Input features are scaled and encoded before being passed to the model. The output is a **probability score** indicating the likelihood of churn.

---


## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **TensorFlow/Keras**
- **Scikit-learn**
- **Pandas**
- **Pickle**

---

