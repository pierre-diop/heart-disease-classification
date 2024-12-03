# heart-disease-classification

## Predicting Heart Disease Using Machine Learning
This project explores the use of various Python-based machine learning and data science libraries to build a model capable of predicting whether a patient has heart disease based on clinical parameters.

### 1. Problem Definition
Can we predict whether or not a patient has heart disease given their clinical parameters?

### 2. Data
The dataset used is the Cleveland dataset from the UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/45/heart+disease

An alternate version is available on Kaggle: https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

### 3. Evaluation
The goal is to achieve 95% accuracy in predicting heart disease during the proof-of-concept phase.

### 4. Features
The dataset includes the following clinical parameters:

* age: Age of the patient in years
* sex: Gender (1 = male, 0 = female)
* cp: Chest pain type
  * 0: Typical angina
  * 1: Atypical angina
  * 2: Non-anginal pain
  * 3: Asymptomatic
* trestbps: Resting blood pressure (in mm Hg)
* chol: Serum cholesterol in mg/dl
* fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
* restecg: Resting electrocardiographic results
* thalach: Maximum heart rate achieved
* exang: Exercise-induced angina (1 = yes, 0 = no)
* oldpeak: ST depression induced by exercise relative to rest
* slope: The slope of the peak exercise ST segment
* ca: Number of major vessels (0-3) colored by fluoroscopy
* thal: Thallium stress test result
* target: Target variable (1 = heart disease, 0 = no heart disease)
For a detailed data dictionary, refer to the dataset's official documentation.

### 5. Modeling
This project involves developing and experimenting with machine learning models to predict heart disease. The focus is on feature engineering, exploratory data analysis (EDA), and evaluating different algorithms to achieve the best accuracy.
