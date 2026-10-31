# Student Performance Analyzer

A Data Analytics and Rule-Based Prediction System, built for **Digital Technology (25B11CA114)**, BCA Semester 1, JIIT Noida (ODD 2026).

**Team:** Prateek Sharma (BCG26266) · Shourya Joshi (BCG26297) · Saransh Chamoli (BCG26332) · Skand Chaudhary (BCG26140)
**Submitted to:** Mr. Aakash Goyal

## What it does

- Stores student records, subject-wise marks, attendance and assignment scores (SQLite)
- Calculates averages and percentages, and finds weak subjects and top performers (Pandas)
- Shows performance charts (Matplotlib)
- Classifies each student as **Good / Average / At Risk** using transparent rules
- Generates downloadable PDF, Excel and CSV reports

## Tech stack

Python · Streamlit · Pandas · Matplotlib · SQLite · scikit-learn (optional) · fpdf2 · openpyxl

## How to run (macOS / VS Code terminal)

```bash
cd ~/"digital technology/student-performance-analyzer"
python3 -m venv .venv          # create a virtual environment (first time only)
source .venv/bin/activate      # activate it (every new terminal)
pip install -r requirements.txt
streamlit run app.py           # opens the app in your browser
```

## Project status

- [x] Phase 1: Environment and project setup
- [ ] Phase 2: SQLite database
- [ ] Phase 3: Student management
- [ ] Phase 4: Marks and attendance
- [ ] Phase 5: Analytics
- [ ] Phase 6: Dashboard and charts
- [ ] Phase 7: Performance classification
- [ ] Phase 8: Reports
- [ ] Phase 9: Testing
- [ ] Phase 10: Documentation
