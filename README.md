<h1>Real-Time 3D Pose Estimation & Action Recognition POC</h1>

This repository serves The objective is to efficiently bridge real-time video capture with structured data preparation for advanced 3D Human Pose Estimation and sequential Fine-Grained Action Recognition modules.

---

🚀 **Execution Instructions**

**A. Setup and Installation**

Clone the Repository:

**git clone** [https://github.com/Sakshi17-st/Real-Time-2D-Pose-Detector-POC.git]
cd 3d-pose-poc


**Install Dependencies:** (Requires Python 3.9+ for MediaPipe/PyTorch compatibility)
```
**pip install -r requirements.txt**
```

**B. Running the Tracker**

Run the main Python script. The script will automatically open your default webcam and start the real-time detection. Press 'q' to exit the application.
```
**python pose_tracker.py**
```

**C. Output Artifact**

📌 Output of the Real-Time 2D Pose Tracker

✔ Real-time pose tracking using webcam
✔ 33-body-joint skeleton drawn live
✔ Frame-by-frame 2D keypoints logged to 2d_keypoints_log.csv
✔ FPS displayed on screen for performance monitoring
✔ Application closes on pressing Q
✔ Pipeline prepared for:

2D → 3D pose lifting (Phase 2)

Action recognition using LSTM (Phase 3)

---

