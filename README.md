# Attendance-Using-Face-Recognition


## Face Recognition and Attendance Management Project

This Python project utilizes face recognition to manage attendance. It captures a face image, identifies the student, records attendance in data files, and displays the captured face with the student's information.

## Features

- Face recognition using the face_recognition library.
- Attendance management and recording.
- Display of captured face with student's information.

## Prerequisites

- Python 3
- face_recognition library
- cv2 (OpenCV) library
- pandas library

## How to Use

1. **Install Dependencies:**

   Make sure you have the required libraries installed by running:
   
   ```bash
   pip install face_recognition opencv-python pandas
   ```
2. **Load Reference Data:**

    Edit the 'Student.csv' file to include student information and photo locations.
    
   **Capture a Face Image:**
    
    Run the script to capture a face image by executing:
    
    ```bash
    Copy code
    python capture_face.py
    ```
    This will save the captured image as 'StudentX.png', where X is the number of images captured.
    
 3. **Identify Student and Record Attendance:**
    
    Run the main script by executing:
    
    ```bash
    python attendance_management.py
    ```
    The script will identify the student using face recognition, record attendance in 'Attendance.txt' and 'Attendance.csv', and display the        captured face with information.
    
 4. **View Captured Face:**
    
    The captured face with information will be displayed on the screen.

