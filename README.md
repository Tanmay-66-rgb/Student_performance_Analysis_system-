## 🎓 Student Analysis System

A Streamlit dashboard for analysing student marks, with a **top navigation bar** that splits the app into sections.

| Section | What it shows |
|---|---|
| 🏠 Overview | Key metrics, insights, data preview |
| 📊 Charts | Subject averages, score distribution, grade bands, subject spread |
| 🏆 Rankings | Searchable ranking table, top/bottom 5 |
| 🆘 Support List | Students below the threshold in any subject |
| 📥 Reports | Excel workbook and CSV downloads |

## 📌 About the Project
The Student Performance Analytics System is a Python-based dashboard designed to help teachers and educators understand student performance through data analysis and visualization.

Instead of manually calculating marks and rankings, users can upload a CSV or Excel file and instantly explore academic results through an interactive dashboard.

## 📊 How It Works
Launch the application.
Upload your student dataset in CSV or Excel format.
Review the uploaded data and its validation results.
Explore class statistics, subject charts, and student rankings.
Identify students who need additional academic support.
Export the generated reports for further use.


## 👀Check out : https://student-performance-analytics-tpb.streamlit.app/

## Rules
- Pass rate: share of students ≥ threshold in **every** subject.
- Support list: any single subject below the threshold.
- Ranking: by average, highest first; ties share a rank.

## Files
`app.py` UI · `validation.py` checks · `analysis.py` stats · `export.py` reports · `students.csv` sample
