# 💓 Heart Disease Prediction using Machine Learning

This project focuses on predicting the presence of heart disease using the **Cleveland Heart Disease Dataset** from the UCI Machine Learning Repository. It leverages a **Random Forest Classifier** to identify whether a patient is at risk based on several medical attributes.

---

## 📊 Dataset Description

- **Source:** UCI Machine Learning Repository
- **Dataset Used:** Processed Cleveland Heart Disease Data
- **Records:** 303 patients
- **Goal:** Predict whether a patient has heart disease (binary classification: 0 = No, 1 = Yes)

---

## 📚 Features Used

| Feature     | Description |
|-------------|-------------|
| `age`       | Patient's age (in years) |
| `sex`       | 1 = Male, 0 = Female |
| `cp`        | Chest pain type (0 = typical angina to 3 = asymptomatic) |
| `trestbps`  | Resting blood pressure (mm Hg) |
| `chol`      | Serum cholesterol (mg/dL) |
| `fbs`       | Fasting blood sugar > 120 mg/dL (1 = Yes, 0 = No) |
| `restecg`   | Resting ECG results |
| `thalach`   | Maximum heart rate achieved |
| `exang`     | Exercise-induced angina (1 = Yes, 0 = No) |
| `oldpeak`   | ST depression induced by exercise |
| `slope`     | Slope of the peak exercise ST segment |
| `ca`        | Number of major vessels colored by fluoroscopy |
| `thal`      | Thalassemia (1 = fixed defect, 2 = reversible defect, 3 = normal) |
| `target`    | Heart disease presence (0 = No, 1 = Yes) |

---

## 🛠 Tools & Technologies Used

- **Language:** Python
- **Libraries:**  
  - `pandas` – for data loading and manipulation  
  - `scikit-learn` – for model building, training, evaluation  
  - `joblib` – for saving and loading the trained model  

- **Model Used:** Random Forest Classifier  
- **IDE/Environment:** Jupyter Notebook / VS Code

---

## 🧪 Process Overview

1. **Data Loading:** Fetched the raw data from UCI repository.
2. **Data Cleaning:** Removed missing values and converted all data types appropriately.
3. **Feature Selection:** Selected 13 key features plus one target column.
4. **Target Conversion:** Converted multiclass target into binary classification (0 = no disease, 1 = disease).
5. **Model Training:** Trained a Random Forest Classifier with balanced class weights.
6. **Evaluation:** Used classification report and confusion matrix for evaluation.
7. **Model Saving:** Saved the trained model using `joblib`.
8. **Prediction:** Took custom user input and predicted the risk level of heart disease.
9. **Interpretation:** Displayed confidence score and risk category (Low, Moderate, or High).

---

## 📈 Output Insights

- Model provides predictions along with confidence probabilities.
- Risk is categorized based on the prediction confidence:
  - **High Risk:** Confidence > 70%
  - **Moderate Risk:** Confidence between 30%–70%
  - **Low Risk:** Confidence < 30%

---


## 🧠 Learning Outcomes

- Worked with real clinical data and handled missing values.
- Understood the complete ML lifecycle: preprocessing → training → evaluation → deployment.
- Gained insights into how to interpret ML predictions in healthcare scenarios.

---

## 🧾 Author

Developed by Bensun
For educational and demonstration purposes.
