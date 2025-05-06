# Loan Status Prediction using Machine Learning

This project demonstrates how to build a machine learning model to predict loan approval status based on various applicant details. It is inspired by a hands-on YouTube tutorial and walks through the full pipeline of loading data, preprocessing, training models, and evaluating performance.

## 📌 Project Overview

- **Objective**: Predict whether a loan application will be approved (`Y`) or rejected (`N`) based on several input features.
- **Tools Used**: Python, Pandas, Scikit-learn, NumPy, Matplotlib, Seaborn
- **ML Algorithms**: Logistic Regression, Decision Tree, Random Forest (selectable)
- **Dataset**: Public loan dataset (typically sourced from platforms like Kaggle or UCI)

## 📂 Folder Structure

```

loan-status-prediction/
├── data/
│   └── loan\_data.csv
├── notebook/
│   └── loan\_prediction.ipynb
├── models/
│   └── trained\_model.pkl
├── README.md
└── requirements.txt

````

## 🔍 Features Used

- Gender
- Marital Status
- Education
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-status-prediction.git
   cd loan-status-prediction
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook notebook/loan_prediction.ipynb
   ```

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix

You can switch between different algorithms and compare their performance within the notebook.

## ✅ Future Improvements

* Add GUI with Streamlit or Flask for deployment
* Hyperparameter tuning using GridSearchCV
* Handle imbalanced data using SMOTE or class weights

