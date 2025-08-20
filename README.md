# 🖐️ Index Finger Swipe Gesture Control

This project uses **OpenCV**, **MediaPipe**, and **PyAutoGUI** to detect hand swipe gestures with your **index finger** and simulate keyboard arrow key presses.  
It allows you to control applications (like slideshows, games, or media players) using only your hand movements.

---

## ✨ Features
- Detects index finger tip using **MediaPipe Hands**.
- Recognizes **swipe gestures**: `left`, `right`, `up`, `down`.
- Simulates keyboard arrow keys with **PyAutoGUI**.
- Visualizes detected hand landmarks in real-time via webcam.
- Cooldown system to prevent accidental multiple key presses.

---

## 🛠️ Tech Stack
- **Python 3**
- [OpenCV](https://opencv.org/) – For webcam access and visualization.
- [MediaPipe](https://mediapipe.dev/) – For hand tracking.
- [PyAutoGUI](https://pyautogui.readthedocs.io/) – For simulating key presses.

---

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/index-finger-swipe-control.git
   cd index-finger-swipe-control
