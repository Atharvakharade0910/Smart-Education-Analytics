# Smart Education Analytics and Student Performance Prediction System using Apache Spark

## Project Overview

This project develops a Smart Education Analytics Platform using Apache Spark and PySpark to analyze student academic records, attendance, online learning activities, examination scores, and placement records. The system performs data preprocessing, exploratory data analysis (EDA), ETL pipeline development, and machine learning to predict student placement status.

---

## Objectives

- Initialize Apache Spark and load educational datasets.
- Perform RDD transformations and actions.
- Implement key-value operations and persistence.
- Perform DataFrame operations including joins and aggregations.
- Analyze educational data using Spark SQL.
- Develop an ETL pipeline for data cleaning and preprocessing.
- Build a Machine Learning model using Spark MLlib.
- Predict student placement status.

---

## Dataset

Dataset used:

- Smart Education Synthetic Dataset (CSV)

The dataset contains:

- Student Information
- Attendance Percentage
- Online Learning Activities
- Examination Scores
- CGPA
- Technical Skills
- Placement Information

The dataset also contains:

- Missing Values
- Duplicate Rows
- Outliers

which are cleaned during the ETL process.

---

## Technologies Used

- Python
- Apache Spark
- PySpark
- Spark SQL
- Spark MLlib
- Google Colab
- Git & GitHub

---

## Project Workflow

1. Install PySpark
2. Initialize Spark Session
3. Load Dataset
4. Perform RDD Operations
5. Apply Key-Value Operations
6. Perform DataFrame Operations
7. Execute Spark SQL Queries
8. Develop ETL Pipeline
9. Train Machine Learning Model
10. Evaluate Model Performance
11. Save Trained Model

---

## Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Prediction:

- Placement Status
  - Placed
  - Not Placed

Evaluation Metrics:

- Accuracy
- F1 Score

---

## Project Structure

```
Smart-Education-Analytics/
│
├── data/
│   └── smart_education_single_dirty_dataset.csv
│
├── notebooks/
│   └── Case_Study_8.ipynb
│
├── README.md
├── requirements.txt
│
└── outputs/
```

---

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## Execution Steps

1. Open the notebook in Google Colab.
2. Install PySpark.
3. Upload the dataset.
4. Run all cells sequentially.
5. View EDA outputs.
6. Train the Machine Learning model.
7. Evaluate Accuracy and F1 Score.
8. Save the trained model.

---

## Output

The project generates:

- Student Attendance Analysis
- Subject-wise Performance Analysis
- Top Performing Students
- Placement Trend Analysis
- Semester-wise Academic Report
- ETL Processed Dataset
- Placement Prediction Model
- Model Accuracy and F1 Score

---

## Author

Atharva Kharade