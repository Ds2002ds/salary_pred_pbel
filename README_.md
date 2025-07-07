
# 💼 Salary Prediction App

This desktop application predicts employee salaries based on various personal and professional attributes using machine learning. It uses ensemble techniques (Random Forest and Gradient Boosting) to increase prediction accuracy, and features a user-friendly GUI built with Tkinter.

---

## 📊 Features

- Predicts salaries based on multiple attributes like job title, experience, education, etc.
- GUI for easy interaction – no coding knowledge required.
- Uses ensemble models (Random Forest + Gradient Boosting) via a Voting Regressor.
- Preprocessing pipeline for handling missing values, categorical data, and scaling.

---

## 🧠 Machine Learning Model

- **Preprocessing**:
  - Numerical: Mean imputation + Standard Scaler
  - Categorical: Most frequent imputation + One-hot encoding
- **Model Used**:
  - Voting Regressor combining:
    - Random Forest Regressor
    - Gradient Boosting Regressor

---

## 📝 Input Features

The following features are taken as input through the GUI:

- **Education Level**
- **Years of Experience**
- **Job Title**
- **Industry**
- **Location**
- **Company Size**
- **Certifications**
- **Age**
- **Working Hours per Week**
- **Crucial Code**

---

## 📁 Dataset

The app uses a dataset named `salary_train.csv` with at least the following columns:

- `ID`
- `salary` (target column)
- `education_level`
- `years_experience`
- `job_title`
- `industry`
- `location`
- `company_size`
- `certifications`
- `age`
- `working_hours`
- `crucial_code`

Ensure the dataset is placed in the **same directory** as the script.

---

## 🚀 How to Run

1. Clone the repository or download the code.
2. Make sure Python is installed with the required libraries.
3. Install required packages:
   ```bash
   pip install pandas scikit-learn
   ```
4. Run the script:
   ```bash
   python salary_prediction_gui.py
   ```
5. Fill in the GUI form and click **"Predict Salary"** to see the result.

---

## 🖼️ GUI Preview

![Salary Prediction GUI](Screenshot%20from%202025-07-07%2016-10-27.png)

---

## 📦 Dependencies

- `pandas`
- `scikit-learn`
- `tkinter` (comes with standard Python installation)

---

## 📜 License

This project is open-source and free to use for personal and educational purposes.

---

## 🙋‍♂️ Author

Developed by **Deepanshu Sharma**.

---
