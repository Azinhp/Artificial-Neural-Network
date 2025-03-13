# Diabetes Prediction with Neural Network

This repository contains code to predict diabetes using an Artificial Neural Network (ANN) implemented with scikit-learn's `MLPClassifier`.

## Dataset

The dataset used is `diabetes.csv`, which contains various medical features of patients and their diabetes status.

**Column Descriptions:**

* `Pregnancies`: Number of times pregnant.
* `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
* `BloodPressure`: Diastolic blood pressure (mm Hg).
* `SkinThickness`: Triceps skin fold thickness (mm).
* `Insulin`: 2-Hour serum insulin (mu U/ml).
* `BMI`: Body mass index (weight in kg/(height in m)^2).
* `DiabetesPedigreeFunction`: Diabetes pedigree function.
* `Age`: Age (years).
* `Outcome`: Class variable (0 or 1). 1 indicates diabetes.

## Dependencies

* Python 3.x
* NumPy
* Pandas
* Scikit-learn

Install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn
