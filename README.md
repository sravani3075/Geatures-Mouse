# 🖐️ Finger Mouse (Hand Gesture Virtual Mouse)

A computer vision-based virtual mouse that lets users interact with their computer using hand gestures. The system tracks hand movements through a webcam and converts specific gestures into mouse actions such as cursor movement, clicking, and holding.

---

🚀 Features

* Control the cursor using the index finger
* Perform mouse clicks with a thumb + middle finger gesture
* Hold the mouse button using all five fingers
* Smooth and responsive hand tracking
* Real-time webcam-based operation

---

🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* PyAutoGUI

---

📦 Installation

Install the necessary Python packages using:

```bash
pip install opencv-python mediapipe pyautogui
```

---

▶️ How to Run

Execute the following command:

```bash
python finger_mouse.py
```

---

⚠️ Important Note

Download the required MediaPipe hand-tracking model from:

https://storage.googleapis.com/mediapipe-models/hand_landmarker/hand_landmarker/float16/1/hand_landmarker.task

After downloading, keep the `hand_landmarker.task` file in the **same directory** as the Python program.

---

🎮 Controls

* ☝️ Index Finger → Move the Mouse Cursor
* 🤏 Thumb + Middle Finger → Perform a Click
* 🖐️ All 5 Fingers → Hold the Mouse Button

---

📌 Future Improvements

* Add right-click gesture support
* Implement gesture-based scrolling
* Enhance tracking precision and stability

---

💼 Author

Sravani

---

⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!
