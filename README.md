# AI-Virtual-Personal-Fitness-Coach
An AI-powered virtual fitness trainer that uses pose estimation to provide real-time feedback during workouts.

📌 Overview
This project captures webcam video and uses MediaPipe’s pose estimation model to detect key body points. It calculates joint angles and counts exercise repetitions such as squats or bicep curls, ensuring form accuracy.

🎯 Features
- Real-time pose tracking
- Exercise repetition counter
- Visual feedback with joint angles
- Webcam-based interface

🛠️ Tools Used
- Python 3.7+
- OpenCV – Video stream processing
- MediaPipe – Human pose estimation
- NumPy – Mathematical computations

🚀 How It Works
1. Capture live webcam feed.
2. Use MediaPipe to identify key landmarks (e.g., shoulder, elbow, wrist).
3. Compute joint angles and detect range of motion.
4. Count valid reps when full movement is completed.

📷 Sample Output
Real-time video frame with body landmarks and angle overlays.

📁 Run the Code
pip install opencv-python mediapipe numpy
python fitness_coach.py
