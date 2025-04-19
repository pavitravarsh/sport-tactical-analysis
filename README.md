# ⚽🏀 Sports Tactical Analysis System 🎾🏐  
A computer vision-based tactical analysis platform for team sports like football and tennis. This project performs player and ball detection, tracking, and movement analysis using deep learning and classical computer vision techniques.

---

## 📌 Features

- 🎯 Real-time player and ball detection using **YOLOv8**
- ➡️ Object tracking with **SORT (Simple Online Realtime Tracking)**
- 📐 Camera motion estimation and **perspective transformation**
- 🏃 Speed and distance calculations of tracked entities
- 📊 Tactical visualizations including:
  - Heatmaps of player movement
  - Ball possession & distribution
  - Mini-court overlay
- 🔁 Stub mode for replaying precomputed detections for faster debugging

---

## 🛠️ Tech Stack

- **Languages:** Python
- **Libraries:** OpenCV, NumPy, Matplotlib, Pandas
- **Models:** YOLOv8 (Ultralytics), SORT (Kalman Filter + IoU-based tracking)
- **Frameworks:** PyTorch, Flask (for future integration)
- **Tools:** Jupyter, Pickle (for saving stubs), Git

---


