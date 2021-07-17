# ML_Heartdisease

This repository contains all the codes used for the Applied Machine Learning_Heart disease Project

The used data is obtained from Kaggle: https://www.kaggle.com/ronitf/heart-disease-uci
The presence of heart disease is presented by variable "target".  It is integer valued from 0 (no presence) to 4. However, experiments with the database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0)

Input variables:

1. patientid: ID of the patient
2. age: age in years
3. sex: sex (1 = male; 0 = female)
4. cp: chest pain type -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic
5. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
6. chol: serum cholestoral in mg/dl
7. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
8. restecg: resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
9. thalach: maximum heart rate achieved
10. exang: exercise induced angina (1 = yes; 0 = no)
11. oldpeak = ST depression induced by exercise relative to rest
12. slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping
13. ca: number of major vessels (0-3) colored by flourosopy
14. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

Predicted Variable:

15. target: diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 59 through 68 in the full dataset are vessels)
