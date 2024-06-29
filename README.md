# Heart_disease_classifier

Overview:
This project is designed to classify the presence of heart disease in patients using a machine learning approach. The project employs the RandomForestClassifier from the scikit-learn library to predict heart disease based on various health metrics.

Tools Used:
Python, Pandas, NumPy, Matplotlib, Scikit-Learn

Dataset:
The dataset used in this project is the Heart Disease Dataset from the UCI Machine Learning Repository. It contains 303 instances and 14 attributes.

1. Age: Age of the patient (in years)
2. Sex: Sex of the patient (1 = male, 0 = female)
3. CP: Chest pain type
    * 0: Typical angina
    * 1: Atypical angina
    * 2: Non-anginal pain
    * 3: Asymptomatic
4. Trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
5. Chol: Serum cholesterol in mg/dl
6. FBS: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
7. Restecg: Resting electrocardiographic results
    * 0: Normal
    * 1: Having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria
8. Thalach: Maximum heart rate achieved
9. Exang: Exercise-induced angina (1 = yes, 0 = no)
10. Oldpeak: ST depression induced by exercise relative to rest
11. Slope: The slope of the peak exercise ST segment
    * 0: Upsloping
    * 1: Flat
    * 2: Downsloping
12. Ca: Number of major vessels (0-3) colored by fluoroscopy
13. Thal: Thalassemia
    * 0: Normal
    * 1: Fixed defect
    * 2: Reversible defect
14. target
