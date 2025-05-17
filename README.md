Classroom Attendance Tracker
Overview
This Python-based Classroom Attendance Tracker helps educators efficiently record and monitor student attendance across multiple subjects. It allows users to mark attendance, edit past records, identify students with low attendance, and export attendance reports to Excel using pandas.

Features
- Mark Attendance: Input absentees and automatically track present students.
- View Attendance: Display attendance statistics subject-wise or overall.
- Edit Attendance: Modify recorded attendance for any date.
- Detained List: Identify students below the 75% attendance threshold.
- Export to Excel: Save attendance records in a .xlsx file with two sheets (overall attendance and detained list).
  
Technologies Used
- Python: Core logic implementation
- pandas: Excel file handling
- datetime: Date validation
  
How to Run
- Install dependencies:
pip install pandas
- Run the script:
python attendance_tracker.py

Possible Enhancements
- Persistent Storage: Save attendance records in a database.
- Graphical Interface: Convert the CLI tool into a GUI using Tkinter or PyQt.
- Attendance Trends: Add visualization tools like graphs for better insights.
