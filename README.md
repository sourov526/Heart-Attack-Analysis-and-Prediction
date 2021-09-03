# Heart-Attack-Analysis-and-Prediction
Heart attack is a myocardial necrosis caused by acute and persistent ischemia and hypoxia of  coronary artery which manifestations are arrhythmia, shock or heart failure, which can be fatal
A heart attack occurs when the flow of blood to the heart is blocked. The blockage is most often 
a buildup of fat, cholesterol and other substances, which form a plaque in the arteries that feed
the heart (coronary arteries). Sometimes, a plaque can rupture and form a clot that blocks 
blood flow.
We have collected a dataset from kaggle for analysis and predict heart attack. 
Our dataset has 303 records, where each record represents a person. Targetvariable is output which has a value of 1 if the person had a heart attack.
The dataset has 14 columns, 13 of them are predictor variables or features and 
one variable is the target variable. Let’s have a look at our 13 predictor variables:
‘age’ : Age of the person
‘sex’ : Gender of the person. This column has values 0 and 1. 1 means male and 0 
means female.
‘cp’ : Chest pain type
 value 1: typical angina
 value 2: atypical angina
 value 3: non-anginal pain
 value 4: asymptomatic
‘trtbps’ : Resting blood pressure (in mm Hg). High blood pressure is more likely to 
cause heart attack.
‘chol’ : Cholestoral in mg/dl fetched via BMI sensor
‘fbs’ : (fasting blood sugar>120 mg/dl) (1 = true; 0 = false)
‘resting’ : Resting electrocardiographic results 
 0 = normal
 1 = having ST-T wave abnormality ( T wave inversions and/or ST elevations
 and/or ST elevation or depression of >0.05 mV)
 2 = showing probable or definite left ventricular
 Hypertrophy by Este’s criteria
‘thalachh’ : Maximum heart rate achieved
‘exng’ : Exercise induced angina (0 = No, 1 = Yes)
‘oldpeak’ : Previous peak; slp : slope
‘caa’ : Number of major vessels (0-3) ‘thall’ : Thalium Stress Test result (0,3)
‘output’ : 0 = less chance of heart attack, 1 = more chance of heart attack
