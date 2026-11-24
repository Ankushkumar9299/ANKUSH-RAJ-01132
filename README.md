# Student Attendance & Performance Tracker (PS No. 47)

## Requirements
- Python 3
- pandas
- matplotlib

## Install libraries
```bash
python -m pip install pandas matplotlib
```

## Run
Keep `main.py` and `students.csv` in the same folder, then run:
```bash
python main.py
```

## CSV format
The file must contain these columns:
`Name, Classes_Held, Classes_Attended, Marks`

## Rules
- Attendance percentage = (Classes_Attended / Classes_Held) * 100
- A student is **At Risk** if attendance is strictly below 75% OR marks are strictly below 40.
- Invalid rows are skipped (for example, attended classes greater than classes held, marks outside 0-100, or non-numeric values).

## Menu
1. Student Report
2. Summary and Charts (bar chart and scatter chart)
3. Exit
