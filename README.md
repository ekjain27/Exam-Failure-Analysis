🎯 Exam Failure Analysis & Early Risk Detection 📉🎓
📌 Project Overview

Educational institutions often identify students after they fail exams, leaving little scope for timely intervention.
This project analyzes academic and behavioral data to detect students at risk of exam failure early, enabling proactive academic support.

The focus is on explainable, metric-driven analysis rather than black-box prediction models.

🎯 Problem Statement

Students fail exams due to a combination of factors such as:

Poor attendance

Low internal assessment scores

Inconsistent study habits

History of past academic failures

However, these indicators are often analyzed in isolation.
This project combines multiple measurable signals to systematically identify failure risk before exams occur.

🎯 Objectives

Analyze key factors contributing to exam failure

Identify at-risk students using clear, interpretable rules

Support early academic intervention through data insights

📂 Dataset Description

The dataset represents student performance over a semester and includes academic, behavioral, and contextual attributes.

🔑 Key Features

attendance_pct – Percentage of classes attended

internal_marks – Internal assessment scores

assignment_score – Assignment performance

study_hours – Average daily study hours

past_failures – Number of previous exam failures

exam_score – Final exam score

failure_risk – Target variable (Yes / No)

🛠️ Tech Stack & Tools

Python

Pandas – Data cleaning and manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook

Git & GitHub

🔍 Methodology

Data cleaning and validation

Feature engineering

Exploratory Data Analysis (EDA)

Rule-based risk classification

Insight generation using visualizations

📐 Failure Risk Classification Logic

A student is classified as At Risk if any of the following conditions apply:

• Exam score < 40
• Attendance < 65%
• Internal marks < 35
• Past failures ≥ 2


This approach ensures transparency and interpretability, making results easy to understand for non-technical stakeholders.

📊 Exploratory Data Analysis

The analysis includes:

Pass vs Fail distribution

Attendance vs exam performance

Study hours vs exam score

Impact of past failures

Correlation heatmap of numerical features

💡 Key Insights

Low attendance is strongly associated with exam failure

Internal assessments are reliable predictors of final outcomes

Students with prior failures face significantly higher risk

Consistent study habits reduce failure probability

⚠️ Limitations

Rule-based logic (no machine learning model used)

Limited dataset size

No real-time academic tracking

🚀 Future Enhancements

Machine learning–based failure prediction

Faculty dashboard for monitoring risk

Integration with Learning Management Systems (LMS)

Automated early warning alerts

📁 Project Structure
exam-failure-analysis/
│
├── exam_data.csv
├── failure_analysis.ipynb
├── README.md
└── .gitignore

▶️ How to Run the Project

Clone the repository

Open failure_analysis.ipynb in Jupyter Notebook

Run the cells sequentially

💼 Use Case

Academic risk monitoring

Student performance analytics

Education-focused data analysis projects

👤 Author

Ekansh Jain
Aspiring Data Analyst / Intern

⭐ Conclusion

This project demonstrates how simple, explainable data analysis can help institutions identify exam failure risk early and support better academic outcomes.
