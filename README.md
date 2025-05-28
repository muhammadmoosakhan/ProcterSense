# ProcterSense
ProctorSense — An AI-powered proctoring system that ensures focus and academic integrity through real-time eye, head, and hand movement detection using Python, OpenCV, and MediaPipe. Lightweight, scalable, and future-ready for education and corporate environments.

# ProctorSense 👁️‍🗨️  
**No Moves Go Unseen**

An AI-powered real-time proctoring system designed to enhance academic integrity, focus, and productivity in digital environments.

---

## 🧠 Overview
ProctorSense uses computer vision and AI to monitor:
- 👁️ Eye gaze patterns
- 🧍‍♂️ Head pose orientation
- ✋ Hand presence and visibility

This ensures secure and distraction-free experiences for:
- Online exams 📝
- Remote job interviews 👨‍💻
- Corporate productivity monitoring 🏢

---

## 🔧 Features

### 1. Eye Gaze Monitoring
- Tracks eye movement using facial landmarks.
- Flags frequent off-screen glances or unnatural gaze patterns.

### 2. Head Pose Analysis
- Estimates yaw, pitch, and roll using facial keypoints.
- Detects if a student constantly looks around during exams.

### 3. Hand Presence Monitoring
- Checks if hands are visible during the session.
- Detects sudden disappearance of hands as potential cheating behavior.

---

## 🧰 Tech Stack
- `Python 3.10+`
- `MediaPipe`
- `OpenCV`
- `dlib`
- `Torch`
- `cv2.VideoCapture` for real-time webcam input

---

## 🗂️ Project Structure

```bash
ProctorSense/
│
├── main.py                 # Entry point
├── eye.py                  # Eye tracking logic
├── head.py                 # Head pose detection logic
├── hands.py                # Hand monitoring logic
├── background.png          # Background image used in UI
├── requirements.txt        # List of dependencies
├── venv/                   # Python virtual environment
├── models/                 # Contains shape predictor & model files
├── logs/                   # Logs and screenshots 
└── dlib-wheel/             # Pre-downloaded dlib binary for Windows



## 👨‍💻 Team

### 🧠 Muhammad Moosa Khan  
**Co-Team Lead | Vision Architect | Project Manager**  
Led the project's vision, logic building, and conceptual architecture. Spearheaded creative design, team coordination, UI/UX aesthetics, and branding strategies. Played a key role in feature ideation, planning, and technical documentation.

### 💻 Hussain Mansoor Bhutto  
**Co-Team Lead | System Architect | Technical Lead**  
The technical backbone of ProctorSense. Led system integration, code compilation, debugging, and deployment. Managed model optimization and live demonstration. Also pitched the project effectively, playing a vital role in our win.

---

### 👁️ Mahnoor Noman  
**Module Contributor – Head Pose Detection**  
Worked on head pose estimation logic using MediaPipe and dlib. Assisted in dataset understanding and camera setup validations.

### 👁️ Karishma Kumari & 🖐️ Munira Quaid Joher  
**Module Contributors – Eye & Hand Tracking**  
- Karishma contributed to the **eye gaze detection module**, researching facial landmark precision and integrating detection with system input.
- Munira focused on the **hand presence monitoring module**, supporting logic structuring, feature handling, and behavioral flag triggers.

---

> 🤝 *Together, we collaborated on ProctorSense to bring vision, technical excellence, and usability under one roof — aiming to redefine digital monitoring through AI.*

