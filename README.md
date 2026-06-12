# Student Academic Performance Prediction

## Overview

This project was completed as part of the **IDEAS Summer Internship Program 2026**.

The objective of this project is to predict a student's academic performance category using Machine Learning techniques. The project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and interpretation.

---

## Project Information

* **Project Title:** Student Academic Performance Prediction
* **Internship Program:** IDEAS Summer Internship Program 2026
* **Prepared By:** Jaishnav Das
* **Notebook:** Student_Academic_Performance_Prediction.ipynb

---

## Dataset

The dataset was obtained from Kaggle:

Academic Performance Prediction Dataset

The dataset contains information related to students such as:

* Age
* Gender
* Attendance Percentage
* Study Hours
* Previous Scores
* Internet Access
* Extracurricular Participation
* Family Background Factors
* Academic Performance Category

Target Variable:

`performance_category`

---

## Objectives

The main objectives of this project are:

1. Load and explore the dataset.
2. Identify numerical and categorical features.
3. Handle missing values.
4. Encode categorical variables.
5. Scale numerical features.
6. Split the dataset into training and testing sets.
7. Train a Decision Tree Classifier.
8. Evaluate model performance using accuracy.
9. Analyze feature importance.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## Machine Learning Workflow

### Step 1: Data Loading

* Imported the dataset using Pandas.
* Displayed the first five records.

### Step 2: Data Exploration

* Identified numerical columns.
* Identified categorical columns.

### Step 3: Missing Value Handling

* Checked for null values.
* Filled numerical missing values using Median.
* Filled categorical missing values using Mode.

### Step 4: Label Encoding

* Converted categorical data into numerical form using LabelEncoder.

### Step 5: Feature and Target Separation

* Features stored in X.
* Target variable stored in y.

### Step 6: Train-Test Split

* 80% Training Data
* 20% Testing Data

### Step 7: Feature Scaling

* Applied MinMaxScaler.
* Scaled all features between 0 and 1.

### Step 8: Model Training

* Trained a Decision Tree Classifier.
* Used random_state = 42 for reproducibility.

### Step 9: Model Evaluation

* Generated predictions on the test dataset.
* Calculated Accuracy Score.

### Step 10: Feature Importance Analysis

* Extracted feature importance scores.
* Identified the most influential factors affecting student performance.

---

## Results

The Decision Tree Classifier was successfully trained and evaluated on the dataset.

Performance metrics generated:

* Accuracy Score
* Feature Importance Ranking

The model helps identify factors that contribute most significantly to student academic success.

---

## Project Structure

```text
├── Student_Academic_Performance_Prediction.ipynb
├── README.md
└── student_performance_dataset.csv
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/student-performance-prediction.git
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn
```

### Run Notebook

Open the notebook in:

* Google Colab
* Jupyter Notebook
* VS Code

and execute all cells sequentially.

---

## Future Improvements

* Random Forest Classifier
* XGBoost Classifier
* Hyperparameter Tuning
* Cross Validation
* Model Deployment using Flask or Streamlit
* Interactive Dashboard Development

---

## Conclusion

This project demonstrates a complete machine learning pipeline for predicting student academic performance. Through preprocessing, feature engineering, model training, and evaluation, the project provides insights into the factors influencing academic success and showcases the practical application of machine learning in educational analytics.

---

## Author

**Jaishnav Das**

IDEAS Summer Internship Program 2026
