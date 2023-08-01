# diabetic_predictor
Diabetes Predictor
This is a diabetes predictor that uses a machine learning model to predict whether a person has diabetes or not based on their health metrics.

The health metrics collection is not advanced and has to be done manually by the user. The user has to enter the following metrics:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
The order and formatting is taken care by the application. The user just has to enter the values.
The application uses a machine learning model to predict whether the user has diabetes or not. The model is trained on the Diabetes.csv dataset.

The model uses the algorithms: Logistic Regression, Random Forest Classifier . The model with the highest accuracy is used to make the prediction.

The application is built using flask
To, run, you first need to run as follows
app.py
__init__.py
brain.py
routes.py
model.pkl
model.ipynb
Now, the model.pkl is already pre trained to have a good enough accuracy. 
If you want to train the model yourself, you can use the model.ipynb file and output to model.pkl. The application will automatically use the new model.
