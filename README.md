# 💰 Insurance Cost Prediction Model

## 📌 Overview

This project predicts medical insurance charges based on patient data using machine learning. It applies Linear Regression to estimate continuous healthcare costs accurately.

---

## 📊 Dataset

* Source: Kaggle
* Dataset: Medical Cost Personal Dataset
* Link: https://www.kaggle.com/datasets/mirichoi0218/insurance

### 📁 Features:

* age
* sex
* bmi
* children
* smoker
* region

### 🎯 Target:

* `charges` → Medical insurance cost

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn

---

## 🔍 Project Workflow

1. Data Loading
2. Feature Engineering
3. Encoding (Categorical → Numerical)
4. Feature Scaling
5. Train-Test Split
6. Model Training (Linear Regression)
7. Model Evaluation

---

## 🤖 Model Used

* Linear Regression

  * Suitable for continuous target prediction
  * Simple and interpretable baseline model

---

## 📈 Performance

* R² Score: **~0.82**
* Evaluation Metrics:

  * Mean Squared Error (MSE)
  * Root Mean Squared Error (RMSE)

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/insurance-prediction.git
cd insurance-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Project

```bash
python insurance_model.py
```

---

## 📦 Requirements

* pandas
* numpy
* scikit-learn

---

## 💡 Example Prediction

The model predicts insurance cost based on user inputs like age, BMI, smoking status, etc.

---

## 📌 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Hyperparameter tuning
* Add visualization dashboard
* Deploy using Streamlit

---

## 👤 Author

**Abdul Ahad**

* GitHub: https://github.com/abdul9870

---
