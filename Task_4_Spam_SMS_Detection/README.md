# 📩 Spam SMS Detection using Machine Learning

## 📖 Project Overview

This project is developed as part of the **CodSoft Machine Learning Internship**.

The objective of this project is to classify SMS messages as either **Spam** or **Normal Message** using Machine Learning techniques. The model learns patterns from previously labeled SMS messages and predicts whether a new incoming message is spam or not.

---

## 🎯 Objective

To build a Machine Learning model that can automatically identify spam SMS messages and help users filter unwanted or fraudulent messages.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- CountVectorizer
- Multinomial Naive Bayes
- Jupyter Notebook (VS Code)

---

## 📂 Dataset

- Dataset: SMS Spam Collection Dataset
- Total Messages: **5169**
- Classes:
  - **Normal Message**
  - **Spam Message**

---

## ⚙️ Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Text Vectorization using CountVectorizer
6. Train-Test Split
7. Model Training using Multinomial Naive Bayes
8. Model Evaluation
9. Save Trained Model
10. Predict Custom Messages

---

## 📈 Model Performance

**Algorithm Used:** Multinomial Naive Bayes

**Accuracy Achieved:** **98.26%**

---

## 🧪 Sample Predictions

### Example 1

**Input**

Congratulations! You have won ₹50,000. Claim your prize now!

**Prediction**

Spam Message

---

### Example 2

**Input**

Hey! I'll reach home in 10 minutes.

**Prediction**

Normal Message

---

## 📁 Project Structure

```
Task_4_Spam_SMS_Detection/
│
├── dataset/
│   └── spam.csv
│
├── spam_sms_detection.ipynb
├── spam_model.pkl
├── vectorizer.pkl
└── README.md
```

---

## 🚀 Future Improvements

- Deploy the model as a web application using Streamlit or Flask.
- Improve accuracy using advanced NLP techniques.
- Add support for real-time SMS prediction.

---

## 👩‍💻 Developed By

**S. Vahini**

B.Tech - Artificial Intelligence & Data Science

CodSoft Machine Learning Internship