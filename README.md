# Diabetes Prediction Using Random Forest

This project implements a machine learning model to predict the likelihood of diabetes in patients based on specific health metrics.

---

## Project Overview

The model utilizes the **Random Forest Classifier** algorithm to perform binary classification. By analyzing features such as glucose levels, BMI, and age, the system determines whether a patient is likely to be diabetic.

### Performance

* **Model:** Random Forest Classifier
* **Accuracy:** 82%

---

## Dataset Features

The model is trained on the following health indicators:

* **Pregnancies:** Number of times pregnant
* **Glucose:** Plasma glucose concentration
* **BloodPressure:** Diastolic blood pressure (mm Hg)
* **SkinThickness:** Triceps skin fold thickness (mm)
* **Insulin:** 2-hour serum insulin (mu U/ml)
* **BMI:** Body mass index (weight in $kg/(height in m)^2$)
* **DiabetesPedigreeFunction:** Diabetes genetic score
* **Age:** Patient age (years)

---

## Model Architecture

The Random Forest algorithm operates by constructing a multitude of decision trees during training and outputting the class that is the mode of the classes of the individual trees.

---

## Installation & Usage

1. **Clone the repository:**
```bash
git clone https://github.com/Gopal-next/Diabetes-Prediction.git

```


2. **Install dependencies:**
```bash
pip install pandas scikit-learn numpy

```


3. **Run the script:**
```bash
python predict.py

```



---

## Results

The model achieved an accuracy of **82%** on the test dataset. Further optimization can be performed using **Hyperparameter Tuning** (GridSearchCV) to improve the precision and recall scores.
