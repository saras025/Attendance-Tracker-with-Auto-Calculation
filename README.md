# Attendance-Tracker-with-Auto-Calculation

📝 Description
This Excel project tracks student attendance across multiple days and automatically calculates attendance percentage. It highlights low attendance for easy intervention.

🧠 Features
Mark students as Present (P) / Absent (A)
**Automatically calculates:

1)Total Working Days 
Calculate total working days excluding festival and sundays i.e holidays.
=COUNTIFS(B9:O9,"<>Sunday", B9:O9,"<>festival")
![Screenshot 2025-06-02 194744](https://github.com/user-attachments/assets/5a855a1f-d642-4d4e-b69d-f4ff4137dbcd)


2)Present Days
Calculate number of days the student is present from total working days 
=countifs(range,"P"
![Screenshot 2025-06-02 194759](https://github.com/user-attachments/assets/191514ef-7321-47dd-acd1-2de366df0c06)

3)% Attendance
calculate attendance % using (present days/working days * 100)
**Conditional Formatting to flag low attendance (<75%)**
GREEN if % greater than 75% and RED if % below 75%


![Screenshot 2025-06-02 194811](https://github.com/user-attachments/assets/282255fb-c322-4705-b732-56fe192dc2a0)






**🔧 Tools Used
*Microsoft Excel
*Formulas: COUNTIFs,Conditional Formatting :)

