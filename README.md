# Hand Gesture Controlled Pioneer P3-DX Robot (MediaPipe + CoppeliaSim)

Overview
This project implements a real-time hand gesture control system for the Pioneer P3-DX differential-drive robot using **MediaPipe Hand Tracking**, **OpenCV**, and **CoppeliaSim**.

Features
- Real-time gesture detection (0–5 fingers)
- Commands: Stop, Forward, Backward, Turn Left, Turn Right
- Smooth gesture filtering with deque averaging
- Full integration with CoppeliaSim using ZMQ Remote API
- Human–Robot Interaction via camera

Technologies
Python · OpenCV · MediaPipe · CoppeliaSim · ZMQ Remote API

Code Highlights
- Gesture recognition using hand landmarks  
- Clean control mapping to differential-drive motors  
- Lightweight + fast real-time performance  

How to Run
1. Install dependencies  
2. Start CoppeliaSim  
3. Run the script:  
