# drivers_drowsynesdetection
Driver Drowsiness Detection and Monitoring System

The Driver Drowsiness Detection and Monitoring System is a real-time computer vision application designed to improve road safety by continuously monitoring a driver's facial behavior and alertness level. The system uses a webcam, MediaPipe Face Landmarker, OpenCV, and Machine Learning-based facial landmark analysis to detect signs of fatigue, distraction, and microsleep while driving.

The application tracks facial landmarks such as the eyes, mouth, iris, nose, and chin to analyze driver behavior. Eye Aspect Ratio (EAR) is used to detect prolonged eye closure and drowsiness, while Mouth Aspect Ratio (MAR) is used to identify yawning events. The system also utilizes MediaPipe blendshape scores to improve blink detection accuracy.

Key features include:

Real-time Eye Closure Detection using EAR and blink scores.
Drowsiness Detection based on continuous eye closure duration.
Microsleep Detection for dangerous long-duration eye closures.
Yawning Detection using mouth opening measurements.
Gaze Tracking to determine whether the driver is looking forward, left, or right.
Head Position Monitoring to detect head-down posture.
Phone Distraction Detection by combining head-down and gaze information.
PERCLOS (Percentage of Eye Closure) calculation for fatigue assessment.
Audio Alert System to warn drivers when drowsiness or microsleep is detected.
Live Monitoring Dashboard displaying driver status and safety metrics.

The system classifies the driver's state into three categories:

Normal – Driver is attentive and alert.
Drowsy – Eyes remain closed beyond a predefined threshold.
Microsleep – Extended eye closure indicating a critical safety risk.

Technologies Used:

Python
OpenCV
MediaPipe Face Landmarker
NumPy
Streamlit (Frontend Dashboard)
Winsound Alarm System

Applications:

Smart Vehicle Safety Systems
Advanced Driver Assistance Systems (ADAS)
Fleet Management Monitoring
Driver Fatigue Detection
Road Safety Research

This project demonstrates the practical application of Computer Vision, Facial Landmark Detection, Real-Time Video Processing, and Human Behavior Analysis to reduce road accidents caused by driver fatigue and distraction.
