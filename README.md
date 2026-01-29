# Face Authentication Attendance System

## Project Overview
The Face Authentication Attendance System is a Python-based application that automates the attendance process using real-time face recognition. Instead of manual attendance, the system detects and recognizes faces through a webcam and marks attendance automatically, making the process faster, secure, and error-free.

## Features
- Real-time face detection using webcam
- Face recognition and matching with stored images
- Automatic attendance marking
- Secure and contactless system
- User-friendly interface
- Reduces manual errors and proxy attendance

## Technologies Used
- Python
- OpenCV
- NumPy
- Face Recognition Library
- CSV / Database (for attendance storage)

## How It Works
1. The system captures images of registered users.
2. Face encodings are generated and stored.
3. During attendance, the webcam scans faces in real time.
4. The detected face is matched with stored data.
5. If a match is found, attendance is marked automatically with date and time.

## Installation
1. Clone the repository:
git clone https://github.com/yourusername/face-authentication-attendance-system.git

2. Navigate to the project folder:
cd face-authentication-attendance-system
3. Install required libraries:

pip install -r requirements.txt


## Usage
1. Add user images to the dataset folder.
2. Run the main Python file:
python main.py

3. The webcam will open and start detecting faces.
4. Attendance will be recorded automatically.

## Advantages
- Saves time
- Contactless attendance
- Prevents fake attendance
- Accurate and efficient

## Future Enhancements
- Cloud database integration
- Mobile app connectivity
- Multi-camera support
- Admin dashboard for analytics
