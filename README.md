# 🎯 Color Object Tracker (OpenCV)

This Python project uses OpenCV to detect and track a specific colored object (green) in real time using a webcam.

## 📦 Technologies
- Python 3
- OpenCV
- NumPy

## 🧠 How It Works
- Captures video from webcam
- Converts each frame to HSV
- Applies color mask to isolate object
- Detects contours and draws a box around the detected object

## ▶️ How to Run
1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Run the tracker: `python object_tracker.py`
4. Press `Q` to quit

## 📸 Output Example
<img src="demo.png" alt="demo screenshot" width="500"/>
