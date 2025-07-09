# Student-score-predictor

Welcome to the **Student Exam Score Predictor** — a simple machine learning project that estimates a student’s average exam score using just a few inputs like:

- How many hours they study per week 📚  
- Their class attendance percentage 📅  
- Whether they participate in extracurricular activities 🏅

This app can help educators, tutors, or even students themselves identify if they might need a little extra help before exams!

## What This Project Does

We use real-world data to build and train two regression models:

-  **Linear Regression** – for simplicity and transparency
-  **Random Forest Regressor** – for better performance and accuracy

Both models are used to predict a student’s **average score** based on input features.


## How to Run This Project

1️. Train the Models
If you've just cloned the repo, run this file to train the models and save them:

```bash
python model_train.py
```
You’ll get two .pkl files:
- linear_regression_model.pkl
- random_forest_model.pkl
  
2️. Launch the App
Fire up the Streamlit app using:

```bash
streamlit run app.py
```
Enter your inputs on the sliders and see score predictions from both models. The app runs in your browser at http://localhost:8501.

## Files in This Project
student-score-predictor/
├── app.py                        # The interactive Streamlit app
├── model_train.py               # Trains and saves ML models
├── student-scores.csv           # Dataset with student info
├── linear_regression_model.pkl  # Saved Linear model
├── random_forest_model.pkl      # Saved Random Forest model
└── README.md                    # This file

