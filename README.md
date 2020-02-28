# Heart-Disease-Prediction
Use the heart disease data from UCI Machine Learning Repository to first provide an overview of current heart disease patterns and then use machine learning methods to make predictions of whether an individual has disease or not. 


INTRODUCTION
Heart disease is the leading cause of death in the United States. The frequency of this disease is increasing. Many factors will increase the risk for heart disease such as high cholesterol, high blood pressure, and diabetes. This study is going to use the heart disease data from UCI Machine Learning Repository to first provide an overview of current heart disease patterns and then use machine learning methods to make predictions of whether an individual has disease or not. We compare the methods will finally choose the best method which has highest prediction accuracy. This results of this study can help choose the suitable model to make prediction of the heart disease.
The dataset includes 303 samples. 13 attributes used in this dataset are the ones which will have effect on the heart disease. The attribute ‘num’ is the diagnosis of heart disease. The description of the attributes are as follows,


age​: age in years
sex​: sex(1 = male; 0 = female) cp​: chest pain type
-- Value 1: typical angina
-- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4: asymptomatic
trestbps​: resting blood pressure
chol​: serum cholestoral
fbs​: wheather fasting blood sugar > 120 mg/dl or not
-- Value 0: false
-- Value 1: true
restecg​: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality
-- Value 2: showing probable or definite left ventricular hypertrophy
thalach​: maximum heart rate achieved
exang​: exercise induced angina (1 = yes; 0 = no)
oldpeak​: ST depression induced by exercise relative to rest slope​: the slope of the peak exercise ST segment
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping
ca​: number of major vessels (0-3) colored by flourosopy thal​: 3 = normal; 6 = fixed defect; 7 = reversable defect num​: diagnosis of heart disease (angiographic disease status)
-- Value 0: < 50% diameter narrowing
-- Value 1: > 50% diameter narrowing
We assume that every value with 0 means heart is okay, and 1,2,3,4
means heart disease.
