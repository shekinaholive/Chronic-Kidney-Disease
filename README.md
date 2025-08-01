# 🩺 Chronic Kidney Disease Detection (IBM Project)

This project aims to detect Chronic Kidney Disease (CKD) using clinical patient data and machine learning, and deploy the model through a Flask web application.

---

## 📊 Dataset
- **Source:** [UCI CKD Dataset](https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease)
- **Records:** 400 patient entries
- **Features:** 25 attributes including:
  - Demographic: `age`, `bp`
  - Lab test values: `sg`, `al`, `su`, `sc`, `bgr`, `bu`, `sod`, `pot`
  - Categorical: `rbc`, `pc`, `htn`, `dm`, `cad`, `appet`, `pe`, `ane`
  - Target: `classification` (ckd / notckd)

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature normalization and scaling

2. **Model Training**
   - Trained multiple ML models: Logistic Regression, Decision Tree, Random Forest, and SVM
   - Model evaluation using accuracy, precision, recall, F1-score

3. **Flask Deployment**
   - Final trained model saved using `joblib`
   - Flask app developed to take user input and predict CKD status
   - HTML templates for form input and result display

---

