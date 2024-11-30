# Virtual Mouse Using Hand Gestures 🎮🖱️

A Python-based project that enables touchless computer interaction through real-time hand gesture recognition. This virtual mouse uses computer vision to track hand movements and perform actions like mouse movement, left-click, right-click, double-click, and taking screenshots.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
  - [Prerequisites](#prerequisites)
  - [Installation Steps](#installation-steps)
  - [Check Installation](#check-installation)
- [How to Run](#how-to-run)
- [How It Works](#how-it-works)
- [Screenshots](#screenshots)
- [License](#license)

---

## Features 🚀
- **Real-time hand tracking and gesture recognition**: Detects hand movements and converts them into mouse actions.
- **Mouse movement and actions**:
  - Move the cursor based on the index finger position.
  - Left-click, right-click, and double-click using intuitive hand gestures.
  - Take screenshots with a unique gesture.
- **Touchless interaction**: Enhances user experience and accessibility by eliminating the need for a physical mouse.

---

## Technologies Used 💻
- **Python**: Core programming language.
- **OpenCV**: Captures video feed and processes frames for hand gesture tracking.
- **MediaPipe**: Detects and tracks hand landmarks in the video feed.
- **PyAutoGUI**: Simulates mouse movement and actions.
- **Pynput**: Handles mouse button controls (left-click, right-click).

---

## Setup and Installation 🛠️

### Prerequisites
Ensure you have **Python 3.7 or above** installed. You can download it from [python.org](https://www.python.org/).

### Installation Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/virtual-mouse.git  
   cd virtual-mouse
2. **Create a Virtual Environment(optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Linux/Mac
   venv\Scripts\activate     # On Windows
3. **Install Required Dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Ensure your requirements.txt includes**:
   - opencv-python
   - mediapipe
   - pyautogui
   - pynput
5. **Check Installation**:
   To verify that all dependencies are installed correctly, run:
   ```bash
   python -c "import cv2, mediapipe, pyautogui, pynput"

   
## How to Run 🏃‍♂️
### Connect Your Webcam: Make sure a webcam is connected to your computer.

**Navigate to the Project Directory**:
```bash
    cd virtual-mouse
```
**Run the Python Script**:

```bash
  python Virtual_Mouse.py
```
**Perform Gestures to Control the Mouse**:

  - Move your index finger to move the cursor.
  - Pinch your thumb and index finger for a left-click.
  - Perform other gestures for right-click, double-click, and screenshot capture.
  - Press q to exit the application.

## How It Works 🤖
  - Capture Video Feed: OpenCV captures video frames from your webcam.
  - Hand Detection: MediaPipe detects key hand landmarks (such as fingertips and palm).
  - Gesture Recognition: Calculates distances and angles between hand landmarks to recognize gestures like pinch for a click.
  - Mouse Simulation: PyAutoGUI and Pynput simulate mouse movements and clicks based on detected gestures.

## Contributions 🤝
Feel free to contribute by:

 - Reporting issues
 - Suggesting new features
 - Creating pull requests
 - Please create an issue for any bugs or feature requests!

## Contact 📨
If you have any questions, feel free to reach out or open an issue in the repository!
