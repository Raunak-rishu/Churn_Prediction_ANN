## **📌 Customer Churn Prediction (ANN + Streamlit)**

This project is a **Customer Churn Prediction system** built using an **Artificial Neural Network (ANN)** and deployed with **Streamlit**.
The app predicts the probability of a customer leaving a company based on key customer attributes.

---

## 🚀 Features

* Trained ANN model using TensorFlow
* Same preprocessing pipeline used during training
* Interactive Streamlit web interface
* Predicts **churn probability** and churn status

---

## 🛠 Tech Stack

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* Streamlit

---

## 📂 Project Structure

```
├── app.py
├── saved_model/
│   ├── model.h5
│   └── preprocessor.pkl
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation Steps

1️⃣ **Clone the repository**

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

2️⃣ **Create and activate a virtual environment (optional but recommended)**

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

3️⃣ **Install dependencies**

```bash
pip install -r requirements.txt
```

4️⃣ **Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. User enters customer details via the Streamlit UI
2. Input data is preprocessed using the saved `preprocessor.pkl`
3. The trained ANN model predicts churn probability
4. The app displays whether the customer is **likely to churn or not**