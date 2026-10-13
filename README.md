# Student Performance Analysis

Data analysis project completed during my Data Analyst internship at **Syntecxhub**.

The project analyzes the academic performance of 300 students across five subjects (Math, English, Science, Urdu, Computer) and finds which factors affect their results.

> **Note:** No dataset was provided, so a simulated student dataset (fixed random seed) was used. The code works with any real dataset that has the same columns.

## Objectives
- Load and preprocess the student dataset (marks, attendance, etc.)
- Analyze subject-wise and overall performance trends
- Identify factors affecting performance (study hours, attendance)
- Compare performance across different classes
- Visualize results using bar, pie and line charts
- Generate insights for improving academic results

## Tools Used
Python, pandas, numpy, matplotlib, Jupyter Notebook

## Key Findings
- Overall average marks: **69.4 / 100**, pass rate: **97.3%**
- Strongest subject: **Urdu (73.0)**, weakest subject: **Math (64.5)**
- Study hours have a strong positive correlation with marks (**r = 0.82**). Students studying 5+ hours/day average 82.5 marks vs 55.9 for under 2 hours.
- Attendance has a moderate positive correlation (**r = 0.35**). Students above 90% attendance average 73.0 vs 63.9 below 75%.
- Class A performs best (74.7) and Class C is the lowest (64.7).

## Recommendations
- Run extra practice sessions for Math
- Set a minimum 75% attendance policy
- Encourage 4-5 hours of structured study daily
- Give Class C extra teacher support and peer learning with Class A
- Identify at-risk students (low study hours and low attendance) early

## Project Structure
```
├── Student_Performance_Analysis.ipynb   # Main notebook
├── analysis.py                          # Same code as a Python script
├── students.csv                         # Raw dataset
├── students_cleaned.csv                 # Cleaned dataset
├── insights.txt                         # Insights and recommendations
├── Student_Performance_Analysis_Report.pdf
└── charts/                              # All generated charts
```

## How to Run
1. Install the libraries: `pip install pandas numpy matplotlib`
2. Open `Student_Performance_Analysis.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells (or run `python analysis.py`)

## Author
**Rizwan Ali**
B.S. Artificial Intelligence, QUEST Nawabshah
[LinkedIn](https://www.linkedin.com/in/rizwan-ali-85a2b92b6) | [GitHub](https://github.com/rizwanmadad)
