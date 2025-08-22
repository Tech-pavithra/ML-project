**Heart Disease Bayesian Prediction** : 
This project predicts the probability of heart disease using a Bayesian network implemented with BayesPy. It uses patient data encoded with categorical enums.

Data : 
Input CSV (heart_disease_data.csv) includes Age, Gender, Family History, Diet, Lifestyle, Cholesterol, and Heart Disease status.

How to Run : 
Install dependencies:
pip install bayespy numpy colorama

Run the script:
python your_script_name.py

Enter patient details as guided by enum mappings to get heart disease probability.

Enum Mappings
Age: SuperSeniorCitizen(0), SeniorCitizen(1), MiddleAged(2), Youth(3), Teen(4)

Gender: Male(0), Female(1)

Family History: Yes(0), No(1)

Diet: High(0), Medium(1), Low(2)

Lifestyle: Athlete(0), Active(1), Moderate(2), Sedetary(3)

Cholesterol: High(0), BorderLine(1), Normal(2)

Heart Disease: Yes(0), No(1)
