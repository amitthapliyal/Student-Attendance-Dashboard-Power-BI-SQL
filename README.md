# Student-Attendance-Dashboard-Power-BI-SQL
A Power BI &amp; SQL project for school attendance tracking. Uses CSV datasets (Students, Attendance, ScanLogs) to monitor total students, gate scans, class attendance, and skipped entries. Built with DAX queries and table relationships, providing dynamic dashboards for real-time insights.

=>Repository Contents

1-Students.csv → Master student details.
2-DailyAttendance.csv → Daily attendance records.
3-ScanLogs.csv → Logs of student scans (time, location).
4-StudentDashboard.pdf → Exported Power BI Dashboard report.
5-Dashboard Screenshot → Preview image of the dashboard.

=>Tech Stack

1-SQL Server → For staging data and managing tables.
2-Power BI Desktop → For building relationships, DAX queries, and dashboard.
3-CSV Files → Raw student, attendance, and scan log datasets.
4-DAX (Data Analysis Expressions) → To calculate metrics like skipped students, attendance %,GATE Attendence,Canteen attendence etc.

=>Workflow

1-Load Students.csv, DailyAttendance.csv, and ScanLogs.csv into SQL Server / Power BI.
2-Create relationships using StudentID.
3-Use DAX queries to calculate:
4-Total Students
5-Gate Attendance
6-Class Attendance
7-Skipped Students (entered without Main Gate scan).
8-Design a dashboard in Power BI for interactive reporting.


=>Key Insights – Student Attendance Dashboard

The dashboard dynamically changes based on date filters. Below are attendance insights for 1 September 2025. images
### 📅 1st September 2025
Total Students → 100
Gate Attendance → 61
Class Attendance → 71
Skipped Gate → 10 (students entered illegally, bypassing the main gate
![1 September Attendance](images/1dashboard.png)

### 📅 2nd September 2025
Total Students → 100
Gate Attendance → 73
Class Attendance → 81
Skipped Gate → 8
![2 September Attendance](images/2dashboard.png)

### 📅 3rd September 2025
Total Students → 100
Gate Attendance → 65
Class Attendance → 84
Skipped Gate → 19
![3 September Attendance](images/3dashboard.png)

### 📅 4th September 2025
4th September 2025
Total Students → 100
Gate Attendance → 99
Class Attendance → 100

Skipped Gate → 1
![4 September Attendance](images/4dashboard.png)

=>Trend Summary:
Skipped students fluctuated (10 → 8 → 19 → 1).
Gate attendance improved steadily (61 → 73 → 65 → 99).
Class attendance peaked at 100 by 4th September.

=>Conclusion

This project demonstrates how real-time student attendance tracking can be implemented using raw CSV logs, SQL, Power BI, and DAX. It highlights practical BI skills like ETL, data modeling, and dashboarding while solving a real-world school management problem.
