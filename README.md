# Hand_Gesture_Task-prodigy-infotech
This project focuses on recognizing hand gestures using computer vision techniques. The system detects hand landmarks in real-time and classifies gestures accordingly.
Hand Gesture Recognition Model ✋🚀
This repository contains the implementation of a Hand Gesture Recognition System developed during my internship at Prodigy Infotech. The project utilizes Computer Vision and Machine Learning to identify and classify hand gestures in real-time.
📌 Project Overview
The goal of this task was to develop a model that can accurately identify different hand gestures from image or video data. This technology enables intuitive human-computer interaction (HCI) and gesture-based control systems.
📊 Dataset
The model is trained/validated using the LeapGestRecog dataset from Kaggle, which includes 10 distinct gesture classes.
• Source: Kaggle - LeapGestRecog
• Classes include: Palm, Fist, Thumb, Index, etc.
🛠️ Tech Stack
• Language: Python 3.x
• Libraries: * OpenCV: For image processing and webcam integration.
• MediaPipe: For high-fidelity hand landmark detection and tracking.
• Matplotlib: For visualizing training performance and accuracy graphs.
• NumPy: For efficient numerical array operations.
🚀 Key Features
• Real-time Tracking: Uses MediaPipe to detect 21 hand landmarks (joints) with high precision.
• Minimal Latency: Optimized for edge devices and standard webcams without requiring heavy GPU resources.
• Gesture Logic: Implements spatial coordinate analysis to distinguish between open and closed hand states.
📈 Results
The model successfully identifies hand joints and maps them to specific gestures.
• Accuracy: High precision in landmark localization.
• Performance: Smooth real-time detection at 30+ FPS on standard hardware.

