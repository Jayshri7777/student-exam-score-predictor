# Student Exam Score Predictor

A machine learning web application that predicts student exam scores based on various factors including study hours, attendance, mental health, sleep patterns, and part-time job status.

## Features

- **Interactive Sliders**: Adjust study hours per day, attendance percentage, mental health score, and sleep hours
- **Part-time Job Toggle**: Select whether the student has a part-time job
- **Real-time Prediction**: Get instant exam score predictions as you adjust the parameters
- **Clean Interface**: User-friendly dark theme interface built with Streamlit

## How to Use

1. Adjust the sliders for:
   - Study Hours per Day (0-12 hours)
   - Attendance Percentage (0-100%)
   - Mental Health Score (1-10 scale)
   - Sleep Hours per Day (0-12 hours)

2. Select whether the student has a part-time job

3. Click "Predict Exam Score" to get the predicted score

## Technology Stack

- **Frontend**: Streamlit
- **Machine Learning**: Scikit-learn
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly

## Installation

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Files Structure

```
student-exam-predictor/
├── app.py                 # Main Streamlit application
├── best_model.pkl         # Trained ML model
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## Model Information

The prediction model considers multiple factors that influence academic performance:
- Study time dedication
- Class attendance consistency
- Mental health and well-being
- Sleep quality and duration
- Work-life balance (part-time job impact)

## Live Demo

https://student-exam-score-predictor-bypqoudhaafjhwnioup7zn.streamlit.app/

---

*This project demonstrates the application of machine learning in educational analytics and student performance prediction.*
