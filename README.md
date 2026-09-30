# Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project uses **Machine Learning** to predict the presence of heart disease based on patient-related medical features.

A **Logistic Regression** model is trained on a heart disease dataset and evaluated using different classification metrics.

## 🎯 Objective

The main objective of this project is to build a machine learning classification model that can predict whether a patient has heart disease based on the available input features.

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook
* Matplotlib
* Seaborn

## 📂 Dataset

The project uses a CSV dataset named:

`heart disease.csv`

The target column is:

`target`

The target variable represents the classification outcome used for heart disease prediction.

## 🔄 Project Workflow

1. Import the required libraries.
2. Load the heart disease dataset.
3. Explore the dataset.
4. Separate input features (`X`) and target variable (`y`).
5. Split the dataset into training and testing sets.
6. Train a Logistic Regression model.
7. Generate predictions on the test data.
8. Evaluate the model using:

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion Matrix

## 🤖 Machine Learning Model

### Logistic Regression

Logistic Regression is used as the classification algorithm for predicting the target class.

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

The model uses `random_state=42` to make the train-test split reproducible.

## 📊 Model Evaluation

The model is evaluated using the following metrics:

### Accuracy

Measures the overall percentage of correctly classified samples.

### Precision

Measures how many of the samples predicted as positive are actually positive.

### Recall

Measures how many of the actual positive samples are correctly identified.

### F1-Score

Provides a combined measure of precision and recall.

### Confusion Matrix

The confusion matrix shows the number of:

* True Positives
* True Negatives
* False Positives
* False Negatives

## 📓 Jupyter Notebook

The complete implementation is available in:

`heart_disease_prediction.ipynb`

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/heart-disease-prediction-ml.git
```

### 2. Open the project folder

```bash
cd heart-disease-prediction-ml
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open `heart_disease_prediction.ipynb` and run the cells.

## 📦 Requirements

The main Python libraries required are:

* pandas
* scikit-learn
* matplotlib
* seaborn
* jupyter

## ⚠️ Disclaimer

This project is intended for **educational and demonstration purposes only**. The machine learning model should not be used as a medical diagnostic tool.

## 👩‍💻 Author

**MANISHA U**

---

⭐ If you find this project useful, consider giving the repository a star!
