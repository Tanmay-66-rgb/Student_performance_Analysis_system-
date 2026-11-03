# 🎓 Student Analysis System

A Streamlit dashboard for analysing student marks, with a **top navigation bar** that splits the app into sections.

| Section | What it shows |
|---|---|
| 🏠 Overview | Key metrics, insights, data preview |
| 📊 Charts | Subject averages, score distribution, grade bands, subject spread |
| 🏆 Rankings | Searchable ranking table, top/bottom 5 |
| 🆘 Support List | Students below the threshold in any subject |
| 📥 Reports | Excel workbook and CSV downloads |

## Run
```bash
pip install -r requirements.txt
python -m streamlit run app.py
```
Open http://localhost:8501. Nothing is shown until a CSV/Excel file is uploaded in the sidebar (needs a student ID/name column and numeric subject columns, marks 0–100). A sample `students.csv` is included to try it.

## Rules
- Pass rate: share of students ≥ threshold in **every** subject.
- Support list: any single subject below the threshold.
- Ranking: by average, highest first; ties share a rank.

## Files
`app.py` UI · `validation.py` checks · `analysis.py` stats · `export.py` reports · `students.csv` sample
