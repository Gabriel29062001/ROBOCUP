# ROBOCUP


## 🧠 Overview
This project was developed as part of the **RoboCup** robotics challenge and focuses on integrating **computer vision** and **speech interaction** for object recognition and manipulation.  
Using a trained **YOLOv5** model, the system detects target objects in real time and provides their positions in the image frame. A **speech recognition module** allows users to verbally specify the object of interest, while the system automatically captures a photo, identifies the object, and computes its coordinates.  
These coordinates are then transmitted to a **robotic arm**, enabling autonomous grasping and pick-and-place actions based on visual and verbal input.

This  project is part of my Bachelor Project at EPFL.


<p align="center">
  <a href="./assets/robocup.gif" title="RoboCup Project">
    <img src="./assets/robocup.gif" width="45%" alt="RoboCup Project Demo"/>
  </a>
</p>

---

## ⚙️ Technical Details

| Category | Details |
|-----------|----------|
| **Languages** | Python |
| **Frameworks / Libraries** | `YOLOv5` (Ultralytics), `OpenCV`, `SpeechRecognition`, `PyAudio`, `NumPy`, `Serial` |
| **Techniques** | Object detection and classification, real-time computer vision, voice command recognition, coordinate extraction, robot arm control |
| **Hardware** | USB camera or webcam, microphone, 3-DOF or 6-DOF robotic arm (serial interface) |
| **Environment** | Ubuntu 20.04, Python 3.10, VS Code |
| **Features** | End-to-end system combining speech recognition and object detection, photo capture with verbal query, real-time coordinate computation for robotic manipulation |
