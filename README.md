# User-Authentication
Face Recognition System with DeepFace

This project implements a real-time face verification system using Python, OpenCV, and the DeepFace library. It captures live video feed from a webcam and compares it with a reference image to check for a face match.  

---

Features
- Real-Time Face Detection: Captures live frames from the webcam.
- Face Verification: Uses the DeepFace library to verify if the detected face matches a reference image.
- Threaded Processing: Utilizes threading to ensure smooth and efficient frame processing.
- User Feedback: Displays "MATCH!" or "NO MATCH!" directly on the video feed based on verification results.

---

Prerequisites
Libraries and Tools
Ensure the following dependencies are installed:
- Python 3.7+
- OpenCV
- DeepFace
- NumPy

Install the required libraries using:
pip install opencv-python-headless deepface numpy

Hardware Requirements
- A functional webcam
- A saved reference image named photo.jpg in the same directory as the script

---

How to Run
1. Clone this repository:
   git clone https://github.com/your-username/face-recognition-deepface.git
2. Navigate to the project directory:
   cd face-recognition-deepface
3. Place the reference image (photo.jpg) in the directory.
4. Run the script:
   python face_recognition.py

---

Key Functions
- check_face(frame): Verifies if the given frame matches the reference image.
- Threading: Ensures the verification process runs asynchronously to maintain video stream performance.

---

Usage
- Launch the script to start the video feed.
- A green "MATCH!" or red "NO MATCH!" will display on the screen based on face verification.
- Press q to quit the application.


Limitations
- The script relies on DeepFace’s verify method, which may encounter errors for unclear or misaligned faces.
- Performance may vary depending on hardware and lighting conditions.

---

Contribution
Feel free to submit issues and pull requests to improve this project. Contributions are always welcome!

---

License
This project is licensed under the MIT License. See the LICENSE file for details.

