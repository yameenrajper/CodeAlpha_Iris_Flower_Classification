# CodeAlpha_Iris_Flower_Classification

This project is part of the **CodeAlpha Data Science Internship**. It focuses on building a Machine Learning model using the Iris dataset to classify flower species based on sepal and petal measurements.

---

## 📌 Task Description
- **Task 1:** Iris Flower Classification
- **Domain:** Data Science / Machine Learning
- **Objective:** Train a Machine Learning model to classify Iris flowers into three species (`setosa`, `versicolor`, `virginica`) using physical measurements.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Libraries Used:**
  - `pandas` - Data manipulation
  - `scikit-learn` - Machine learning model, dataset loading, and evaluation metrics

---

## 📊 Dataset Information
The dataset used is the standard **Iris Dataset** provided directly by Scikit-Learn.
- **Features:**
  1. Sepal Length (cm)
  2. Sepal Width (cm)
  3. Petal Length (cm)
  4. Petal Width (cm)
- **Target Classes:**
  - `0`: Setosa
  - `1`: Versicolor
  - `2`: Virginica

---

## 🚀 Model Details & Workflow
1. **Data Loading:** Loaded the Iris dataset into a pandas DataFrame.
2. **Data Splitting:** Split the dataset into 80% Training set and 20% Testing set using `train_test_split`.
3. **Model Selection:** Applied **Random Forest Classifier** (`RandomForestClassifier`) for multi-class classification.
4. **Evaluation:** Evaluated model performance using Accuracy Score and Classification Report.

---

## 📈 Results
- **Model Accuracy:** 100%
- **Evaluation Metrics:** Detailed Precision, Recall, and F1-Score produced via `classification_report`.

---

## 💻 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/CodeAlpha_Iris_Flower_Classification.git](https://github.com/YOUR_USERNAME/CodeAlpha_Iris_Flower_Classification.git)
   cd CodeAlpha_Iris_Flower_Classification
