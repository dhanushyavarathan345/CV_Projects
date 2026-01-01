# CV_Projects
My Data Science &amp; Analytics Projects

Student Attendance Face Recognition


📌 Project Overview

This project automates student attendance marking using computer vision and face recognition. It not only marks students as present automatically but also allows marking absent students with reasons.

Key Benefits:

Saves time in large classrooms.

Reduces manual errors and fraudulent attendance.

Records absent reasons, e.g., “Sick,” “Late,” “On Leave,” etc.

Can be extended to multiple classrooms or institutions.

🛠️ Tools & Technologies

Programming Language: Python

Libraries: OpenCV, face_recognition, numpy, pandas

Environment: Jupyter Notebook / Python IDE

Optional: Webcam for live attendance capture

💡 How It Works

Dataset Preparation: Collect student face images and store them in a faces/ folder.

Face Encoding: Convert student faces into numerical encodings for recognition.

Real-Time Detection: Capture live video feed and detect faces.

Attendance Logging:

Automatically marks recognized students as Present.

Unrecognized or missing students can be marked as Absent with a reason.

Attendance File: Logs Date, Time, Student Name, Status, and Reason in a CSV.

🧩 Features

Recognizes multiple faces simultaneously.

Logs date, time, student name, and status automatically.

Records reason for absence manually or via input.

Easy addition of new students by updating the faces/ folder.

📈 Sample Output

CSV file with attendance:

Name	Date	Time	Status	Reason
John Doe	2026-01-01	09:00AM	Present	-
Jane Smith	2026-01-01	09:01AM	Absent	Sick
Mike Ross	2026-01-01	09:02AM	Absent	On Leave
