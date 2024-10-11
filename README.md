
Automatic Attendance Management System Using Facial Recognition
Overview
This project implements an Automatic Attendance Management System for institutions, using facial recognition to streamline and automate the attendance process. The system is built using lightweight algorithms like Haar Cascade and LBPH (Local Binary Patterns Histogram) for real-time face detection and recognition. Students can log in with their credentials, and once their face is scanned, the system records their attendance along with the timestamp in the database. Professors or admins can log in to view attendance records by subject.

Features
User Authentication: Secure login for students, professors, and admins.
Real-time Face Recognition: Attendance is marked through facial recognition using Haar Cascade and LBPH algorithms.
Automated Attendance Logging: Attendance records are updated in the database with a timestamp for each face scan.
Admin/Professor Access: Admins and professors can view attendance by entering a subject code.
Lightweight and Fast: The system is designed to be fast and lightweight, suitable for real-time usage in institutional settings.
Technologies Used
Programming Language: Python
Facial Recognition: OpenCV (Haar Cascade and LBPH), Dlib
Machine Learning: TensorFlow
Data Handling: NumPy, Pandas
Database: MySQL
Libraries: OpenCV, Dlib
Installation Guide
Prerequisites
Ensure you have the following installed on your system:

Python 3.x
MySQL Server
Required Python libraries:
opencv-python
opencv-contrib-python
dlib
tensorflow
numpy
pandas
mysql-connector-python
