📊 Exam Failure Analysis & Early Risk Detection
📌 Project Overview

Educational institutions often identify students only after they fail exams.
This project analyzes academic and behavioral data to identify students at risk of exam failure early, enabling proactive academic support.

The project focuses on data analysis and explainable logic, making it suitable for decision-making rather than black-box prediction.

🎯 Objectives

Analyze factors contributing to exam failure

Identify at-risk students using measurable metrics

Provide actionable insights for early intervention

🧠 Problem Statement

Traditional academic monitoring is reactive.
This project aims to shift toward proactive risk detection by analyzing attendance, internal assessments, study habits, and past academic history.

📂 Dataset Description

The dataset represents student performance over a semester and includes academic, behavioral, and contextual features.

🔑 Key Columns

attendance_pct – Attendance percentage

internal_marks – Internal assessment scores

assignment_score – Assignment performance

study_hours – Average daily study hours

past_failures – Number of previous failures

exam_score – Final exam score

failure_risk – Target variable (Yes / No)

🛠️ Tools & Technologies

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook

Git & GitHub

🔍 Methodology

Data cleaning and validation

Feature engineering

Exploratory Data Analysis (EDA)

Rule-based failure risk classification

Insight generation through visualization

📐 Risk Classification Logic

A student is marked At Risk if any of the following conditions apply:

- Exam score < 40
- Attendance < 65%
- Internal marks < 35
- Past failures ≥ 2


This approach ensures interpretability and transparency.

📊 Key Analysis & Visualizations

Pass vs Fail distribution

Attendance vs exam performance

Study hours vs exam score

Correlation heatmap

Impact of past failures

💡 Key Insights

Low attendance is strongly correlated with exam failure

Internal assessments are reliable indicators of final outcomes

Students with prior failures have significantly higher risk

Consistent study habits reduce failure probability

⚠️ Limitations

Rule-based logic (no ML model used)

Limited dataset size

No real-time academic tracking

🚀 Future Enhancements

Machine learning-based risk prediction

Dashboard for faculty monitoring

Integration with Learning Management Systems (LMS)

Automated early warning alerts
