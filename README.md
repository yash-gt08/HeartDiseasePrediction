# HeartDiseasePrediction
This is a Machine-Learning(ML) based project to predict heart disease. This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is an integer valued 0 = no disease and 1 = disease. Attribute Information:

age
sex
chest pain type (4 values) *Value 0: typical angina *Value 1: atypical angina *Value 2: non-anginal pain *value 3: asymptomatic
resting blood pressure (in mm Hg)
serum cholesterol in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise-induced angina
old peak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by fluoroscopy
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. [Exact Information available on Kaggle]
We are applying 5 Machine Learning algorithms:- Linear Regression, Support Vector Machine(SVM), K-nearest neighbours (KNN), Random Forest Classifier And Gradient Booster. I found the Random Forest Classifier as the most accurate that is why will be using it to train final dataset and for deployment purposes. At last, I made a Graphical User Interface(GUI) for users.
