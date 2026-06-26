# Project Data Analysis

## heart.csv

This dataset provides various information about patients, including age, gender, blood pressure, cholesterol levels, electrocardiographic (ECG) features, and more.

### Data Features

* **age**: The age of the patient.
* **sex**: Gender of the patient (0: female, 1: male).
* **cp**: Type of chest pain.
* **trestbps**: Resting blood pressure.
* **chol**: Serum cholesterol.
* **fbs**: Fasting blood sugar > 120 mg/dl.
* **restecg**: Resting electrocardiographic results.
* **thalach**: Maximum heart rate achieved.
* **exang**: Exercise induced angina.
* **oldpeak**: ST depression induced by exercise relative to rest.

### Data structure

* Rows = 1025
* Columns = 14

### Statistical Analysis

1. Average age : 54

```
df['age'].mean()
```

2. Average cholestrol : 246

```
df['chol'].mean()
```
3. Average heart rate achieved : 149

```
df['thalach'].mean()
```
