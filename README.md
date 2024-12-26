# HeartDiseasePrediction
This is a Machine-Learning(ML) based project to predict heart disease. This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is an integer valued 0 = no disease and 1 = disease. Attribute Information:
<p>
<br>1.)age</br>
<br>2.)sex</br>
<br>3.)chest pain type (4 values) *Value 0: typical angina *Value 1: atypical angina *Value 2: non-anginal pain *value 3: asymptomatic</br>
<br>4.)resting blood pressure (in mm Hg)</br>
<br>5.)serum cholesterol in mg/dl</br>
<br>6.)fasting blood sugar > 120 mg/dl</br>
<br>7.)resting electrocardiographic results (values 0,1,2)</br>
<br>8.)maximum heart rate achieved</br>
<br>9.)exercise-induced angina</br>
<br>10.)old peak = ST depression induced by exercise relative to rest</br>
<br>11.)the slope of the peak exercise ST segment</br>
<br>12.)number of major vessels (0-3) colored by fluoroscopy</br>
<br>13.)thal: 0 = normal; 1 = fixed defect; 2 = reversable defect The names and social security numbers of the patients were recently removed from the database, replaced with dummy values. [Exact Information available on Kaggle] </br></p>
We are applying 5 Machine Learning algorithms:- Linear Regression, Support Vector Machine(SVM), K-nearest neighbours (KNN), Random Forest Classifier And Gradient Booster. I found the Random Forest Classifier as the most accurate that is why will be using it to train final dataset and for deployment purposes. At last, I made a Graphical User Interface(GUI) for users.
