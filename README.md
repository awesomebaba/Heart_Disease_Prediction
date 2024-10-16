# Heart Disease Prediction (Using Naive Bayes Classifier)
This project aims to predict the likelihood of **heart disease** based on various medical and physiological parameters. The prediction is performed using a Naive Bayes classifier, a probabilistic machine learning model well-suited for classification tasks.

The model is trained on several key health features and outputs whether a person is at risk for heart disease or not. The application has been deployed using Streamlit, providing an easy-to-use interface where users can input relevant health data and get an immediate prediction.

## Features
The model uses the following features as input for the prediction:

Name: Enter your name.

Age: The age of the person in years.

RestingBP: Resting blood pressure in mm Hg.

Cholesterol: Serum cholesterol level in mg/dL.

FastingBS: Fasting blood sugar level (1 if > 120 mg/dL, otherwise 0).

MaxHR: Maximum heart rate achieved during exercise.

ExerciseAngina: Whether exercise induces angina (chest pain) (Yes/No).

Oldpeak: ST depression induced by exercise relative to rest.

ST Slope: The slope of the peak exercise ST segment (options: 'Up', 'Flat', 'Down').

Chest Pain Type (CPT): Type of chest pain experienced (options: 'ATA' – Atypical Angina, 'NAP' – Non-Anginal Pain, 'ASY' – Asymptomatic, 'TA' – Typical Angina).

Resting ECG: Results of resting electrocardiogram (options: 'Normal', 'ST' – having ST-T wave abnormality, 'LVH' – showing left ventricular hypertrophy).

Sex: Gender of the individual ('Male' or 'Female').
How to Use

### Visit the deployed app at https://heartpredict001.streamlit.app/.

Input your personal and medical information into the form.
After filling all the fields, the application will predict whether you are at risk of heart disease based on the provided data.

### Technical Details
**Naive Bayes Classifier:** This classifier is used because of its simplicity and effectiveness in classification problems with categorical and continuous data.

**Streamlit:** A lightweight web framework is used to deploy the machine learning model and create an interactive user interface.
#### Deployed Link
Access the Heart Disease Prediction app here:
https://heartpredict001.streamlit.app/

#### Future Improvements
Add more features such as smoking habits, alcohol consumption, and family history of heart disease.
Explore other classifiers such as Random Forest, Logistic Regression, and SVM for potentially higher accuracy.
Incorporate visualization tools to display probability scores and feature importance.

