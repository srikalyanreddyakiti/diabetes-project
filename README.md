🩺 Diabetes Prediction Project
This project is an end-to-end implementation of a machine learning model to predict the likelihood of diabetes in patients, based on medical parameters such as glucose levels, BMI, age, insulin levels, and more. The project also includes a web-based interface built with Flask for real-time prediction.

📌 Overview
Project Title: Diabetes Prediction

Student: Akiti Sri Kalyan Reddy

ID No.: 19STUCHH010130

Discipline: Data Science & Artificial Intelligence (DSAI)

Institution: ICFAI Tech, IFHE University, Hyderabad

Faculty Guide: Mr. Deevena Raju

Course: Data Warehousing and Mining

Duration: 10 Days (17/11/2021 – 27/11/2021)

🔍 Problem Statement
To develop a predictive model that classifies whether a person has diabetes using patient medical data. The model is deployed as a Flask web application.

🔧 Technologies & Tools Used
Programming Language: Python

IDE: VSCode

Web Framework: Flask

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Joblib

Frontend: HTML, CSS

Platform: Jupyter Notebook via Anaconda Navigator

📊 Dataset
Source: Pima Indians Diabetes Dataset

Provided by: National Institute of Diabetes and Digestive and Kidney Diseases

Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, Outcome (0 or 1)

📈 Workflow Summary
Data Collection

Source: Public dataset specific to Pima Indian heritage

Online research and documented data references

Data Preprocessing

Missing values replaced with NaN

Feature scaling using MinMaxScaler

Selected top features based on correlation heatmap

Data Visualization

Heatmaps, count plots, and bar plots for EDA

Insights on feature relevance with diabetes outcome

Modeling

Algorithm Used: Support Vector Classifier (SVC)

Hyperparameters: kernel, gamma, C

Evaluation: Accuracy Score, Confusion Matrix, Classification Report

Model Deployment

Built using Flask with routing, templates, and styling

Accepts user inputs via HTML form and returns predictions

🖥️ How to Run the Project
Clone this repository

Install required dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn flask

Launch the Flask app:
python app.py

Open the local web server in your browser (usually http://127.0.0.1:5000/)

Enter input values and get real-time diabetes prediction

✅ Conclusion
Successfully built a functional diabetes prediction model

Learned the full ML lifecycle: data analysis, preprocessing, modeling, evaluation, and deployment

The same approach can be extended to other medical conditions such as breast cancer or malaria

Future scope includes adding more features and improving model accuracy with advanced algorithms

📚 References
https://towardsdatascience.com/end-to-end-data-science-example-predicting-diabetes-with-logistic-regression-db9bc88b4d16

https://medium.com/analytics-vidhya/building-a-diabetes-predictor-4702b99bc7e4

https://www.python.org/

https://www.questionpro.com/blog/data-collection/
