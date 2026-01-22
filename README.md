# Credit Card Fraud Detection

This project detects fraudulent credit card transactions using Machine Learning.
It solves a real-world problem where fraud cases are very rare compared to normal transactions.

This notebook is designed to run on **Google Colab**.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]


https://colab.research.google.com/drive/1tAl0hfmUJyDrwR4X883ouTNABMX3IKXa

---

## Objective

To build a machine learning model that can:
- Identify fraudulent transactions
- Handle highly imbalanced data
- Improve fraud detection accuracy and recall

---

## Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Files

ML_PROJECT/
│
├── CREDIT_CARD_FRAUD_DETECTION.ipynb
└── README.md


---

## 📊 Dataset Description

### Dataset Source

The dataset used in this project is publicly available on Kaggle:

🔗 https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

- The dataset contains anonymized credit card transactions
- All features are numerical
- Target column:
  - `0` → Legitimate transaction
  - `1` → Fraudulent transaction
- The dataset is highly imbalanced

---

## 🔄 Steps Performed

1. Imported required libraries
2. Loaded and explored the dataset
3. Data preprocessing and scaling
4. Exploratory Data Analysis (EDA)
5. Train-test split
6. Machine Learning model training
7. Model evaluation

---

## 🤖 Machine Learning Model

- Classification-based approach
- Performance evaluated using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

> Recall is given higher importance because missing fraud cases can cause financial loss.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Sangeethabarla/ML_PROJECT.git
2. Navigate to the project folder:
   ```bash
   cd ML_PROJECT

3. Open the notebook in Google Colab:
   - Visit https://colab.research.google.com
   - Open the notebook from GitHub
   - Select `CREDIT_CARD_FRAUD_DETECTION.ipynb`

## ✅ Results

The model successfully identifies fraudulent transactions

Works well on imbalanced data

Suitable for real-world fraud detection use cases

## 🚀 Future Enhancements

Use advanced models like Random Forest or XGBoost

Apply SMOTE for better imbalance handling

Deploy the model using Flask or Streamlit

Enable real-time fraud prediction

## 👩‍💻 Author

Sangeetha Barla
Aspiring Software Engineer | Machine Learning Enthusiast

## 📌 Conclusion

This project demonstrates how Machine Learning can be effectively applied to detect financial fraud by combining data analysis, preprocessing, and classification techniques.


