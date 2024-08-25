# Student Performance Prediction

## Overview

This project aims to analyze the influence of attendance rates on student performance and predict student categories such as "High Achiever" or "Struggling Student" using machine learning algorithm. The project utilizes a Random Forest Classifier to build a predictive model based on various features.

## Data

The dataset used in this project is `student_performance.csv`, which contains the following columns:
- `StudentID`: Unique identifier for each student (not used in modeling)
- `Name`: Name of the student (not used in modeling)
- `Gender`: Gender of the student
- `AttendanceRate`: Percentage of classes attended
- `StudyHoursPerWeek`: Average hours spent studying per week
- `PreviousGrade`: Grade obtained in previous assessments
- `ExtracurricularActivities`: Indicator of participation in extracurricular activities (integer)
- `ParentalSupport`: Level of parental support ('Low', 'Medium', 'High')
- `FinalGrade`: Final grade obtained by the student

## Installation

Ensure you have Python installed on your system. You can install the required libraries using pip:

```bash
pip install pandas scikit-learn matplotlib
